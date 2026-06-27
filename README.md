# Reaper releases

Official release artifacts for [Reaper](https://github.com/reaper-org/reaper).

## Layout

```
macos/
  arm64/
    v0.1.0/
      Reaper-0.1.0-macos-arm64.dmg
      SHA256SUMS
      RELEASE_NOTES.md
  x64/
    vX.Y.Z/
      ...
```

Artifact names match the build output from `reaper` (`Reaper-{version}-macos-{arch}.dmg`).

## Install (macOS)

1. Download the DMG for your Mac's architecture (`arm64` for Apple Silicon, `x64` for Intel).
2. Open the DMG and drag **Reaper.app** to **Applications**.
3. Eject the mounted volume and launch Reaper from Applications.

Verify downloads with the checksum file in each version directory:

```bash
shasum -a 256 -c SHA256SUMS
```

## Versions

| Version | macOS arm64 | Notes |
|---------|-------------|-------|
| [0.1.0](macos/arm64/v0.1.0/RELEASE_NOTES.md) | [DMG](macos/arm64/v0.1.0/Reaper-0.1.0-macos-arm64.dmg) | Initial public release |
