Reaper 0.1.2 — macOS (UI build 297)

**Install:** download the **DMG for your Mac** below. Ignore GitHub's automatic "Source code (zip)" and "Source code (tar.gz)" links — those archives are empty placeholders and are not distributable builds.

| Mac | Download |
|-----|----------|
| Apple Silicon (M1/M2/M3/M4) | `reaper-0.1.2-macos-arm64.dmg` |
| Intel (2015–2020 MacBook Pro, iMac, etc.) | `reaper-0.1.2-macos-x86_64.dmg` |

Requires **macOS 11 (Big Sur)** or later. Drag Reaper.app to Applications, then launch.

**First launch:** ad-hoc signed builds may require right-click → Open once, or allow in System Settings → Privacy & Security.

### What's new (build 297)
- **Java diagnostics false positives** — suppress squiggles for SLF4J, Mockito, JUnit, and Lombok `@Slf4j` when build files declare them but Reaper's offline classpath is still catching up
- **Project class references** — hide `cannot find symbol` for classes that exist elsewhere in the workspace sources
- **Per-file test classpath** — test sources merge test-scoped dependency trees for javac diagnostics
- **Gradle/Maven source roots** — recognize Kotlin, integrationTest, testFixtures, and generated layouts; color main/test/generated dirs in the file tree

### Prior 0.1.2 highlights (build 296)
- **Annotation indexing** — `@RestController`, custom `@interface` types, and library annotations detected via classfile flags and shown in `@` completions
- **Generated AP sources** — more Gradle/Maven generated output layouts indexed (MapStruct headers, annotation processor dirs)
- **Gradle wrapper in nested modules** — walks up to repo root `./gradlew` and runs `-p <module>` instead of falling back to Settings/PATH Gradle

**Tip:** opening the .dmg repeatedly mounts a new Finder volume each time — eject old Reaper drives when done.

SHA256 (arm64): `be28763f7c6d2fc72ccfe2bb3a27bf6bf9e2ec489195fe9b1262b34ccef3403f`

SHA256 (x86_64): `1435ff74ed1723a3c571c003577384b6e875c26a5e0d17187d27bd8c1c09e449`
