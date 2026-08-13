# Direct shard generation closure

Recorded: 2026-08-13

## Claim and scope

Question: can the macOS 27 shard generate the reviewed beta 4 to beta 5 diff,
publish it on a review branch, and prove that branch is the new current track
without guessing source identity or writing directly to `main`?

- First lifecycle stage: a maintainer manually dispatches the workflow from
  the default branch with no caller-controlled build inputs.
- Last lifecycle stage: the workflow validates the two-commit publication
  branch, atomically pushes it with its permanent source tag, and emits a
  pull-request handoff URL.
- Supported claim after a successful hosted run: the exact pinned IPSW pair
  produced one immutable payload tree, canonical shard metadata, and a branch
  whose detector result is `current`.
- Excluded: opening or merging the shard pull request, central catalog
  insertion, scheduling future discovery, and external announcements.

## Authority map

| Property | Authority |
| --- | --- |
| Track identity and baseline | Reviewed `track.json` plus terminal merged manifest |
| Latest release identity | Catalog detector at its immutable workflow pin |
| Firmware bytes | Pinned Apple CDN URLs, sizes, and SHA-256 values |
| Diff transformation | Pinned `ipsw` release and exact command flags |
| Payload identity | Git tree in the payload-only source commit and permanent source tag |
| Manifest and README | Catalog tooling at its immutable commit |
| Publication state | Git branch/tag refs and GitHub compare URL |

## Feature-closure matrix

| Stage | Required evidence | Status before hosted run |
| --- | --- | --- |
| Selection and trigger | Default-branch `workflow_dispatch`; no build inputs | Unresolved |
| Inputs and resources | Exact baseline/candidate metadata and verified IPSW bytes | Unresolved |
| Transformation and signing | Pinned `ipsw`; exact flags; unsigned Git commits | Unresolved |
| Advertisement and options | No schedule or caller overrides; least-privilege job permissions | Unresolved |
| Dispatch and transport | Atomic source-tag/branch push and review handoff | Unresolved |
| State transition | Payload-only source commit then metadata/publication commit | Unresolved |
| Outcome oracle | Equal source/destination Git trees and branch discovery `current` | Unresolved |

## Expected phase inventory

Exactly one candidate is accepted: macOS 27 beta 5, build `26A5406e`, after
baseline beta 4, build `26A5388g`. Exactly two IPSW files, one generated
payload directory, one source commit, one permanent source tag, one publication
commit, one manifest, one provenance record, and one review handoff are expected.

## Negative evidence and stop conditions

A green discovery job alone does not prove acquisition, generation, or
publication. The workflow stops on a non-default dispatch ref, a different
latest build, an existing payload or branch, ambiguous downloads, byte or hash
mismatch, unexpected generated paths, a stale rendered README, a signed
commit, an existing or mismatched source tag, unequal Git trees, a dirty
worktree, or a post-publication detector result other than `current`.

## Bounded conclusion

All rows remain unresolved until the workflow is merged and a hosted beta 5
run supplies direct evidence. A pull-request check can validate the workflow's
read-only discovery surface but cannot stand in for the costly generation run.
