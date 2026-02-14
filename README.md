# RbnSystemPro 🚀

**The Ultimate Windows Post-Installation & Optimization Tool**

![RbnSystemPro Banner](https://via.placeholder.com/1200x400?text=RbnSystemPro+Dashboard+Screenshot)

## 📖 Overview
RbnSystemPro is a modern, all-in-one utility designed to streamline the post-installation process for Windows. Whether you've just formatted your PC or want to optimize an existing system, RbnSystemPro automates hardware analysis, driver installation, software deployment, and system cleaning with a single click.

Built with **.NET 8/9** and **WPF-UI**, it offers a premium, responsive, and intuitive user experience.

## ✨ Key Features

### 🌐 Network Optimizer
- **Smart WiFi Management:** View, connect, and manage WiFi networks with a sticky connection header.
- **DNS Optimization:** One-click switch to Google DNS (8.8.8.8) or Cloudflare DNS (1.1.1.1).
- **Network Reset:** Flush DNS, reset TCP/IP stack, and optimize latency.

### 🧹 System Cleaner
- **Browser Cleanup:** Clears cache and temp files for Chrome, Edge, Firefox, Brave, and Opera.
- **Deep Clean:** Removes system temporary files (`%TEMP%`, `Windows\Temp`) and obsolete Registry entries.
- **Instant Result:** view detailed logs of reclaimed space.

### 🎮 Driver Manager
- **Essential Drivers:** Single-click installation for Chipset, Audio, LAN, and WiFi drivers.
- **GPU Drivers:** Auto-detects NVIDIA/AMD/Intel cards and installs the correct drivers via official sources/winget.
- **Smart Detection:** Identifies hardware IDs to prevent wrong installations.

### 📦 Software Deployment
- **Bulk Install:** Install essential apps (Chrome, VS Code, Discord, etc.) in one go.
- **Silent Mode:** No "Next, Next, Finish" - everything installs in the background.
- **Winget Integration:** Uses the official Windows Package Manager for secure and up-to-date software.

### 📊 Dashboard & Activity Log
- **Visual Timeline:** Track every action (Success/Fail) in a beautiful timeline view.
- **Hardware Monitor:** Real-time CPU, GPU, and RAM usage stats.
- **System Info:** Quick summary of your OS version, BIOS, and specs.

## 🚀 Getting Started

### Prerequisites
- Windows 10 (Version 2004+) or Windows 11.
- .NET 8.0 Desktop Runtime.
- Internet connection (for driver/software downloads).

### Installation
1.  Go to the [Releases](../../releases) page.
2.  Download the latest `RbnSystemPro-vX.X.X.zip`.
3.  Extract the archive to a folder (e.g., `C:\RbnSystemPro`).
4.  Run `RbnSystemPro.exe` as **Administrator**.

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
