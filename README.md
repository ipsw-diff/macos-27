# macOS 27 firmware diffs

Browsable firmware-diff payloads for macOS 27, published from
[`blacktop/ipsw-diffs`](https://github.com/blacktop/ipsw-diffs).

## Available diffs

- [27.0 (26A5378n) vs. 27.0 (26A5388g)](diffs/27_0_26A5378n_vs_27_0_26A5388g/README.md)
  ([manifest](manifests/27_0_26A5378n_vs_27_0_26A5388g.json))

## Layout

- `diffs/` contains the browsable Markdown payload.
- `manifests/` contains machine-readable provenance and integrity metadata.
- `track.json` contains the reviewed macOS 27 selector and merged baseline.

## Discovery

The manual, read-only discovery workflow calls the catalog detector at an
immutable commit. It accepts no OS, device, major, or build overrides and does
not download firmware, generate diffs, push branches, or open pull requests.

This repository is an initial sharding pilot. The source repository remains the
authoritative legacy corpus until the migration catalog and publication workflow
are validated end to end.
