# Zain Kashif

Software Developer working on mobile clients, runtime sandboxing, and systems programming.

I build mobile applications, developer tooling, and systems software. My work focuses on low-latency interfaces, remote execution environments, and direct hardware audio/graphics pipelines.

---

### Projects

#### [QuickKode](https://github.com/D3MONOXXIZZ/QuickKode)
Mobile client for running autonomous coding agents inside isolated cloud sandboxes.
- Spins up ephemeral [E2B](https://e2b.dev) Linux environments over WebSocket.
- Bidirectional Google Drive sync for local and remote workspace persistence.
- Monitor agent execution logs, inspect AST changes, and review git diffs on mobile without needing a desktop terminal.
- *Tech: Flutter, Dart, E2B SDK, Cloud APIs*

#### [KharchaBook](https://github.com/D3MONOXXIZZ/kharchabook)
Lightweight personal expense tracker built for students.
- Offline-first architecture backed by SQLite with zero tracking, telemetry, or network latency.
- Custom vector-rendered editorial UI running within a strict 60 FPS frame budget.
- Dual-theme design system written directly in Flutter without third-party component wrappers.
- *Tech: Flutter, Dart, SQLite*

#### FreeBeat
Android music player and streaming client engineered for lossless playback.
- Integrates directly with Poweramp's 10-band DSP equalizer pipeline to bypass standard Android audio resampling.
- Hardware-accelerated lossless audio decoding with parametric EQ curves.
- *Tech: Flutter, Android Audio APIs, Poweramp DSP*

#### [Space Invaders 8086](https://github.com/D3MONOXXIZZ/CEN323_G_5_SpaceInvaders)
The 1978 arcade game written from scratch in 16-bit real-mode x86 assembly for emu8086.
- Direct video memory mapping (`0xA000` / `INT 10h`) for sprite rendering and double buffering.
- Raw keyboard interrupt polling via `INT 16h` and PIT-based game loop timing.
- No engines or runtime libraries—just bare registers, interrupts, and memory.
- *Tech: x86 Assembly, emu8086*

#### [Megascans Bridge for Blender](https://github.com/D3MONOXXIZZ/Megascans-Bridge-for-Blender-v5.0-)
Fixes broken Megascans material node tree exports in modern Blender releases. Replaces paywalled marketplace add-ons with a free, open-source Python bridge.
- *Tech: Python, Blender Python API (`bpy`)*

---

### Technical Focus

- **Languages:** Dart, Kotlin, Python, x86 Assembly, C
- **Mobile & UI:** Flutter, Android SDK, Jetpack Compose, custom render objects, design systems
- **Systems & Runtimes:** E2B sandboxes, Linux, audio DSP, SQLite, Docker, Git

---

### Contact

- **Email:** [xain.kash@gmail.com](mailto:xain.kash@gmail.com)
- **GitHub:** [@D3MONOXXIZZ](https://github.com/D3MONOXXIZZ)
