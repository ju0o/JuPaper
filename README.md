# JuPaper

> **Write first. Organize later.**

JuPaper is a local-first freehand notebook for people who think better when handwriting, sketches, arrows, text, and images can live together without forcing structure too early.

The core rule is simple:

> The notebook should not interrupt the thought just because the thought is messy.

## What JuPaper supports

- freehand pen and highlighter
- eraser and text
- multiple notebooks and pages
- undo / redo
- page reordering
- image paste and import
- lasso and grouped movement
- simple shape and arrow assistance
- automatic local saving
- rolling recovery snapshots
- cross-notebook search groundwork
- offline iPad writing
- Apple Pencil support
- QR device pairing
- per-device authentication and revoke
- private Windows ↔ iPad sync
- Windows app packaging and installer flow
- checksum-verified update / rollback flow

## Local-first by default

Original handwriting and sketches remain canonical.

Search, OCR, and future AI understanding are treated as derived layers. They should never silently replace or rewrite the original page.

## Device model

JuPaper is being built around a practical two-device workflow:

```text
Windows desktop
  ↕ private sync
iPad + Apple Pencil
```

The notebook remains useful offline, while synchronization is an optional layer rather than a requirement for writing.

## Status

**V1 candidate / pre-release.**

The current build includes the main notebook workflow, offline-first storage, recovery, device pairing, private synchronization, and Windows packaging infrastructure.

A stable public installer will be published only after the remaining real-device, privacy, signing, and release checks are complete.

## Release path

```text
Private Alpha → Beta → 1.0 RC → V1
```

Pre-release builds are intentionally prevented from silently updating to a nonexistent stable artifact.

## Product principles

- Writing must stay fast and low-friction.
- The original page is the source of truth.
- Offline use should remain useful.
- Recovery matters as much as editing.
- Sync should be optional and understandable.

## License

Distribution and source-code licensing terms will be finalized with the first stable public release.
