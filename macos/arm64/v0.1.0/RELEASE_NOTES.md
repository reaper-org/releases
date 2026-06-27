# Reaper 0.1.0 (macOS arm64)

macOS Apple Silicon build.

## Install

Download `Reaper-0.1.0-macos-arm64.dmg`, open it, drag **Reaper.app** to **Applications**, then launch.

Verify the download:

```bash
shasum -a 256 -c SHA256SUMS
```

## Highlights

- **Live terminal output** — shell, Gradle, and Java runs stream as they execute
- **Terminal command markers** — each run is visually separated with a labeled header/footer
- **JUnit test chevrons** — run individual tests, parameterized tests, or the whole test class
- **Gradle test filters** — `--tests` paths with `/` and UI path suffixes parse correctly
- **Java 8 / Gradle JVM fix** — Run Java uses your configured JDK; Gradle keeps a modern JVM
- **Diagnostic underlines** — squiggly errors sit below code, not over it
- Cursor agent **Stop** and **Revert** (undo last turn + file changes)
- Agent **Working… / queued** status above the chat input
- **Open a new window when switching repos** (Settings → Appearance)
- macOS multi-window support for separate repo windows
- Go to Class (⌘O), Ruby/Java navigation, Gradle indexer, diagnostics, terminal, and agent panel

## Tip

Opening the `.dmg` repeatedly mounts a new Finder volume each time — eject old `Reaper` drives. Install the reaper app first and then click the app from Applications.
