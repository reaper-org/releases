# Reaper 0.1.0 (macOS arm64)

macOS Apple Silicon build.

## Install

Download `Reaper-0.1.0-macos-arm64.dmg`, open it, drag **Reaper.app** to **Applications**, then launch.

Verify the download:

```bash
shasum -a 256 -c SHA256SUMS
```

## Highlights

- Cursor agent **Stop** and **Revert** (undo last turn + file changes)
- Agent **Working… / queued** status above the chat input
- **Open a new window when switching repos** (Settings → Appearance)
- macOS multi-window support for separate repo windows
- Go to Class (⌘O), Ruby/Java navigation, Gradle indexer, diagnostics, terminal, and agent panel

## Tip

Opening the `.dmg` repeatedly mounts a new Finder volume each time — eject old `Reaper` drives or run `scripts/eject-reaper-dmgs.sh` in the [reaper](https://github.com/reaper-org/reaper) repo.
