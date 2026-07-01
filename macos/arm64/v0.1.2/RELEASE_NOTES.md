Reaper 0.1.2 — macOS (UI build 306)

**Install:** download the **DMG for your Mac** below. Ignore GitHub's automatic "Source code (zip)" and "Source code (tar.gz)" links — those archives are empty placeholders and are not distributable builds.

| Mac | Download |
|-----|----------|
| Apple Silicon (M1/M2/M3/M4) | `reaper-0.1.2-macos-arm64.dmg` |
| Intel (2015–2020 MacBook Pro, iMac, etc.) | `reaper-0.1.2-macos-x86_64.dmg` |

Requires **macOS 11 (Big Sur)** or later. Drag Reaper.app to Applications, then launch.

**First launch:** ad-hoc signed builds may require right-click → Open once, or allow in System Settings → Privacy & Security.

### What's new (build 306)
- **Bundled Node.js only in app** — Cursor agent never falls back to the laptop's Homebrew or PATH Node; build uses vendored Node too
- Bundled Node.js for Cursor agent (build 305)
- JaCoCo line coverage aligned with HTML report (build 304)

**Tip:** Configure your Cursor API key in Settings → Cursor agent on each Mac.

SHA256 (arm64): `270728150e2cd82295a446f126af02b0722286db6b181eb7066a0e1394b826f7`

SHA256 (x86_64): `cf93a393f7fa2186c4583a82931047b87f2890afa762c9aeb25a500ace144b75`
