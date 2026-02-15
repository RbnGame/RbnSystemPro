# RbnSystemPro 🚀

**The Ultimate Windows Post-Installation & Optimization Tool**

<img width="2064" height="864" alt="image-1" src="https://github.com/user-attachments/assets/8407a88a-5935-46b7-98d9-9d382022b45f" />

## 📖 Overview
RbnSystemPro is a modern, all-in-one utility designed to streamline the post-installation process for Windows. Whether you've just formatted your PC or want to optimize an existing system, RbnSystemPro automates hardware analysis, driver installation, software deployment, and system cleaning with a single click.

Built with **.NET 8/9** and **WPF-UI**, it offers a premium, responsive, and intuitive user experience.

## ✨ Key Features

### 🖥️ Windows Deployment
- **Automated Install:** Create a fully automated Windows format USB with `autounattend.xml`.
- **System Compatibility:** Checks for TPM 2.0, Secure Boot, and CPU compatibility for Windows 11.
- **Custom ISO:** Integrate drivers and scripts directly into your installation media.

### 🎮 Advanced Driver Manager
- **Smart GPU Detection:** Automatically identifies your NVIDIA, AMD, or Intel graphics card and downloads the precise driver.
- **Essential Chipsets:** One-click installation for Audio (Realtek), LAN/WiFi (Intel/Killer), and Chipset drivers.
- **Official Sources:** Downloads directly from vendor servers or via Windows Package Manager (winget).

### 🚀 PC Performance & Health
- **Real-Time Monitoring:** View live CPU & GPU temperatures, usage, and RAM consumption.
- **System Cleanup:** Deep clean `%TEMP%`, prefetch, and browser cache (Chrome, Edge, Opera, Brave).
- **Latency Optimization:** Tune TCP/IP settings for better gaming and streaming stability.

### 🛡️ Windows Update & Security
- **Security Dashboard:** Check Windows Activation status, Defender state, and Firewall settings.
- **Update Management:** View pending updates, force check, or pause updates easily.
- **Privacy Tools:** (Coming Soon) Telemetry blocking and bloatware removal.

### 🌐 Network Optimizer
- **Smart WiFi:** Manage wireless connections with a sticky, always-visible status bar.
- **DNS Switcher:** Instantly switch to Google (8.8.8.8) or Cloudflare (1.1.1.1) for faster browsing.
- **Network Reset:** Flush DNS cache and reset network adapters in one click.

### 📦 Software Deployment
- **Bulk Application Install:** Install essential tools (Chome, Discord, VS Code, Steam, etc.) silently in the background.
- **Winget Integration:** Secure and fast downloads directly from Microsoft's repository.

### 📊 Activity Timeline
- **History Log:** Visual timeline of every action taken (Driver install, System Clean, etc.).
- **Status Reports:** Detailed success/error logs for troubleshooting.

## 🚀 Getting Started

### Prerequisites
- Windows 10 (Version 2004+) or Windows 11.
- .NET 8.0 Desktop Runtime.
- Internet connection (for driver/software downloads).

### Installation
1.  Go to the [Releases](../../releases) page.
2.  Download the latest `RbnSystemPro_Setup_vX.X.X.exe`.
3.  Run `RbnSystemPro_Setup_vX.X.X.exe` as **Administrator**.
4.  Follow the installation wizard.

## 🛠️ Technology Stack
- **Core:** C# / .NET 8
- **UI Framework:** WPF (Windows Presentation Foundation)
- **Design System:** [WPF-UI](https://github.com/lepoco/wpfui) (Fluent Design)
- **Dependency Injection:** Microsoft.Extensions.DependencyInjection
- **Logging:** Custom File Looger (`Logs/log.txt`) & JSON Activity Log.

## 💬 Feedback & Support
Found a bug or have a suggestion? Please open an issue on our [Issues](../../issues) page or contact us directly.

## 📜 Copyright
**(c) 2026 Rbnbilisim Team**. All rights reserved.
Unauthorized copying, modification, or distribution of this software is strictly prohibited.

---
*Developed with ❤️ by the Rbnbilisim Team & AI Assistants.*
