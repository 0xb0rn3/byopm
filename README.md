<div align="center">

# 🛡️ BYOPM v0.1.1

```
██████╗ ██╗   ██╗ ██████╗ ██████╗ ███╗   ███╗
██╔══██╗╚██╗ ██╔╝██╔═══██╗██╔══██╗████╗ ████║
██████╔╝ ╚████╔╝ ██║   ██║██████╔╝██╔████╔██║
██╔══██╗  ╚██╔╝  ██║   ██║██╔═══╝ ██║╚██╔╝██║
██████╔╝   ██║   ╚██████╔╝██║     ██║ ╚═╝ ██║
╚═════╝    ╚═╝    ╚═════╝ ╚═╝     ╚═╝     ╚═╝
```

### 🛡️ **Build Your Own Pentest Machine** 🛡️

**Intelligent OS Detection & Automated Security Framework Deployment**

[![Version](https://img.shields.io/badge/version-0.1.1-00ff88?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/0xb0rn3/byopm)
[![Platform](https://img.shields.io/badge/platform-Linux-00d4ff?style=for-the-badge&logo=linux&logoColor=white)](https://www.linux.org/)
[![License](https://img.shields.io/badge/license-GPL--3.0-blue?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

[![Tools](https://img.shields.io/badge/🛠️_2_Frameworks-00ff88?style=flat-square)]()
[![Distros](https://img.shields.io/badge/📦_20+_Supported_Distros-00d4ff?style=flat-square)]()
[![Automation](https://img.shields.io/badge/⚡_100%_Automated-ffbe0b?style=flat-square)]()

**[🚀 Quick Start](#-one-command-deployment)** • 
**[✨ Features](#-what-is-byopm)** • 
**[📦 Frameworks](#-integrated-security-frameworks)** • 
**[🎯 Usage](#-usage-guide)** • 
**[🧪 Tested Systems](#-tested--verified-systems)** • 
**[🛡️ Support](#-support)** • 
**[👨‍💻 Author](#-author)**

---

</div>

## 🎯 **What is BYOPM?**

**BYOPM (Build Your Own Pentest Machine)** is an intelligent, automated deployment system that transforms any compatible Linux distribution into a fully-equipped penetration testing powerhouse. By detecting your operating system family and automatically deploying the appropriate security framework, BYOPM eliminates the complexity of manual tool installation.

<div align="center">

### 🔥 **The Ultimate Security Framework Orchestrator**

</div>

<table>
<tr>
<td width="50%">

#### 🧠 **Intelligent Detection**
- **Automatic OS Recognition** - Detects 20+ Linux distributions
- **Family Classification** - Identifies Debian-based vs Arch-based systems
- **Hardware Analysis** - CPU, RAM, disk space verification
- **Kernel Detection** - Version and architecture compatibility checks
- **Package Manager Mapping** - APT, Pacman, and more

</td>
<td width="50%">

#### ⚡ **Automated Deployment**
- **Zero Configuration** - Works out-of-the-box
- **Framework Selection** - Automatically chooses Krilin or Kygox
- **Dependency Management** - Installs all prerequisites automatically
- **Repository Integration** - Adds Kali/BlackArch repositories temporarily
- **Clean Exit** - Removes temporary configurations after deployment

</td>
</tr>
</table>

---

## 🚀 **One-Command Deployment**

<div align="center">

### ⚡ **Get Started in Seconds**

```bash
# Clone the repository
git clone https://github.com/0xb0rn3/byopm.git

# Enter directory
cd byopm

# Make executable
chmod +x byopm

# Run BYOPM (interactive mode)
sudo ./byopm

# Or run with options
sudo ./byopm --verbose    # Verbose output
sudo ./byopm --dry-run    # Test without changes
sudo ./byopm --no-backup  # Skip backup creation
```

</div>

### 📺 **What Happens Next?**

```
🔍 System Analysis Complete
  • Operating System: Kali Linux
  • OS Family: Debian-based
  • Package Manager: apt
  • Recommended Tool: Krilin
  • Architecture: x86_64
  • Kernel: 6.1.0-kali9-amd64

⚡ Deployment Confirmation
  You are about to deploy: Krilin Security Framework
  Target system: Kali Linux
  
✓ Prerequisites Verification
✓ Dependency Installation
✓ Repository Configuration
🚀 Launching Krilin Security Framework...

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  KRILIN - TACTICAL SECURITY ARSENAL
  Combat-Ready Framework v0.2 Stable
  
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

[*] System Reconnaissance Complete
[+] Debian Version: 12 (bookworm)
[+] Available Tools: 200+ security packages

[*] Select tactical option (0-10):
```

---

## ✨ **Core Features**

<div align="center">

### 🎨 **What Makes BYOPM Special?**

</div>

<table>
<tr>
<td width="25%" align="center">
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/brain.svg" width="60" height="60">
<h3>🧠 Smart Detection</h3>
<p>Automatically identifies your system and selects the perfect security framework</p>
</td>
<td width="25%" align="center">
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/rocket.svg" width="60" height="60">
<h3>⚡ Zero Config</h3>
<p>No manual setup required - everything is automated from detection to deployment</p>
</td>
<td width="25%" align="center">
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/shield-halved.svg" width="60" height="60">
<h3>🛡️ Safe Deploy</h3>
<p>Creates backups, validates systems, and ensures clean rollback capability</p>
</td>
<td width="25%" align="center">
<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/terminal.svg" width="60" height="60">
<h3>🎭 Beautiful UI</h3>
<p>Modern terminal interface with progress bars, spinners, and color-coded feedback</p>
</td>
</tr>
</table>

### 🎯 **Comprehensive Feature Set**

```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║  🔍 INTELLIGENT SYSTEM DETECTION                                         ║
║  ├─ Automatic OS identification (Debian, Ubuntu, Kali, Parrot, etc.)   ║
║  ├─ Architecture detection (x86_64, ARM)                                ║
║  ├─ Kernel version analysis                                             ║
║  ├─ Resource availability check (RAM, Disk, CPU)                        ║
║  └─ Package manager verification                                        ║
║                                                                          ║
║  ⚡ AUTOMATED FRAMEWORK DEPLOYMENT                                       ║
║  ├─ Krilin for Debian-based systems (Debian, Ubuntu, Kali, Parrot)     ║
║  ├─ Kygox for Arch-based systems (Arch, Manjaro, Garuda, BlackArch)    ║
║  ├─ Automatic dependency resolution                                     ║
║  ├─ Repository management (temporary integration)                       ║
║  └─ Clean uninstallation support                                        ║
║                                                                          ║
║  🛡️ SAFETY & RELIABILITY                                                 ║
║  ├─ Pre-deployment system validation                                    ║
║  ├─ Automatic backup creation                                           ║
║  ├─ Error handling & recovery                                           ║
║  ├─ Progress tracking & logging                                         ║
║  └─ Rollback capability                                                 ║
║                                                                          ║
║  🎨 MODERN USER EXPERIENCE                                               ║
║  ├─ Animated progress indicators                                        ║
║  ├─ Color-coded output (success, error, warning, info)                 ║
║  ├─ Interactive menu system                                             ║
║  ├─ Verbose mode for debugging                                          ║
║  └─ Comprehensive help system                                           ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

---

## 📦 **Integrated Security Frameworks**

BYOPM intelligently chains two powerful security frameworks based on your system type:

<div align="center">

### 🔗 **The Framework Chain**

</div>

<table>
<tr>
<td width="50%">

### 🦸 **Krilin - Debian Security Framework**

<div align="center">

```
███╗   ███╗██████╗ ██╗██╗     ██╗███╗   ██╗
████╗ ████║██╔══██╗██║██║     ██║████╗  ██║
██╔████╔██║██████╔╝██║██║     ██║██╔██╗ ██║
██║╚██╔╝██║██╔══██╗██║██║     ██║██║╚██╗██║
██║ ╚═╝ ██║██║  ██║██║███████╗██║██║ ╚████║
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝╚══════╝╚═╝╚═╝  ╚═══╝
```

**v0.2 Stable**

</div>

#### 🎯 **Target Systems**
- ✅ Debian GNU/Linux (11+, 12 Bookworm)
- ✅ Ubuntu Linux (20.04+, 22.04, 24.04)
- ✅ Kali Linux (Rolling)
- ✅ Parrot Security OS
- ✅ Linux Mint
- ✅ Pop!_OS
- ✅ Elementary OS
- ✅ Zorin OS

#### 🛠️ **Features**
- **10 Security Categories** covering all pentesting phases
- **200+ Tools** from Kali Linux repositories
- **Intelligent Repository Management** with automatic cleanup
- **Debian Backports Kernel** support
- **Kali Linux Kernel** integration
- **Individual Tool Selection** for precise installations
- **Complete Arsenal** option (10+ GB deployment)

#### 📚 **Tool Categories**
1. 🔍 **Information Gathering** - nmap, dnsrecon, theharvester, recon-ng
2. 🔎 **Vulnerability Analysis** - nikto, sqlmap, lynis, openvas
3. 💥 **Exploitation Tools** - metasploit-framework, exploitdb, set
4. 📡 **Wireless Attacks** - aircrack-ng, wifite, kismet, reaver
5. 🌐 **Web Application Analysis** - burpsuite, zaproxy, wfuzz, dirb
6. 🔑 **Password Attacks** - hydra, john, hashcat, crunch
7. 🎯 **Individual Kali Tools** - Custom selection
8. 🧰 **Debian Backports Kernel** - Latest stable kernel
9. 🔥 **Kali Linux Kernel** - Security-optimized kernel
10. ⚠️ **All Kali Hacking Tools** - Complete arsenal

</td>
<td width="50%">

### ⚡ **Kygox - Arch Security Arsenal**

<div align="center">

```
██╗  ██╗██╗   ██╗ ██████╗  ██████╗ ██╗  ██╗
██║ ██╔╝╚██╗ ██╔╝██╔════╝ ██╔═══██╗╚██╗██╔╝
█████╔╝  ╚████╔╝ ██║  ███╗██║   ██║ ╚███╔╝ 
██╔═██╗   ╚██╔╝  ██║   ██║██║   ██║ ██╔██╗ 
██║  ██╗   ██║   ╚██████╔╝╚██████╔╝██╔╝ ██╗
╚═╝  ╚═╝   ╚═╝    ╚═════╝  ╚═════╝ ╚═╝  ╚═╝
```

**v1.0.1 Nebula**

</div>

#### 🎯 **Target Systems**
- ✅ Arch Linux (Rolling)
- ✅ Archcraft
- ✅ Manjaro Linux
- ✅ EndeavourOS
- ✅ Garuda Linux
- ✅ BlackArch Linux
- ✅ Artix Linux
- ✅ ArcoLinux

#### 🛠️ **Features**
- **10 Security Categories** based on BlackArch groups
- **2800+ Tools** from BlackArch repositories
- **5 Animated Loaders** for visual feedback
- **Real-time Progress Tracking** with percentages
- **Smart GPG Management** with auto-recovery
- **Batch Processing** (50 tools at once)
- **Complete Arsenal** installation support
- **State Management** with rollback capability

#### 📚 **Tool Categories**
1. 🔍 **Information Gathering** - scanners, recon, fingerprinting
2. 🔎 **Vulnerability Analysis** - scanners, fuzzers, exploitation
3. 🌐 **Web Application Analysis** - web testing, proxies
4. 🔑 **Password Attacks** - crackers, password tools, crypto
5. 📡 **Wireless Attacks** - WiFi, Bluetooth, NFC tools
6. 💥 **Exploitation Tools** - exploits, backdoors, binaries
7. 🔬 **Digital Forensics** - forensics, malware, reversing
8. 🎭 **Sniffing & Spoofing** - sniffers, spoofers, proxies
9. 🎯 **Post Exploitation** - backdoors, tunnels, keyloggers
10. 🎪 **Social Engineering** - social engineering, VoIP

</td>
</tr>
</table>

### 🔗 **How BYOPM Chains These Frameworks**

```
┌─────────────────────────────────────────────────────────────────┐
│                      BYOPM Orchestration                        │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  Step 1: System Detection                                      │
│  ├─ Detect OS (via /etc/os-release, lsb_release)              │
│  ├─ Identify family (Debian vs Arch)                          │
│  ├─ Verify package manager (apt vs pacman)                    │
│  └─ Check system resources                                    │
│                                                                 │
│  Step 2: Framework Selection                                   │
│  ├─ Debian-based → Krilin                                     │
│  ├─ Arch-based → Kygox                                        │
│  └─ Unsupported → Error with recommendations                  │
│                                                                 │
│  Step 3: Pre-Deployment                                        │
│  ├─ Install prerequisites (git, curl, wget, python)           │
│  ├─ Create system backup                                      │
│  ├─ Verify disk space (minimum 5GB, recommended 20GB)         │
│  └─ Check internet connectivity                               │
│                                                                 │
│  Step 4: Framework Deployment                                  │
│  ├─ Clone framework repository                                │
│  ├─ Set proper permissions                                    │
│  ├─ Execute framework launcher (run or kygox)                 │
│  └─ Pass control to framework's interactive menu              │
│                                                                 │
│  Step 5: Post-Deployment                                       │
│  ├─ Log deployment history                                    │
│  ├─ Clean temporary files                                     │
│  ├─ Show success summary                                      │
│  └─ Provide next steps                                        │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🌍 **Supported Operating Systems**

<div align="center">

### ✅ **20+ Linux Distributions**

</div>

<table>
<tr>
<td width="50%">

### 🟦 **Debian-Based Systems** → Krilin

#### Officially Tested ✅
- 🧊 **Debian** (11 Bullseye, 12 Bookworm)
- 🟧 **Ubuntu** (20.04 LTS, 22.04 LTS, 24.04 LTS)
- 🐉 **Kali Linux** (Rolling Release)
- 🦜 **Parrot Security OS** (Latest)
- 🌿 **Linux Mint** (21.x, 22.x)
- 🎨 **Pop!_OS** (22.04)

#### Community Verified ✅
- 💎 **Elementary OS**
- 🔷 **Zorin OS**
- 🌊 **Deepin Linux**
- 🔵 **MX Linux**

</td>
<td width="50%">

### 🔵 **Arch-Based Systems** → Kygox

#### Officially Tested ✅
- 🏛️ **Arch Linux** (Rolling Release)
- 🎨 **Archcraft** (Latest)
- 🦅 **Garuda Linux** (Latest)
- 🟢 **Manjaro** (Stable)
- 🟣 **EndeavourOS** (Latest)

#### Community Verified ✅
- ⚫ **BlackArch Linux**
- 🔴 **ArcoLinux**
- ⚪ **Artix Linux** (systemd-free)
- 🔵 **Parabola GNU/Linux**

</td>
</tr>
</table>

### 📊 **Compatibility Matrix**

| Distribution | BYOPM | Framework | Status | Notes |
|:------------|:-----:|:---------:|:------:|:------|
| 🧊 **Debian 12** | ✅ | Krilin | Full Support | Bookworm tested |
| 🟧 **Ubuntu 24.04** | ✅ | Krilin | Full Support | LTS recommended |
| 🐉 **Kali Rolling** | ✅ | Krilin | Full Support | Native pentesting tools |
| 🦜 **Parrot OS** | ✅ | Krilin | Full Support | Security-focused |
| 🏛️ **Arch Linux** | ✅ | Kygox | Full Support | Rolling release |
| 🎨 **Archcraft** | ✅ | Kygox | Full Support | Lightweight |
| 🦅 **Garuda** | ✅ | Kygox | Full Support | Gaming optimized |
| 🟢 **Manjaro** | ✅ | Kygox | Full Support | User-friendly |
| 🔴 **RedHat/CentOS** | ❌ | None | Not Supported | Use Fedora Security Lab |
| 🟢 **OpenSUSE** | ❌ | None | Not Supported | Use native tools |

---

## 💻 **System Requirements**

<div align="center">

### 🖥️ **Minimum & Recommended Specifications**

</div>

<table>
<tr>
<td width="50%">

### ⚠️ **Minimum Requirements**

```yaml
Operating System:
  • Debian-based or Arch-based Linux
  • Kernel 4.0+ (5.0+ recommended)
  • 64-bit architecture

Hardware:
  • Processor: Dual-core 2.0GHz
  • RAM: 4GB (8GB for full arsenal)
  • Storage: 20GB free space
  • Network: Stable internet connection

Software:
  • Root/sudo access
  • bash 4.0+
  • Package manager (apt/pacman)
  • Basic utilities (curl, wget, git)
```

</td>
<td width="50%">

### ✨ **Recommended Specifications**

```yaml
Operating System:
  • Latest stable release
  • Kernel 5.15+ or newer
  • x86_64 architecture

Hardware:
  • Processor: Quad-core 2.5GHz+
  • RAM: 16GB (32GB for heavy workloads)
  • Storage: 50GB+ SSD
  • Network: Broadband (10+ Mbps)

Software:
  • Updated system packages
  • Python 3.8+
  • GPG/GnuPG installed
  • Build essentials
```

</td>
</tr>
</table>

### 📏 **Storage Requirements by Deployment Type**

| Deployment Type | Minimum Space | Recommended | Average Install Time |
|:----------------|:-------------:|:-----------:|:--------------------:|
| **BYOPM Only** | 100MB | 500MB | < 1 minute |
| **Single Category** | 2GB | 5GB | 5-15 minutes |
| **Multiple Categories** | 5GB | 10GB | 15-45 minutes |
| **Full Arsenal (Krilin)** | 10GB | 20GB | 1-3 hours |
| **Full Arsenal (Kygox)** | 15GB | 30GB | 2-4 hours |

---

## 🚀 **Usage Guide**

<div align="center">

### 📖 **Complete Command Reference**

</div>

### 🎮 **Interactive Mode (Recommended)**

```bash
# Standard interactive deployment
sudo ./byopm

# This will:
# 1. Display beautiful ASCII banner
# 2. Detect your operating system
# 3. Show system information and recommendations
# 4. Present interactive menu with options
# 5. Deploy selected framework
# 6. Hand over control to framework menu
```

### ⚙️ **Command-Line Options**

```bash
# Help and Information
./byopm --help              # Show usage instructions
./byopm --version           # Display version information

# Deployment Modes
sudo ./byopm                # Interactive mode (default)
sudo ./byopm --verbose      # Verbose output with detailed logs
sudo ./byopm --dry-run      # Preview actions without executing

# Safety Options
sudo ./byopm --no-backup    # Skip automatic backup creation
sudo ./byopm --force        # Force deployment (skip confirmations)

# Examples
sudo ./byopm -v             # Short form of --verbose
sudo ./byopm -d             # Short form of --dry-run
sudo ./byopm --verbose --dry-run  # Combine options
```

### 📋 **Interactive Menu Options**

Once BYOPM launches the framework, you'll see a menu:

```
╔══════════════════════════════════════════════════════════════╗
║              BYOPM OPTIONS MENU                              ║
╠══════════════════════════════════════════════════════════════╣
║  1) 🚀 Deploy Security Tools              [Recommended]      ║
║  2) 🔍 Show System Information                               ║
║  3) ⚙️ Check Prerequisites                                    ║
║  4) 📦 Update Tool Repositories                              ║
║  5) ℹ️ View Deployment History                               ║
║  6) 🔥 Enable Verbose Mode                                   ║
║  0) ❌ Exit                                                   ║
╚══════════════════════════════════════════════════════════════╝

Select option:
```

**Option Details:**

1. **Deploy Security Tools** - Launches framework (Krilin or Kygox) with full menu
2. **Show System Information** - Displays detailed system analysis
3. **Check Prerequisites** - Verifies all dependencies are installed
4. **Update Tool Repositories** - Refreshes package databases
5. **View Deployment History** - Shows previous deployment logs
6. **Enable Verbose Mode** - Activates detailed debugging output
0. **Exit** - Safely exits BYOPM with cleanup

---

## 🎯 **Real-World Usage Examples**

<div align="center">

### 💡 **Practical Scenarios**

</div>

<details>
<summary><b>🛡️ Scenario 1: Bug Bounty Hunter on Ubuntu</b></summary>

```bash
# System: Ubuntu 22.04 LTS
# Goal: Set up web application testing environment

$ sudo ./byopm

# BYOPM Output:
🔍 System Analysis Complete
  • Operating System: Ubuntu Linux
  • OS Family: Debian-based
  • Package Manager: apt
  • Recommended Tool: Krilin
  
✓ Prerequisites installed
✓ Backup created
🚀 Launching Krilin Security Framework...

# Krilin Menu appears:
[*] Select tactical option (0-10):
5  # Web Application Analysis

# Installation begins:
[*] Deploying Web Application Analysis arsenal...
✓ burpsuite
✓ zaproxy  
✓ sqlmap
✓ wfuzz
✓ dirb
✓ gobuster
✓ ffuf

[+] Successfully deployed 156 tools
[+] Your Web Application Analysis is now combat ready.
```

**Result:** Complete web security testing suite installed and ready!

</details>

<details>
<summary><b>🔓 Scenario 2: Network Pentester on Arch Linux</b></summary>

```bash
# System: Arch Linux
# Goal: Full penetration testing arsenal

$ sudo ./byopm

# BYOPM Output:
🔍 System Analysis Complete
  • Operating System: Arch Linux
  • OS Family: Arch-based
  • Package Manager: pacman
  • Recommended Tool: Kygox
  • Available Tools: 2847

✓ System validation complete
🚀 Launching Kygox Security Arsenal...

# Kygox Menu with animations:
🎬 Cinematic loaders activated
[1] Information Gathering
[5] Wireless Attacks
[8] Sniffing & Spoofing

# Select multiple categories
🔨 Forging tools... [████████████░░░] 75%
💻 01▓▒░10▓▒░ Configuring system... 100%
✓ 487 tools deployed successfully!
```

**Result:** Comprehensive network testing environment ready!

</details>

<details>
<summary><b>🎓 Scenario 3: Student on Kali Linux</b></summary>

```bash
# System: Kali Linux (already has tools)
# Goal: Organize and update existing tools

$ sudo ./byopm

# BYOPM Output:
🔍 System Analysis Complete
  • Operating System: Kali Linux
  • OS Family: Debian-based
  • Note: Kali already includes most pentesting tools
  
⚠️ Kali Linux detected!
This system already includes extensive security tools.
BYOPM can help organize and supplement your arsenal.

Options:
  1) Update existing tools
  2) Add specialized categories
  3) Install custom kernel
  4) Exit

# User selects: 1 (Update existing tools)
[*] Refreshing Kali repositories...
[*] Updating installed packages...
✓ 1,247 packages updated
✓ 23 new tools available
```

**Result:** Kali system updated and optimized!

</details>

<details>
<summary><b>🏢 Scenario 4: SOC Analyst on Debian Server</b></summary>

```bash
# System: Debian 12 Bookworm Server
# Goal: Forensics and monitoring tools only

$ sudo ./byopm --verbose

# BYOPM Output (verbose mode):
[DEBUG] Loading configuration...
[DEBUG] Checking system resources...
[INFO] Detected Debian 12 Bookworm
[INFO] 64GB RAM available
[INFO] 500GB free disk space

🔍 System Analysis Complete
  • Operating System: Debian GNU/Linux
  • Sufficient resources for full deployment
  
# Deploy specific categories
[7] Individual Kali Tools
  
# User input:
Tools to deploy: volatility autopsy sleuthkit wireshark tcpdump

🔨 Installing volatility... ✓
🔨 Installing autopsy... ✓
🔨 Installing sleuthkit... ✓
🔨 Installing wireshark... ✓
🔨 Installing tcpdump... ✓

[+] 5/5 tools installed successfully
[+] Forensics toolkit ready for analysis
```

**Result:** Targeted forensics deployment on production server!

</details>

---

## 🧪 **Tested & Verified Systems**

<div align="center">

### ✅ **Comprehensive Testing Matrix**

</div>

### 🟦 **Debian-Based Distributions**

| Distribution | Version | BYOPM | Krilin | Status | Notes |
|:------------|:-------:|:-----:|:------:|:------:|:------|
| 🧊 **Debian** | 11 (Bullseye) | ✅ | ✅ | Stable | LTS support |
| 🧊 **Debian** | 12 (Bookworm) | ✅ | ✅ | Stable | Current stable |
|
