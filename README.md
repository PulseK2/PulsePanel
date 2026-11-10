<div align="center">
  <img width="2752" height="1536" alt="pulsegameserverpanel" src="https://github.com/user-attachments/assets/9c2dbdff-b900-4efc-be80-e980843a4d31" />
  <h1>PulseGameServerPanel (PulsePanel)</h1>
  <p>
    A free, open-source, lightweight Windows desktop game server &amp; Discord bot hosting panel built with Tauri 2, Rust, React, and TypeScript.
  </p>
  <p>
    <strong>83+ Built-In Game &amp; Bot Presets • ConPTY Headless Consoles • Built-In File Manager &amp; FTP • Startup Parameter Editor</strong>
  </p>
</div>

---

## Overview

**PulseGameServerPanel** turns any Windows PC into a fast, zero-cost, self-hosted game server and Discord bot control panel — distributed as a **single standalone executable (`PulsePanel.exe`)** with an embedded SQLite database and no paid subscriptions or external runtime clutter.

More programs & projects by **[PulseK2](https://github.com/PulseK2/)**.

---

## Features

- **1-Click Installer & 83 Built-In Presets**:
  - **79 SteamCMD Dedicated Servers** (Valve's Dedicated Servers List & popular survival/FPS titles including *Garry's Mod*, *Counter-Strike 2*, *CS:GO Legacy*, *CS 1.6*, *CS:CZ*, *Team Fortress 2*, *TFC*, *Left 4 Dead 1 & 2*, *Rust*, *Palworld*, *ARK: Survival Ascended / Evolved*, *7 Days to Die*, *Valheim*, *Satisfactory*, *V Rising*, *Enshrouded*, *Project Zomboid*, *Squad*, *Arma Reforger*, *Insurgency 2014 & Sandstorm*, *Sven Co-op*, *Icarus*, *Myth of Empires*, *Killing Floor 1 & 2*, and many more).
  - **Minecraft**: Automatic OpenJDK 21 provisioning + *Minecraft Java Edition* & *Bedrock Dedicated Server* setup.
  - **Discord Bots**: Automatic isolated *Node.js (`discord.js`)* and *Python (`discord.py`)* `.venv` bot scaffolding with `.env` configuration.
  - **Custom Servers**: Attach any Windows `.exe`, `.bat`, Java `.jar`, Node.js, or Python server binary.
- **Integrated Headless Consoles**:
  - Live SteamCMD `console_log.txt` tailing directly inside the panel (zero stray SteamCMD windows) with disk-space (`0x202`) detection.
  - Native Windows **ConPTY** pseudoconsole hosting for Valve Source/GoldSource (`srcds_console.exe`, `hlds.exe`, `svends.exe`) and interactive console commands with copyable output.
- **Built-In File Manager & Embedded FTP Server**:
  - Browse, upload, download, rename, delete, and edit server config files directly in the panel.
  - Built-in RFC 959 **FTP Server** (`port 2121` by default) with per-server isolated credentials and one-click password regeneration.
- **Startup Parameter Editor & Mod Manager**:
  - Visual startup flag toggles, map/port/max-player overrides, custom CLI arguments, plus Steam Workshop & Modrinth mod management.
- **Live Telemetry & Backups**:
  - Real-time per-process CPU, RAM, host network metrics, port/Windows Firewall helpers, activity logs, and one-click `.zip` backups/restores.
  -  **Built in AI assistant**:
    - Built in ai assistant that can help you debug errors and help with many other things (needs api key) can be used with gemini,openai or a local ai.
    -  **Automated Tasks**:
    -  Configure automated maintenance windows, scheduled restarts, backup cron tasks and crash watchdogs.
- **100% Free & Local**: No accounts, telemetry lock-in, or paid tiers.

---

## Single-EXE Usage (Windows)

1. Download the standalone **`PulsePanel.exe`** (or setup installer) from the **[Releases](../../releases)** page.
2. Double-click `PulsePanel.exe` — no installation folder of extra DLLs required.
3. Choose **Install Game / Bot** in the sidebar to deploy servers (auto-provisions SteamCMD, OpenJDK 21, Node.js, or Python as needed).

---

## Tech Stack

- **Desktop & Backend**: [Tauri 2](https://v2.tauri.app/), Rust (`tokio`, `sysinfo`, `rusqlite` bundled SQLite, Windows ConPTY & Job Objects, `zip`, `reqwest`)
- **Frontend**: React 19, TypeScript, Vite, Tailwind CSS, Lucide Icons, Recharts

---

## Want a Featured added feel free to make a request!.
## Please post all bugs.

## Author

Created by **[PulseK2](https://github.com/PulseK2/)**.
