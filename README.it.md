<div align="center">

<img src="assets/icons/logo_winfastprox.png" width="220" alt="WinFast Pro X Logo"/>

# WinFast Pro X

### 🚀 Suite di Ottimizzazione Windows di Nuova Generazione

**Gratuito. Nessun account. Nessuna telemetria. Nessun trucco.**

[![Release](https://img.shields.io/github/v/release/fra77-byte/WinFastProX?color=0078D4&label=Ultima%20Versione&style=flat-square)](https://github.com/fra77-byte/WinFastProX/releases)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?style=flat-square&logo=windows&logoColor=white)](https://github.com/fra77-byte/WinFastProX/releases)
[![Licenza](https://img.shields.io/badge/Licenza-Freeware-107C10?style=flat-square)](LICENSE.txt)
[![Made in Italy](https://img.shields.io/badge/Made%20in-Italy%20🇮🇹-009246?style=flat-square)](https://www.studio1informatica.it)

[⬇️ Download](#-download) • [✨ Funzionalità](#-funzionalità) • [📸 Screenshot](#-screenshot) • [🧬 Libreria Tweak](#-libreria-tweak-completa) • [❓ FAQ](#-faq) • [☕ Donazioni](#-supporta-il-progetto)

---

> **"Lo strumento di ottimizzazione che Windows avrebbe dovuto includere."**
> Costruito da uno sviluppatore ossessionato dalla latenza, per gamer, streamer e creator che si rifiutano di lasciare prestazioni sul tavolo.

</div>

---

## 🎯 Cos'è WinFast Pro X?

WinFast Pro X è una **suite di ottimizzazione Windows gratuita e all-in-one** progettata per **gamer, streamer, creator e power user** che vogliono ogni millisecondo di prestazione che il loro hardware può offrire — senza bloatware, abbonamenti, o pericolose modifiche di registro alla cieca.

A differenza degli strumenti "ottimizzatori" generici che spingono cleaner fasulli e software sponsorizzato, WinFast Pro X è costruito su **vera conoscenza degli internals di Windows**: scheduling del kernel NT, override ACPI non documentati, analisi di simboli PDB e ricerca originale. Ogni singolo tweak mostra il suo **impatto misurabile nel mondo reale** prima che tu lo applichi.

**La differenza chiave:**
- ✅ Ogni tweak è **documentato** con stime di impatto reali
- ✅ **Punto di Ripristino** automatico prima di ogni modifica
- ✅ **Rollback completo** di qualsiasi tweak individuale, in qualsiasi momento
- ✅ **Analisi AI** della tua specifica configurazione hardware
- ✅ **Zero telemetria** — tutta l'analisi gira localmente

---

## ✨ Funzionalità

### 🎮 Ottimizzazione Gaming

| Funzione | Cosa fa |
|---|---|
| **Game Boost One-Click** | Applica il set ottimale di tweak per la tua GPU (NVIDIA/AMD/Intel) e CPU in un click — profilo hardware rilevato automaticamente |
| **Xbox Platform Hub** | Rileva la compatibilità e attiva Auto HDR, DirectStorage, HAGS, VRR, Game Mode e Dynamic Latency Input |
| **Latency Sniper** | Monitor processi in tempo reale che mostra quali app di background rubano tempo CPU mentre giochi |
| **GPU Priority Boost** | Imposta la GPU su priorità di scheduling alta via HKLM — riduzione misurabile della varianza del frame time |
| **HAGS** | Hardware-Accelerated GPU Scheduling — riduce l'overhead di sincronizzazione CPU-GPU |
| **Disabilita MPO** | Elimina gli artefatti Multi-Plane Overlay che causano micro-stuttering su setup multi-monitor |
| **Game DVR Off** | Disabilita la registrazione in background di Xbox Game Bar che consuma silenziosamente CPU e disco |

### ⚙️ Prestazioni di Sistema

| Funzione | Cosa fa |
|---|---|
| **Process Boost** | Disabilita il power throttling di Windows, imposta la massima priorità foreground dello scheduler (Win32PrioritySeparation=0x26), riduce l'aggressività del core parking al 10% |
| **Piano Alte Prestazioni** | Attiva il piano energetico Alte Prestazioni — impedisce lo scaling della frequenza CPU durante i carichi |
| **SysMain Off** | Disabilita il servizio SuperFetch che causa thrashing del disco su sistemi SSD |
| **Windows Search Off** | Disabilita il servizio di indicizzazione — recupera larghezza di banda I/O |
| **Ottimizzazione Memoria** | Ottimizza paging executive, large system cache e I/O page lock limit per latenza minima |
| **Timer Shutdown App** | Riduce WaitToKillAppTimeout da 20s a 2s — i programmi si chiudono istantaneamente |
| **Effetti Visivi** | Preset "ottimizza per prestazioni" in un click — rimuove trasparenza, ombre, animazioni |

### 📡 Rete e Latenza

| Funzione | Cosa fa |
|---|---|
| **Disabilita Nagle** | Disabilita l'algoritmo di Nagle su tutte le interfacce di rete attive — riduce la latenza dei pacchetti di 5–30ms nel gaming competitivo |
| **Ottimizzazione TCP** | Ottimizza il receive window TCP, abilita il controllo di congestione BBR-style |
| **DNS Cloudflare** | Passa tutte le interfacce a Cloudflare 1.1.1.1 / 1.0.0.1 — DNS pubblico più veloce, privacy-first |
| **NIC Power Save Off** | Impedisce a Windows di spegnere le schede di rete — elimina le micro-disconnessioni e il jitter Wi-Fi |
| **Rimuovi Riserva QoS** | Rimuove la riserva del 20% di banda imposta da GQOS — le applicazioni hanno piena disponibilità |
| **Monitor Ping Live** | Grafico latenza in tempo reale verso i principali server gaming e host personalizzati |

### 🧠 Smart Advisor con AI

L'Smart Advisor integrato esegue un'**analisi consapevole dell'hardware** della tua specifica configurazione:
- Legge modello CPU, numero di core, produttore GPU, quantità RAM e tipo di storage
- Genera raccomandazioni personalizzate di tweak classificate per impatto stimato
- Identifica ottimizzazioni specifiche per hardware (AMD Ryzen vs Intel, GPU NVIDIA vs AMD)
- Selettore profilo: **Gaming** / **Bilanciato** / **Professionale / Streaming**

### 📊 Motore Benchmark

- **Benchmark integrato da 15 secondi**: throughput CPU, banda RAM, I/O disco, risposta scheduler OS
- Salva un **baseline** prima dei tweak, misura di nuovo dopo
- Confronto delta con percentuale di miglioramento esatta
- Risultati esportabili per la condivisione

### ⚗️ Experimental Lab — Tweak Esclusivi di Ricerca

> ⚠️ Sezione avanzata. Documentata, reversibile, ma pensata per power user.

WinFast Pro X include **14 tweak sperimentali** basati su ricerca originale sugli internals non documentati di Windows:

**4 tweak ESCLUSIVI non pubblicati altrove:**
- 🔬 **C-State Inhibition** via ACPI Registry Override — impedisce gli stati idle della CPU durante le sessioni di gaming
- 🔬 **Kernel Thread Quantum Long Variable + Foreground Boost 3×** — estende i time slice per i processi foreground
- 🔬 **KTHREAD Ideal Processor + I/O Priority Critical via IFEO** — assegna i thread di gioco ai core ottimali
- 🔬 **GPU TDR Adaptive Timeout + DPC Watchdog Tuning** — elimina i reset GPU per timeout sotto carico pesante

### 📜 Cronologia e Rollback Completo

Ogni tweak applicato viene registrato permanentemente:
- Timestamp, stato precedente del sistema, risultato
- **Rollback per-tweak** — annulla qualsiasi singola modifica senza toccare le altre
- "Ripristina tutto" in un click allo stato pre-ottimizzazione
- Esportazione JSON della cronologia completa

### 📦 Setup PC — Installer Software

Installazione in un click dei migliori tool gratuiti per Windows:
- **Browser**: Chrome, Firefox, Opera
- **Sicurezza**: Studio One AV (antivirus + VPN + TOR)
- **Produttività**: LibreOffice, PDF24, Notepad++, 7-Zip
- **Media**: VLC, IrfanView, GIMP, Paint.NET
- **Gaming**: Steam
- **Utilità**: WizTree, AutoHotkey, FlowLauncher, Bitwarden
- Basato su **winget** — il package manager ufficiale Microsoft

---

## 📸 Screenshot

<div align="center">

| Dashboard & Info Sistema | Modalità Gaming |
|:---:|:---:|
| ![Sistema](screenshot/sistema.png) | ![Gaming](screenshot/game-mode.png) |

| Xbox Platform Hub | Ottimizzatore Rete |
|:---:|:---:|
| ![Xbox](screenshot/xbox_mode.png) | ![Network](screenshot/network.png) |

| Installer Software |
|:---:|
| ![Software](screenshot/software.png) |

</div>

---

## 🧬 Libreria Tweak Completa

<details>
<summary><strong>🎮 Gaming — 11 tweak</strong></summary>

| Titolo | Severità | Impatto |
|---|---|---|
| Hardware-Accelerated GPU Scheduling | SICURO | ↓ varianza frame time |
| Disabilita Multi-Plane Overlay | SICURO | Elimina micro-stutter multi-monitor |
| Disabilita Game DVR / Xbox Game Bar | SICURO | ↓ uso CPU/disco in background |
| GPU Priorità Alta Prestazioni | SICURO | ↓ latenza rendering |
| Ottimizzazione DirectX | SICURO | Selezione feature level ottimale |
| Attiva Windows Game Mode | SICURO | Priorità thread di gioco |
| Game Boost NVIDIA One-Click | MODERATO | Profilo NVIDIA completo |
| Game Boost AMD One-Click | MODERATO | Profilo AMD completo |
| Game Boost Intel One-Click | MODERATO | Profilo Intel completo |
| Disabilita Servizi Xbox in Background | MODERATO | Recupera RAM e CPU |
| Ottimizzazioni Schermo Intero | AGGRESSIVO | Forza fullscreen esclusivo |

</details>

<details>
<summary><strong>⚙️ Prestazioni — 5 tweak</strong></summary>

| Titolo | Severità | Impatto |
|---|---|---|
| Piano Energetico Alte Prestazioni | SICURO | Impedisce scaling frequenza CPU |
| Process Boost — Latenza CPU Minima | MODERATO | Latenza scheduler, core parking |
| Effetti Visivi: Modalità Prestazioni | SICURO | ↓ carico GPU, UI più reattiva |
| Rimuovi Ritardi Menu | SICURO | Menu contestuali istantanei |
| Timer Shutdown App Veloce | SICURO | Programmi si chiudono in 2s |

</details>

<details>
<summary><strong>📡 Rete — 5 tweak</strong></summary>

| Titolo | Severità | Impatto |
|---|---|---|
| Disabilita Algoritmo Nagle | MODERATO | ↓ 5–30ms ping nei giochi |
| Ottimizzazione Stack TCP | MODERATO | Throughput maggiore, meno jitter |
| DNS → Cloudflare 1.1.1.1 | SICURO | ↓ tempo risoluzione DNS |
| NIC: Disabilita Risparmio Energetico | SICURO | Elimina micro-disconnessioni Wi-Fi |
| Rimuovi Riserva Banda QoS | MODERATO | Larghezza di banda piena |

</details>

<details>
<summary><strong>🔒 Privacy — 3 tweak</strong></summary>

| Titolo | Severità |
|---|---|
| Disabilita Telemetria Windows | SICURO |
| Disabilita Servizi di Localizzazione | SICURO |
| Disabilita ID Pubblicità | SICURO |

</details>

<details>
<summary><strong>💾 Storage — 3 tweak</strong></summary>

| Titolo | Severità |
|---|---|
| Ottimizzazione NTFS | MODERATO |
| Disabilita SysMain/SuperFetch | MODERATO |
| Disabilita Indicizzazione Ricerca | AGGRESSIVO |

</details>

<details>
<summary><strong>🧹 Pulizia — 2 tweak</strong></summary>

| Titolo | Severità |
|---|---|
| Pulisci File Temporanei | SICURO |
| Pulisci Cache Prefetch | SICURO |

</details>

<details>
<summary><strong>⚗️ Sperimentali — 14 tweak esclusivi</strong></summary>

| Titolo | Severità |
|---|---|
| Timer Resolution 0.5ms | MODERATO |
| C-State Inhibition via ACPI ⭐ ESCLUSIVO | MODERATO |
| Kernel Thread Quantum Long Variable ⭐ ESCLUSIVO | MODERATO |
| KTHREAD Ideal Processor via IFEO ⭐ ESCLUSIVO | MODERATO |
| GPU TDR Adaptive Timeout ⭐ ESCLUSIVO | MODERATO |
| MMCSS Audio Latency | MODERATO |
| IRQ Priority Boost | MODERATO |
| Kernel Split-Lock Disable | AGGRESSIVO |
| DPC Watchdog Tuning | AGGRESSIVO |
| Memory Compression Tune | MODERATO |
| CPU Core Parking Advanced | MODERATO |
| GPU Thread Priority Critical | MODERATO |
| Scheduler Dynamic Boost 3x | AGGRESSIVO |
| I/O Priority Critical via IFEO | MODERATO |

</details>

---

## ⬇️ Download

<div align="center">

### ➡️ [Scarica WinFast Pro X v2.2.0](https://github.com/fra77-byte/WinFastProX/releases/latest)

`WinFastProX_Setup_2.2.0.exe` · Windows 10/11 · 64-bit · ~25 MB · Gratuito

</div>

**Requisiti:**
- Windows 10 v2004 (build 19041) o successivo — Windows 11 consigliato
- Processore 64-bit (x64)
- Diritti di Amministratore (richiesti per applicare le ottimizzazioni)
- Connessione internet opzionale

**Installazione:**
1. Scarica l'installer
2. Eseguilo → Windows chiede i permessi di amministratore una volta sola
3. Fatto.

> ⚠️ **Nota antivirus:** alcuni software di sicurezza possono segnalare l'installer come sospetto perché modifica chiavi di registro e impostazioni di sistema. È un falso positivo. WinFast Pro X non contiene malware. L'hash dell'installer è pubblicato sulla pagina Releases.

---

## 🔒 Privacy

WinFast Pro X **non raccoglie nessun dato**.

| | |
|---|---|
| ✅ Nessuna telemetria | ✅ Nessun account richiesto |
| ✅ Nessun processo in background | ✅ Tutta l'analisi gira localmente |
| ✅ Nessuna pubblicità | ✅ Nessun tracker di terze parti |

---

## ☕ Supporta il Progetto

WinFast Pro X è **completamente gratuito** e lo sarà sempre.

<div align="center">

[![Buy Me a Coffee](https://img.shields.io/badge/Offrimi%20un%20Caffè-%E2%98%95%20Supporta%20lo%20Sviluppo-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=000000)](https://buymeacoffee.com/fbaldi)

</div>

**Come ringraziamento ogni donatore riceve:**
- 🛡️ **Studio One AV** — antivirus professionale + VPN multi-paese + navigazione TOR anonima + firewall intelligente
- Valido **12 mesi su 2 dispositivi**
- Inviato entro 24h dalla verifica della donazione

---

## ❓ FAQ

<details>
<summary><strong>È davvero gratuito? Nessun trucco?</strong></summary>
Nessun trucco. Nessun periodo di prova, nessun tier premium, nessun nag screen. Completamente gratuito. Lo sviluppatore è finanziato da donazioni volontarie.
</details>

<details>
<summary><strong>Può rompere il mio PC?</strong></summary>
È progettato appositamente per non farlo. Prima di applicare qualsiasi tweak, WinFast Pro X crea un Punto di Ripristino di Windows e registra lo stato precedente esatto di ogni chiave di registro, servizio e impostazione che tocca. Puoi annullare qualsiasi singola modifica dal pannello Cronologia in qualsiasi momento.
</details>

<details>
<summary><strong>Perché richiede i diritti di amministratore?</strong></summary>
Perché scrive in chiavi di registro HKLM, modifica i piani energetici, cambia i parametri dello stack di rete e controlla i servizi Windows. Queste sono operazioni privilegiate — non c'è modo di eseguirle senza diritti admin. Il prompt UAC appare una volta all'avvio, non ad ogni click.
</details>

<details>
<summary><strong>Il mio antivirus lo segnala. È sicuro?</strong></summary>
Sì. Il rilevamento è un falso positivo: l'app modifica legittimamente chiavi di registro ed esegue comandi di sistema. Non contiene malware, keylogger o miner. Il codice sorgente è disponibile su richiesta per ricercatori di sicurezza.
</details>

<details>
<summary><strong>Come annullo tutto?</strong></summary>
Apri il pannello **Cronologia** → seleziona i tweak da annullare → clicca Rollback. Ogni tweak può essere annullato individualmente. In alternativa, usa il Ripristino del Sistema di Windows al punto creato automaticamente prima di applicare i tweak.
</details>

---

## 👨‍💻 Lo Sviluppatore

**WinFast Pro X** è sviluppato e mantenuto in solitaria da **Francesco Baldi**, fondatore di **Studio One Informatica Soc. Coop. a.r.l.** — un'azienda di servizi IT a Borgo San Lorenzo (Mugello, Toscana).

Nessun finanziamento VC. Nessun team. Nessun budget marketing. Solo uno sviluppatore che costruisce gli strumenti che vorrebbe esistessero.

🌐 [studio1informatica.it](https://www.studio1informatica.it) · 📧 [francesco@studio1informatica.it](mailto:francesco@studio1informatica.it)

---

<div align="center">

**[🇬🇧 Read in English](README.md)**

*Fatto con ❤️ e troppo caffè nel Mugello, Italia*
*Copyright © 2026 Francesco Baldi — Studio One Informatica*

</div>
