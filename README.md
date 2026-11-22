<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="LooperSalty — game engines, emulation, AI tooling" src="assets/banner-dark.svg" width="100%">
</picture>

Developer based in France. I like rebuilding hard things from scratch to understand how they work:
a Minecraft engine in C++, an Xbox Series X emulator, a GPT trained from zero, a programming language made of emoji.

**Right now** — making [AnyXboxX](https://github.com/LooperSalty/AnyXboxX) run real Xbox GDK games on Windows.

---

## Featured · [AnyXboxX](https://github.com/LooperSalty/AnyXboxX)

Prototype Xbox Series X emulator. It loads GDK executables (PE32+ x86-64), runs them through Unicorn and replaces the console's system functions with a C++ runtime (high-level emulation, the same approach as Wine).

| CPU instructions | GPU (RDNA 2 → DXIL) | System functions | GDK runtime |
| :---: | :---: | :---: | :---: |
| **100 %** | **35 %** | **66 %** | **166 / 396** |

<sub>Python · C++ · D3D12 · Unicorn — numbers from the project README.</sub>

---

## Games and real-time 3D

| Project | What it is | Stack |
| --- | --- | --- |
| [Minecraft](https://github.com/LooperSalty/Minecraft) | Minecraft 1.8.9 clone written from scratch: chunk streaming, terrain generation, physics, block rendering | C++17, OpenGL 3.3 |
| [liberty-break](https://github.com/LooperSalty/liberty-break) | GTA-like game in the browser: procedural city, arcade physics, police AI, bank heist, zero external assets | JavaScript, Three.js |
| [nexagen](https://github.com/LooperSalty/nexagen) | Procedural world engine playable in the browser, with AI-assisted generation | TypeScript, Three.js |
| [Belotro](https://github.com/LooperSalty/Belotro) | French coinche turned into a roguelike, Balatro-style. One HTML file, online multiplayer | HTML, Supabase |

## AI and developer tools

| Project | What it is | Stack |
| --- | --- | --- |
| [bob-nanogpt-fr](https://github.com/LooperSalty/bob-nanogpt-fr) | Small French GPT built from zero: BPE tokenizer, causal self-attention, chat fine-tuning, web UI | PyTorch |
| [mojito-lang](https://github.com/LooperSalty/mojito-lang) | 🍹 A programming language written only in emoji, with a compiler to JavaScript and a VS Code extension | TypeScript |
| [jarvis](https://github.com/LooperSalty/jarvis) | Local voice assistant on Ollama: Three.js orb, Obsidian memory, desktop actions, Windows tray | Python |
| [mcp-desktop-windows](https://github.com/LooperSalty/mcp-desktop-windows) | MCP server that drives any Windows app (Win32, WPF, UWP, .NET) through UI Automation | Python |
| [jobbot](https://github.com/LooperSalty/jobbot) | Job-search autopilot: collects offers, scores them, writes a tailored CV and cover letter, follows up | Python |

## Tools I use every day

| Project | What it is | Stack |
| --- | --- | --- |
| [claude-code-config](https://github.com/LooperSalty/claude-code-config) | My Claude Code setup: agents, hooks, rules, slash commands | JavaScript |
| [montage-video-claude](https://github.com/LooperSalty/montage-video-claude) | Video editing driven by Claude Code: skills, MCP servers and a TikTok production kit | Python |
| [cs2-tracker](https://github.com/LooperSalty/cs2-tracker) | Counter-Strike 2 stats: live match tracking, in-game overlay, explainable heuristic anti-cheat | Python |
| [WallpaperEngine](https://github.com/LooperSalty/WallpaperEngine) | GTK4 / libadwaita app to browse and apply Wallpaper Engine wallpapers on Linux | Python |

---

## Stack

**Languages** — C++ · C · TypeScript · JavaScript · Python · Rust · Lua/Luau · PHP · Dart<br>
**Graphics & games** — OpenGL · Three.js · D3D12 · Blender · Roblox Studio · Unreal Engine<br>
**Web** — React · Next.js · Node.js · Symfony · Laravel · Tailwind · PostgreSQL · Supabase<br>
**AI** — PyTorch · Ollama · MCP servers · multi-agent orchestration with Claude Code<br>
**Other** — Docker · Git · Linux · Tauri

## Contact

[LinkedIn](https://github.com/LooperSalty) · 106304476+LooperSalty@users.noreply.github.com · I speak French and English.
