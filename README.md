<div align="center">

<img src="assets/icons/logo_winfastprox.png" width="50%" alt="WinFast Pro X Logo"/>

# WinFast Pro X

### 🚀 Next-Gen Windows Performance & Gaming Suite

**Free. Open. No accounts. No telemetry. No tricks.**

[![Release](https://img.shields.io/github/v/release/fra77-byte/WinFastProX?color=0078D4&label=Latest%20Release&style=flat-square)](https://github.com/fra77-byte/WinFastProX/releases)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/fra77-byte/WinFastProX/releases)
[![License](https://img.shields.io/badge/License-Freeware-107C10?style=flat-square)](LICENSE.txt)
[![Made in Italy](https://img.shields.io/badge/Made%20in-Italy%20🇮🇹-009246?style=flat-square)](https://www.studio1informatica.it)
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20me%20a%20coffee%20☕-FFDD00?style=flat-square)](https://buymeacoffee.com/fbaldi)

[✨ Features](#-features) • [📸 Screenshots](#-screenshots) • [🧬 Tweak Library](#-complete-tweak-library) • [❓ FAQ](#-faq) • [☕ Donate](#-support-the-project)

---

> **"The optimization tool Windows should have shipped with."**
> Built by a developer obsessed with low latency, for gamers, streamers and creators who refuse to leave performance on the table.

</div>

---

## 🎯 What is WinFast Pro X?

WinFast Pro X is a **free, all-in-one Windows system optimizer** engineered for **gamers, streamers, content creators and power users** who want every millisecond of performance their hardware can deliver — without bloatware, subscriptions, or dangerous registry guesswork.

Unlike generic "optimizer" tools that push fake cleaners and sponsor junk software, WinFast Pro X is built on **real Windows internals knowledge**: NT kernel scheduling, undocumented ACPI overrides, PDB symbol analysis and original research. Every single tweak shows its **measured real-world impact** before you apply it.

**The key difference:**
- ✅ Every tweak is **documented** with real impact estimates
- ✅ Automatic **System Restore Point** before every change
- ✅ **Full rollback** of any individual tweak, any time
- ✅ **AI-powered analysis** of your specific hardware configuration
- ✅ **Zero telemetry** — all analysis runs locally

---

## ✨ Features

### 🎮 Gaming Optimization

| Feature | What it does |
|---|---|
| **One-Click Game Boost** | Applies the optimal tweak set for your GPU (NVIDIA/AMD/Intel) and CPU in one click — auto-detected hardware profile |
| **Xbox Platform Hub** | Detects compatibility and activates Auto HDR, DirectStorage, HAGS, VRR, Game Mode and Dynamic Latency Input |
| **Latency Sniper** | Live process monitor showing which background apps steal CPU time while you game |
| **GPU Priority Boost** | Sets your GPU to high-performance scheduling priority via HKLM — measurable reduction in frame time variance |
| **HAGS** | Hardware-Accelerated GPU Scheduling — reduces CPU-GPU sync overhead on supported hardware |
| **MPO Disable** | Eliminates Multi-Plane Overlay artifacts that cause micro-stuttering on multi-monitor setups |
| **Game DVR Off** | Disables Xbox Game Bar background recording that silently consumes CPU and disk |
| **DX Optimization** | Forces optimal DirectX feature levels and disables DXGI debug layers |

### ⚙️ System Performance

| Feature | What it does |
|---|---|
| **Process Boost** | Disables Windows power throttling, sets maximum scheduler foreground priority (Win32PrioritySeparation=0x26), reduces core parking aggressiveness to 10% |
| **High Performance Plan** | Activates the High Performance power plan — prevents CPU frequency scaling during demanding tasks |
| **SysMain Off** | Disables the SuperFetch prefetch service that causes disk thrashing on SSD systems |
| **Windows Search Off** | Disables the indexing service — recovers I/O bandwidth on workstations that don't use Cortana search |
| **Memory Optimization** | Tunes paging executive, large system cache, and I/O page lock limit for minimum latency |
| **Boot Speed** | Disables boot delay, optimizes startup sequence, removes unnecessary boot entries |
| **App Shutdown Timer** | Reduces WaitToKillAppTimeout from 20s to 2s — programs close instantly |
| **Visual FX** | One-click "optimize for performance" visual effect preset — removes transparency, shadows, animations |

### 📡 Network & Latency

| Feature | What it does |
|---|---|
| **Nagle Disable** | Disables Nagle's algorithm on all active network interfaces — reduces packet latency by 5–30ms in competitive gaming |
| **TCP Optimization** | Tunes TCP receive window, enables BBR-style congestion control, disables auto-tuning throttle |
| **DNS Cloudflare** | Switches all interfaces to Cloudflare 1.1.1.1 / 1.0.0.1 — fastest public DNS, privacy-first |
| **NIC Power Save Off** | Prevents Windows from powering down network cards — eliminates micro-disconnections and Wi-Fi jitter |
| **QoS Reserve Remove** | Removes the 20% bandwidth reservation imposed by GQOS — gives applications full network throughput |
| **Live Ping Monitor** | Real-time latency graph to major gaming servers (EU, US, Asia) and custom hosts |

### 🧠 AI Smart Advisor

The integrated Smart Advisor performs **hardware-aware analysis** of your specific system configuration:
- Reads CPU model, core count, GPU vendor, RAM amount and storage type
- Generates personalized tweak recommendations ranked by estimated impact
- Identifies hardware-specific optimizations (AMD Ryzen vs Intel, NVIDIA vs AMD GPU)
- Profile selector: **Gaming** / **Balanced** / **Professional / Streaming**
- Powered by AI — runs fully offline for hardware analysis, optional cloud for advanced recommendations

### 📊 Benchmark Engine

- **15-second integrated benchmark**: CPU throughput, RAM bandwidth, disk sequential/random I/O, OS scheduler response
- Save a **baseline** before applying tweaks, measure again after
- Delta comparison shows exact improvement percentage
- Exportable results for sharing

### ⚗️ Experimental Lab — Exclusive Research Tweaks

> ⚠️ Advanced section. Documented, reversible, but intended for power users.

WinFast Pro X includes **14 experimental tweaks** based on original research into undocumented Windows internals:

**4 EXCLUSIVE tweaks not published anywhere else:**
- 🔬 **C-State Inhibition** via ACPI Registry Override — prevents CPU idle states during gaming sessions
- 🔬 **Kernel Thread Quantum Long Variable + Foreground Boost 3×** — extends time slices for foreground processes
- 🔬 **KTHREAD Ideal Processor + I/O Priority Critical via IFEO** — pins game threads to optimal cores
- 🔬 **GPU TDR Adaptive Timeout + DPC Watchdog Tuning** — eliminates GPU timeout resets under heavy load

**Additional experimental tweaks:**
- Timer Resolution 0.5ms — raises NT timer interrupt frequency for sub-millisecond scheduling precision
- MMCSS Audio Latency — optimizes the multimedia class scheduler for lowest audio latency
- IRQ Priority Boost — elevates interrupt priority for GPU and NIC
- Kernel Split-Lock Detection Disable — removes serialization penalty on unaligned memory access
- And more...

### 📜 History & Full Rollback

Every applied tweak is permanently logged:
- Timestamp, previous system state, result
- **Per-tweak rollback** — undo any single change without touching others
- One-click "restore all" to pre-optimization state
- JSON export of complete history

### 📦 Setup PC — Software Installer

One-click installation of the best free Windows tools:
- **Browsers**: Chrome, Firefox, Opera
- **Security**: Studio One AV (antivirus + VPN + TOR)
- **Productivity**: LibreOffice, PDF24, Notepad++, 7-Zip
- **Media**: VLC, IrfanView, GIMP, Paint.NET
- **Gaming**: Steam
- **Utilities**: WizTree, AutoHotkey, FlowLauncher, Bitwarden
- Powered by **winget** — Microsoft's official package manager

---

## 📸 Screenshots

<div align="center">

| Dashboard & System Info | Gaming Mode |
|:---:|:---:|
| ![Sistema](screenshot/sistema.png) | ![Gaming](screenshot/game-mode.png) |

| Xbox Platform Hub | Network Optimizer |
|:---:|:---:|
| ![Xbox](screenshot/xbox_mode.png) | ![Network](screenshot/network.png) |

| Software Installer |
|:---:|
| ![Software](screenshot/software.png) |

</div>

---

## 🧬 Complete Tweak Library

<details>
<summary><strong>🎮 Gaming (11 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `gaming.hags` | Hardware-Accelerated GPU Scheduling | SAFE | ↓ frame time variance |
| `gaming.mpo.disable` | Disable Multi-Plane Overlay | SAFE | Eliminates micro-stutter on multi-monitor |
| `gaming.gamedvr.off` | Disable Game DVR / Xbox Game Bar | SAFE | ↓ background CPU/disk usage |
| `gaming.gpu.priority` | GPU High Performance Priority | SAFE | ↓ render latency |
| `gaming.dx.optimize` | DirectX Optimization | SAFE | Better DX feature level selection |
| `gaming.mode.enable` | Enable Windows Game Mode | SAFE | Prioritizes game threads |
| `gaming.oneclick.nvidia` | One-Click Game Boost — NVIDIA | MODERATE | Comprehensive NVIDIA profile |
| `gaming.oneclick.amd` | One-Click Game Boost — AMD | MODERATE | Comprehensive AMD profile |
| `gaming.oneclick.intel` | One-Click Game Boost — Intel | MODERATE | Comprehensive Intel profile |
| `gaming.xbox.disable` | Disable Xbox Background Services | MODERATE | Recovers RAM and CPU |
| `gaming.fullscreen.opt` | Fullscreen Optimizations | AGGRESSIVE | Forces exclusive fullscreen mode |

</details>

<details>
<summary><strong>⚙️ Performance (5 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `perf.power.high` | High Performance Power Plan | SAFE | Prevents CPU frequency scaling |
| `perf.power.ultimate` | Process Boost — Min CPU Latency | MODERATE | Scheduler latency, core parking |
| `perf.visual.fx` | Visual Effects: Performance Mode | SAFE | ↓ GPU load, snappier UI |
| `perf.menu.delay` | Remove Menu Delays | SAFE | Instant context menus |
| `perf.app.shutdown` | Fast App Shutdown Timer | SAFE | Programs close in 2s instead of 20s |

</details>

<details>
<summary><strong>📡 Network (5 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `network.nagle` | Disable Nagle Algorithm | MODERATE | ↓ 5–30ms ping in games |
| `network.tcp.optimize` | TCP Stack Optimization | MODERATE | Higher throughput, lower jitter |
| `network.dns.cloudflare` | DNS → Cloudflare 1.1.1.1 | SAFE | ↓ DNS resolution time |
| `network.nic.no_powersave` | NIC: Disable Power Saving | SAFE | Eliminates Wi-Fi micro-drops |
| `network.qos.remove` | Remove QoS Bandwidth Reserve | MODERATE | Full bandwidth for applications |

</details>

<details>
<summary><strong>🔒 Privacy (3 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `privacy.telemetry` | Disable Windows Telemetry | SAFE | Stops diagnostic data upload |
| `privacy.location` | Disable Location Services | SAFE | Prevents location tracking |
| `privacy.advertising` | Disable Advertising ID | SAFE | Removes ad profile tracking |

</details>

<details>
<summary><strong>💾 Storage (3 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `storage.ntfs.optimize` | NTFS Optimization | MODERATE | Disables last access timestamps |
| `storage.superfetch.off` | Disable SysMain/SuperFetch | MODERATE | ↓ disk thrashing on SSD |
| `storage.indexing.off` | Disable Search Indexing | AGGRESSIVE | Recovers I/O on non-search workstations |

</details>

<details>
<summary><strong>🖼️ Visual (2 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `visual.fx.minimal` | Minimal Visual Effects | SAFE | Removes animations, transparency |
| `visual.dark.mode` | Enable Dark Mode | SAFE | System-wide dark theme |

</details>

<details>
<summary><strong>🧹 Cleanup (2 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `cleanup.temp` | Clean Temporary Files | SAFE | Frees disk space, clears DNS cache |
| `cleanup.prefetch` | Clean Prefetch Cache | SAFE | Resets Windows boot prefetch |

</details>

<details>
<summary><strong>🖥️ GPU (3 tweaks)</strong></summary>

| ID | Title | Severity | Impact |
|---|---|---|---|
| `gpu.nvidia.optimize` | NVIDIA Driver Optimization | MODERATE | Lower render latency |
| `gpu.amd.optimize` | AMD Driver Optimization | MODERATE | Lower render latency |
| `gpu.prerendered.frames` | Limit Pre-Rendered Frames | MODERATE | ↓ input lag 1–3 frames |

</details>

<details>
<summary><strong>⚗️ Experimental (14 tweaks — exclusive research)</strong></summary>

| ID | Title | Severity |
|---|---|---|
| `exp.timer.resolution` | Timer Resolution 0.5ms | MODERATE |
| `exp.cstate.inhibit` | C-State Inhibition via ACPI ⭐ EXCLUSIVE | MODERATE |
| `exp.kernel.quantum` | Kernel Thread Quantum Long Variable ⭐ EXCLUSIVE | MODERATE |
| `exp.kthread.ideal` | KTHREAD Ideal Processor via IFEO ⭐ EXCLUSIVE | MODERATE |
| `exp.gpu.tdr.adaptive` | GPU TDR Adaptive Timeout ⭐ EXCLUSIVE | MODERATE |
| `exp.mmcss.audio` | MMCSS Audio Latency | MODERATE |
| `exp.irq.priority` | IRQ Priority Boost | MODERATE |
| `exp.splitlock` | Kernel Split-Lock Disable | AGGRESSIVE |
| `exp.dpc.watchdog` | DPC Watchdog Tuning | AGGRESSIVE |
| `exp.memory.compression` | Memory Compression Tune | MODERATE |
| `exp.cpu.parking` | CPU Core Parking Advanced | MODERATE |
| `exp.gpu.priority.high` | GPU Thread Priority Critical | MODERATE |
| `exp.scheduler.boost` | Scheduler Dynamic Boost 3x | AGGRESSIVE |
| `exp.io.priority` | I/O Priority Critical via IFEO | MODERATE |

</details>

---

## ⬇️ Download

<div align="center">

### ➡️ [Download WinFast Pro X v2.2.0](https://github.com/fra77-byte/WinFastProX/releases/latest)

`WinFastProX_Setup_2.2.0.exe` · Windows 10/11 · 64-bit · ~25 MB · Free

</div>

**Requirements:**
- Windows 10 v2004 (build 19041) or later — Windows 11 recommended
- 64-bit processor (x64)
- Administrator rights (required to apply system-level optimizations)
- Internet connection optional (only needed for AI cloud analysis)

**How to install:**
1. Download the installer
2. Run it → Windows asks for administrator permission once
3. Done. The app is ready.

> ⚠️ **Antivirus false positive:** Security software may flag the installer because it modifies registry keys and system settings — which is precisely what it needs to do. WinFast Pro X contains no malware. The installer hash is published on the Releases page. Run in a sandbox if uncertain.

---

## 🔒 Privacy

WinFast Pro X **collects zero data**.

| | |
|---|---|
| ✅ No telemetry | ✅ No account required |
| ✅ No background processes | ✅ All analysis runs locally |
| ✅ No ads | ✅ No third-party trackers |

Optional network usage only:
- **Smart Advisor AI**: sends only a hardware summary string (no personal data) to the developer's gateway
- **Ping monitor**: ICMP to public hosts you select
- **Donation**: only the email you voluntarily provide

---

## ☕ Support the Project

WinFast Pro X is **completely free** and will always be free. If it saved you money on a coaching session, a new SSD or an FPS boost subscription — consider buying the developer a coffee.

<div align="center">

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%E2%98%95%20Support%20Development-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=000000)](https://buymeacoffee.com/fbaldi)

</div>

**Every donor receives as a gift:**
- 🛡️ **Studio One AV** — professional antivirus + multi-country VPN + TOR anonymous browsing + smart firewall
- Valid **12 months on 2 devices**
- Sent within 24h of donation verification

---

## ❓ FAQ

<details>
<summary><strong>Is it really free? No catch?</strong></summary>
No catch. No trial period, no premium tier, no nag screens, no bundled software. Completely free. The developer is funded by voluntary donations.
</details>

<details>
<summary><strong>Will it break my PC?</strong></summary>
It is specifically designed not to. Before applying any tweak, WinFast Pro X creates a Windows System Restore Point and records the exact previous state of every registry key, service and setting it touches. You can undo any single change from the History panel at any time — even months later.
</details>

<details>
<summary><strong>Why does it need administrator rights?</strong></summary>
Because it writes to HKLM registry keys, modifies power plans, changes network stack parameters and controls Windows services. These are privileged operations — there is no way to perform them without admin rights. The UAC prompt appears once at startup, not on every click.
</details>

<details>
<summary><strong>My antivirus flags it. Is it safe?</strong></summary>
Yes. The detection is a false positive: the app legitimately modifies registry keys and runs system commands. These are exactly the capabilities it needs to optimize your system. The software contains no malware, no keyloggers, no miners. Source available on request.
</details>

<details>
<summary><strong>Does it work on Windows 10?</strong></summary>
Yes, from Windows 10 v2004 (build 19041) onward. Windows 11 unlocks additional features: Auto HDR, DirectStorage GPU mode, VRR, and Xbox Platform hub features.
</details>

<details>
<summary><strong>How do I undo everything?</strong></summary>
Open the **History** panel → select tweaks to undo → click Rollback. Each tweak can be rolled back individually. Alternatively, use Windows' built-in System Restore to the restore point created automatically before you applied any tweaks.
</details>

<details>
<summary><strong>Is the source code available?</strong></summary>
The binary is available on the Releases page. Source code inspection is available on request for security researchers and developers. Contact: francesco@studio1informatica.it
</details>

---

## 👨‍💻 About the Developer

**WinFast Pro X** is developed and maintained solo by **Francesco Baldi**, founder of **Studio One Informatica Soc. Coop. a.r.l.** — an IT services company in Borgo San Lorenzo (Mugello, Tuscany), Italy.

No VC funding. No team. No marketing budget. Just one developer who builds the tools he wishes existed.

Other projects:
- **[Studio One AV](https://www.studio1informatica.it)** — Windows antivirus with multi-country VPN and TOR browsing
- **ProGest** — Web ERP platform for the Italian market

🌐 [studio1informatica.it](https://www.studio1informatica.it) · 📧 [francesco@studio1informatica.it](mailto:francesco@studio1informatica.it) · 🐙 [GitHub](https://github.com/fra77-byte)

---

<div align="center">

**[🇮🇹 Leggi in Italiano](README.it.md)**

*Made with ❤️ and too much coffee in Mugello, Italy*
*Copyright © 2026 Francesco Baldi — Studio One Informatica*

</div>
