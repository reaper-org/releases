Reaper 0.1.2 — macOS (UI build 415)

**Install:** download the **DMG for your Mac** below (Apple Silicon or Intel). This release ships **DMG installers only** — not source archives.

| Mac | Download |
|-----|----------|
| Apple Silicon (M1/M2/M3/M4) | `reaper-0.1.2-macos-arm64.dmg` |
| Intel (2015–2020 MacBook Pro, iMac, etc.) | `reaper-0.1.2-macos-x86_64.dmg` |

Requires **macOS 11 (Big Sur)** or later. Drag Reaper.app to Applications, then launch.

**First launch:** ad-hoc signed builds may require right-click → Open once, or allow in System Settings → Privacy & Security.

### What's new (build 415)

- **Launch splash** — animated Reaper logo with theme-stable rounded SVG and "Starting IDE…" status
- **Welcome screen** — logo animation fixes across all themes (including Off-White)
- **pubspec.yaml** — Dart/Flutter project detection and run support (like Cargo.toml)
- **Pre-push secret scan** — warns before push when env/properties files may contain secrets

**Tip:** Configure your Cursor API key in Settings → Cursor agent on each Mac.

SHA256 (arm64): `64271ce7a9c600ee6d41a052221c5ad4a3da3da145a1a63dc33c69c54b34b1ee`

SHA256 (x86_64): `14cf6b243a8eebc9fd2df4125db08ec9a783b036f008dfefdb92416a5d47af4b`
