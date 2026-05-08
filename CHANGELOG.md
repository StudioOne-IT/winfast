# Changelog — WinFast Pro X

All notable changes are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [2.2.0] — 2026-04

### Added
- **Process Boost** tweak — replaces Ultimate Performance power plan with registry-based
  scheduler optimization (Win32PrioritySeparation, PowerThrottling, core parking)
  that works on all Windows 10/11 editions including Home
- **Loader splash screen** — standalone animated loader process launched before main app,
  shows animated progress bar with 60s linear fill and signal-based completion
- **IA badge** in sidebar — real-time indicator of AI advisor connectivity (blue = online, grey = offline)
- **System tray icon** — minimize to tray instead of closing, with Mostra/Esci context menu

### Fixed
- Installer no longer shows error code 5 (access denied) — removed Defender exclusion
  registry write that required TrustedInstaller privileges
- "Clean Temporary Files" tweak now uses cmd.exe instead of powershell.exe —
  more robust on systems with restricted PowerShell execution policies
- LHM DLL path detection now uses sys.argv[0].parent for robust resolution
  with PyInstaller --onedir deployment

### Changed
- Build system: UPX removed from --onedir builds (counterproductive for DLL loading)
- pythonnet/clr dependency removed from build verification (handled natively by PyInstaller)
- Loader architecture: WinFastProX.exe launches WinFastLoader.exe as detached process,
  communicates via file signal (winfast_ready.signal)

---

## [2.1.0] — 2026-02

### Added
- Xbox Platform Hub — Auto HDR, DirectStorage, HAGS, VRR, Dynamic Latency Input
- Smart Advisor AI — hardware-aware personalized recommendations
- Benchmark engine — 15-second CPU/RAM/disk/OS test with baseline comparison
- One-Click Game Boost profiles for NVIDIA, AMD, Intel
- Experimental Lab — 14 advanced tweaks including 4 exclusive unpublished optimizations
- History & Rollback — per-tweak undo with JSON export
- Live ping monitor — real-time latency to gaming servers

### Changed
- Moved from PyInstaller --onefile to --onedir — eliminates Defender false positives
  caused by self-extraction to TEMP folder

---

## [2.0.0] — 2025-12

### Added
- Complete rewrite in Python 3.11+ / PyQt6
- Dark/light theme toggle
- Multi-language support (IT, EN, DE, FR, ES)
- SVG icon system throughout UI
- License system with HMAC-SHA256 keys
- Real-time thermal monitoring (LibreHardwareMonitor integration)
- Network ping widget

---

## [1.x] — 2025

Initial development versions. Not publicly released.
