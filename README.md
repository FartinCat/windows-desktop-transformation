# 🪐 Minimalist Windows-to-Linux Desktop Overhaul

[![Aether Tech YouTube](https://img.shields.io/badge/YouTube-Aether%20Tech-red?style=for-the-badge&logo=youtube)](https://youtube.com/@AetherTech)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Environment: Windows 11](https://img.shields.io/badge/Environment-Windows%2011-blue?style=for-the-badge&logo=windows)](https://microsoft.com/windows)

Welcome to the official repository for the ultimate Windows 11 visual transformation workflow. This project provides the core links, scripts, and configuration guidelines showcased on **Aether Tech** to completely morph your stock desktop environment into a ultra-minimalist, Arch Linux-inspired tiled workspace.

---

## 📺 Watch the Full Tutorial

Click the banner below to watch the step-by-step visual overhaul breakdown on YouTube:

[![Windows to Arch Desktop Transformation](https://img.shields.io/badge/Aether_Tech-Click_To_Watch_Tutorial-cyan?style=filled-new-button&logo=youtube&logoColor=white&labelColor=black)](YOUR_YOUTUBE_VIDEO_URL_HERE)

> [!TIP]
> Make sure to follow the step-by-step instructions in the video to cleanly handle the custom Start Menu key interception and background gesture synchronization.

---

## 🚀 Step-by-Step Installation

Follow these precise steps to deploy the utilities cleanly without conflicting with your native system settings.

### 1. Install Background Utilities (PowerToys)
We use **PowerToys Awake** to manage system sleep states directly from the system tray. Install the suite using Windows Package Manager via PowerShell:

```powershell
winget install --id Microsoft.PowerToys --source winget
