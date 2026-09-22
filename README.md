# JuPaper

**Write first. Organize later.**

JuPaper is a local-first freehand notebook for people who prefer the freedom of paper: handwriting, rough sketches, arrows, strike-throughs, diagrams, images, and text can live on the same page without forcing structure first.

## Status

JuPaper is currently in **V1 Candidate / Founder Soak**.

The active source repository remains private while the final public-distribution gates are completed. The Windows build now has a native packaged app/installer, offline-first notebooks, iPad/Apple Pencil support, private device sync, recovery/backups, update/rollback plumbing, and automated Windows install/uninstall regression gates.

Current capabilities include:

- freehand pen, highlighter, eraser, text
- multiple notebooks and pages
- undo/redo and page reorder
- image paste/import, lasso/group move, shape/arrow assist
- local automatic saving and rolling recovery snapshots
- cross-notebook search foundation
- offline iPad writing
- QR pairing, per-device authentication and revoke
- Pencil-only palm-rejection mode
- private Windows/iPad synchronization through Tailscale HTTPS
- standalone Windows app + one-click installer pipeline
- checksum-verified update/rollback pipeline

## Product direction

JuPaper is designed around a simple rule:

> The notebook should not interrupt the thought just because the thought is messy.

Original handwriting and sketches remain canonical. Search/OCR/AI understanding are derived layers and should never silently rewrite what the user actually wrote.

## Public release

This repository is the public product/release channel. The stable V1 installer will be published here only after the remaining real-device/privacy/signing release decisions are complete.

Current development stage:

`Private Alpha → Beta → 1.0 RC → Founder Soak → V1`

No `update.json` is published yet, so pre-release builds cannot accidentally auto-update to a nonexistent public artifact.

## License

No source-code license is granted from this public repository at this stage. The public/commercial distribution terms will be finalized with the first stable release.
