# Direct shard generation closure

Recorded: 2026-08-13

## Claim and scope

Question: can the macOS 27 shard generate its next reviewed forward diff,
publish it on a review branch, and prove that branch is the new current track
without guessing source identity or writing directly to `main`?

- First lifecycle stage: a maintainer manually dispatches the workflow from
  the default branch with no caller-controlled build inputs.
- Last lifecycle stage: the workflow validates the two-commit publication
  branch, atomically pushes it with its permanent source tag, and emits a
  pull-request handoff URL.
- Supported claim after a successful hosted run: the exact AppleDB-resolved and
  hash-verified IPSW pair produced one immutable payload tree, canonical shard
  metadata, and a branch whose detector result is `current`.
- Excluded: opening or merging the shard pull request, central catalog
  insertion, scheduling future discovery, and external announcements.

## Authority map

| Property | Authority |
| --- | --- |
| Track identity and baseline | Reviewed `track.json` plus terminal merged manifest |
| Latest release identity | Catalog detector at its immutable workflow pin |
| Firmware bytes | Exact `ipsw dl appledb` records plus verified sizes and SHA-256 values |
| Diff transformation | Pinned `ipsw` release and exact command flags |
| Payload identity | Git tree in the payload-only source commit and permanent source tag |
| Manifest and README | Catalog tooling at its immutable commit |
| Publication state | Git branch/tag refs and GitHub compare URL |

## Feature-closure matrix

| Stage | Required evidence | Status before hosted run |
| --- | --- | --- |
| Selection and trigger | Default-branch `workflow_dispatch`; no build inputs | Unresolved |
| Inputs and resources | Detector builds, unambiguous `ipsw` URL records, and verified bytes | Unresolved |
| Transformation and signing | Pinned `ipsw`; exact flags; unsigned Git commits | Unresolved |
| Advertisement and options | No schedule or caller overrides; least-privilege job permissions | Unresolved |
| Dispatch and transport | Atomic source-tag/branch push and review handoff | Unresolved |
| State transition | Payload-only source commit then metadata/publication commit | Unresolved |
| Outcome oracle | Equal source/destination Git trees and branch discovery `current` | Unresolved |

## Expected phase inventory

Exactly one forward candidate from the reviewed track is accepted. `ipsw`
must resolve exactly one active Apple CDN IPSW record for both the terminal
baseline and candidate. Exactly two verified IPSW files, one generated payload
directory, one source commit, one permanent source tag, one publication commit,
one manifest, one provenance record, and one review handoff are expected.

## Negative evidence and stop conditions

A green discovery job alone does not prove acquisition, generation, or
publication. The workflow stops on a non-default dispatch ref, no forward
candidate, an existing payload or branch, ambiguous URL records, byte or hash
mismatch, unexpected generated paths, a stale rendered README, a signed
commit, an existing or mismatched source tag, unequal Git trees, a dirty
worktree, or a post-publication detector result other than `current`.

## Bounded conclusion

All rows remain unresolved until the workflow is merged and a hosted candidate
run supplies direct evidence. A pull-request check can validate the workflow's
read-only discovery surface but cannot stand in for the costly generation run.
