# CATLOG

Transparent release catalog for the `Nexus` repository.

## Purpose
- Keep release history auditable and easy to review.
- Record exactly what was shipped, when, from which branch, and with which artifacts.
- Flag pre-release limitations clearly.

## Entry Format
- `Version`:
- `Release Date` (UTC):
- `Type` (`pre-release` or `stable`):
- `GitHub Release URL`:
- `Target Branch`:
- `Commit`:
- `Highlights`:
- `Artifacts`:
- `Known Notes / Limitations`:

---

## v0.1.0-pre.1
- Version: `v0.1.0-pre.1`
- Release Date (UTC): `2026-03-22`
- Type: `pre-release`
- GitHub Release URL: `https://github.com/soumo-git/Nexus/releases/tag/v0.1.0-pre.1`
- Target Branch: `dev`
- Commit: `ed6d21b`
- Highlights:
  - First public Nexus pre-release from the monorepo.
  - Parent and Child Android release APKs generated.
  - Parent Desktop Windows installer generated.
- Artifacts:
  - `Nexus-Parent-Desktop-v0.1.0-pre.1-Setup.exe`
  - `Nexus-Parent-Android-v0.1.0-pre.1-unsigned.apk`
  - `Nexus-Child-Android-v0.1.0-pre.1-unsigned.apk`
- Known Notes / Limitations:
  - Android APKs are unsigned release builds.
  - This release is intended for validation/testing, not production rollout.
