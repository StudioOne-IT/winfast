<div align="center">

<img src="assets/icons/winfast.png" width="80" alt="WinFast Pro X Logo"/>

# WinFast Pro X

**Next-Gen Windows Performance & Gaming Suite**

*Free. No accounts. No telemetry. No tricks.*

[![Release](https://img.shields.io/github/v/release/fra77-byte/WinFastProX?color=0078D4&label=Latest%20Release&style=flat-square)](https://github.com/fra77-byte/WinFastProX/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D4?style=flat-square&logo=windows)](https://github.com/fra77-byte/WinFastProX/releases)
[![License](https://img.shields.io/badge/License-Freeware-107C10?style=flat-square)](LICENSE.txt)
[![Made in Italy](https://img.shields.io/badge/Made%20in-Italy%20🇮🇹-009246?style=flat-square)](https://www.studio1informatica.it)

[⬇ Download](#download) • [Features](#features) • [Screenshots](#screenshots) • [FAQ](#faq) • [Donate ☕](#support-the-project)

</div>

---

## What is WinFast Pro X?

WinFast Pro X is a **free, all-in-one Windows optimization suite** built for gamers, power users and anyone who wants to squeeze real performance out of their PC — without bloatware, subscriptions or registry snake oil.

Every tweak is documented with its **real measured impact**, applies with a single click, creates an automatic **System Restore Point** before changing anything, and can be fully **rolled back** at any time from the History panel.

Built and maintained by a single independent Italian developer. No corporate backing, no ads, no data collection — just software made with passion.

---

## Features

### 🎮 Gaming
- **Xbox Platform Hub** — detects hardware compatibility and activates Auto HDR, DirectStorage, HAGS, VRR, Game Mode and Dynamic Latency Input with one click
- **Game Boost** — one-click profile applies the optimal set of tweaks for your GPU (NVIDIA/AMD) and CPU
- **Latency Sniper** — live process monitor showing which apps steal CPU time during gaming
- Dedicated tweaks: GPU priority, HAGS, MPO, Game DVR, Xbox services, DirectX optimization

### ⚙️ General Performance
- Power plan management (High Performance, Ultimate Performance unlock)
- Visual effects optimization, menu delays, app shutdown timers
- Memory management (paging executive, prefetch, SysMain)
- Severity-tagged tweak library: SAFE / MODERATE / AGGRESSIVE

### 📡 Network & Latency
- TCP stack optimization (BBR congestion control, receive window tuning)
- DNS switching (Cloudflare 1.1.1.1, Google 8.8.8.8)
- NIC power saving, interrupt coalescing, QoS reserved bandwidth removal
- Live ping monitor to multiple gaming servers

### 🧠 Smart Advisor
- On-device hardware analysis — zero external connections
- Personalized tweak recommendations based on your actual CPU, GPU and RAM
- Usage profile selector: Gaming / Balanced / Professional

### 📊 Benchmark
- 15-second system benchmark: CPU throughput, RAM bandwidth, disk I/O, OS response
- Baseline save & delta comparison — measure real improvement before and after

### ⚗️ Experimental Lab
- **14 advanced tweaks** based on undocumented Windows internals, PDB symbol analysis, NT source leaks and original research
- Includes 4 **INEDITO** (unpublished) tweaks not found in any other public tool:
  - C-State Inhibition via ACPI Registry Override
  - Kernel Thread Quantum Long Variable + Foreground Boost 3x
  - KTHREAD Ideal Processor + I/O Priority Critical via IFEO
  - GPU TDR Adaptive Timeout + DPC Watchdog Tuning
- All with detailed rollback instructions and Safe Mode recovery steps

### 📜 History & Rollback
- Every applied tweak is logged with timestamp, previous state and result
- Per-tweak rollback — undo any single change without affecting others
- JSON export of the full tweak history

### 📦 Setup PC
- One-click installer for the most useful free Windows software (winget-powered)
- Includes: Studio One AV, Chrome, Firefox, Opera, PDF24, LibreOffice, VLC, 7-Zip, WinRAR and more

---

## Download

<div align="center">

### ➡ [Download WinFast Pro X Setup — Latest Release](https://github.com/fra77-byte/WinFastProX/releases/latest)

`WinFastProX_Setup_2.2.0.exe` · Windows 10/11 · 64-bit · ~25 MB

</div>

**Requirements:**
- Windows 10 version 2004 (build 19041) or later
- Windows 11 recommended for Xbox Platform features (Auto HDR, VRR)
- 64-bit processor (x64)
- Internet connection optional (required only for Smart Advisor AI analysis and Xbox app download)

**Installation:**
1. Download the installer
2. Run it — Windows will ask for administrator permission (required to apply system tweaks)
3. Click Install. That's it.

> ⚠️ **Antivirus note:** Some antivirus software may flag the installer as suspicious because it modifies registry keys and system settings. This is a false positive. WinFast Pro X is clean software — you can verify the installer hash on the Releases page. If in doubt, run it in a sandbox first.

---

## Screenshots

*Screenshots will be added with the first public release.*

---

## Privacy

WinFast Pro X **does not collect any data**.

- ✅ No telemetry
- ✅ No account required
- ✅ No internet connection required for core features
- ✅ All analysis runs locally on your device
- ✅ No background processes when the app is closed

The only optional network activity:
- Smart Advisor AI analysis (calls the developer's gateway — no personal data, only your hardware specs summary)
- Latency monitor (ICMP ping to public hosts you choose)
- Donation flow (sends only the email you voluntarily provide)

---

## Support the Project

WinFast Pro X is **completely free** and always will be. Development is funded entirely by voluntary donations.

<div align="center">

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%E2%98%95%20Donate-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=000000)](https://buymeacoffee.com/fbaldi)

</div>

**As a thank-you for any donation**, you'll receive a **free full license for Studio One AV** — the developer's professional Windows security suite featuring:
- 🛡 Real-time antivirus (ClamAV + YARA-X engines)
- 🌐 Multi-country VPN
- 🔒 Anonymous VPN + TOR browsing
- 🧱 Intelligent firewall

Valid for **12 months on 2 devices** — a value greater than the minimum donation. The license will be sent to your email within 24 hours of donation verification.

---

## FAQ

**Is it really free?**
Yes. No trial, no premium tier, no nag screens. Completely free.

**Does it work on Windows 10?**
Yes, from version 2004 (build 19041). Windows 11 unlocks additional features (Auto HDR, VRR, DirectStorage GPU mode).

**Will it break my PC?**
It's designed not to. Before applying any tweak, WinFast Pro X automatically creates a Windows System Restore Point and saves the previous state of every operation. You can undo any change from the History panel. The most aggressive tweaks have explicit warnings and rollback instructions including Safe Mode recovery.

**Why does it need administrator rights?**
Because it modifies system-level settings: registry keys in HKLM, power plans, network stack parameters. Without admin rights, none of the optimizations can be applied. The UAC prompt appears once at startup.

**My antivirus flags it — is it safe?**
Yes. The flag is a false positive caused by the app's ability to write registry keys and run PowerShell commands (which is exactly what it needs to do to apply optimizations). The software contains no malware, no keyloggers, no trackers. Source code is available for inspection on request.

**How do I undo everything?**
Open the History panel, select the tweaks you want to undo, and click Rollback. Or use Windows' built-in System Restore to the point created before applying tweaks.

---

## About the Developer

WinFast Pro X is developed and maintained by **Francesco Baldi**, owner of **Studio One Informatica Soc. Coop. a.r.l.**, an IT services company based in Borgo San Lorenzo (Mugello, Florence), Italy.

Other software by the same developer:
- **Studio One AV** — Professional Windows antivirus with VPN and TOR (trial available in Setup PC section)
- **ProGest** — Web-based business management platform (Italian market)

🌐 [studio1informatica.it](https://www.studio1informatica.it) · 📧 [francesco@studio1informatica.it](mailto:francesco@studio1informatica.it)

---

<div align="center">

*Made with ❤️ in Italy · Copyright © 2026 Francesco Baldi — Studio One Informatica*

</div>
