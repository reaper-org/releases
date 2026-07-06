Reaper 0.1.2 — macOS (UI build 416)

**Install:** download the **DMG for your Mac** below (Apple Silicon or Intel). DMG installers only — not source archives.

| Mac | Download |
|-----|----------|
| Apple Silicon (M1/M2/M3/M4) | `reaper-0.1.2-macos-arm64.dmg` |
| Intel (2015–2020 MacBook Pro, iMac, etc.) | `reaper-0.1.2-macos-x86_64.dmg` |

Requires **macOS 11 (Big Sur)** or later. Drag Reaper.app to Applications, then launch.

### What's new (build 416)

- **Logo** — rounded SVG (`rx=12`), no CSS wrapper chrome; splash and welcome use `drop-shadow` only
- **Welcome page** — theme-stable logo animation (fixes Off-White white flash)
- **Launch splash** — cache-busted logo/splash assets so updates load reliably
- **pubspec.yaml** — Dart/Flutter project detection and run support

**Tip:** After installing, confirm build **416** in the status bar or console: `document.querySelector('meta[name=reaper-ui-build]').content`

SHA256 (arm64): `65998fa82c50fc2d06396a1fc8614e494c6f2568336e2119015c504828132b68`

SHA256 (x86_64): `6ef3e7364e6307ef5087158bb932d045e3d65f3a7af80572f922a04d76acdbc7`
