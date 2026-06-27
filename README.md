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

## Publishing a new macOS build

From the `reaper` repo:

```bash
./scripts/build-macos-dmg.sh
```

Copy the resulting DMG into this repo:

```bash
VERSION=0.1.0
ARCH=arm64   # or x64
mkdir -p "macos/${ARCH}/v${VERSION}"
cp "../reaper/dist/Reaper-${VERSION}-macos-${ARCH}.dmg" "macos/${ARCH}/v${VERSION}/"
cd "macos/${ARCH}/v${VERSION}"
shasum -a 256 Reaper-${VERSION}-macos-${ARCH}.dmg > SHA256SUMS
```

Add `RELEASE_NOTES.md` for the version, then tag and create a GitHub release on this repo.

## Versions

| Version | macOS arm64 | Notes |
|---------|-------------|-------|
| [0.1.0](macos/arm64/v0.1.0/RELEASE_NOTES.md) | [DMG](macos/arm64/v0.1.0/Reaper-0.1.0-macos-arm64.dmg) | Initial public release |
