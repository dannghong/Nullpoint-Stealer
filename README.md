# Nullpoint-Stealer
Nullpoint Stealer Designed To Steal Everything, And Send To Nullpoint Panel.
![bady](https://github.com/user-attachments/assets/9c2f09f4-ee9b-4010-a0ca-4290a65843f9)

# 🕳️ NullPoint Stealer

![License](https://img.shields.io/badge/license-ECL-blueviolet)
![Status](https://img.shields.io/badge/status-Educational%20Only-red)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2B-blue)
![Language](https://img.shields.io/badge/language-C%23-brightgreen)
![Stealth](https://img.shields.io/badge/stealth-mode-lightgrey)

> **NullPoint Stealer** is a powerful, stealthy data extraction simulation tool written in **C#** for **educational and research purposes only**. It mimics the behavior of real-world malware used by threat actors, allowing cybersecurity students, researchers, and blue teams to explore how these attacks work — and how to defend against them.

---

## 🚀 Features

🧠 A showcase of real-world data harvesting functionality, including:

- 🔐 **Password recovery** from Chromium-based browsers
- 🍪 **Cookie** extraction & session hijack simulation
- 📑 Collects **bookmarks**, **autofill data**, and **browser history**
- 📸 **Screenshot** capture of the active desktop
- 📂 Steals **files** from `Desktop`, `Documents`, `Downloads`
- 🧳 Scans for installed **VPN clients** and extracts config/logins
- 🎮 Targets game platforms like **Steam**, **Epic**, **Battle.net**
- 💰 Detects **crypto wallets** (Metamask, Exodus, Atomic, etc.)
- 📄 Dumps local **.txt**, **.docx**, and **.log** files for juicy data
- 🧩 **Modular architecture** — add your own stealers easily
- ⚡ Lightweight, fast execution with minimal dependencies
- 🕶️ Designed to be stealthy and persistent (for simulation only)

---

## 🧪 Intended Use

This project is built as a **cybersecurity lab tool** for:

- 🧬 Malware analysis practice
- 🧑‍💻 Ethical hacking labs
- 🛡️ Blue team defense testing
- 🔐 Detection engineering (YARA/Sigma rules, etc.)
- 🧠 Understanding how modern stealers operate

Run in **virtualized environments only.**

---

## ⚠️ Disclaimer

> This software is provided **exclusively for educational and ethical research purposes.**
>
> - ❌ Do **NOT** use it on real targets or personal machines.
> - ❌ Do **NOT** deploy or distribute this code with malicious intent.
> - ✅ Use only in isolated VMs or malware sandboxes.
>
> The author takes **no responsibility** for misuse or damages. By using this software, you agree to use it **legally and ethically**, in full compliance with local and international laws.

---

## 🛠️ Build & Run

> Requires: **.NET Framework 4.7.2+** or **.NET 6.0**, Visual Studio / MSBuild

```bash
git clone https://github.com/yourusername/nullpoint-stealer
cd nullpoint-stealer
Open the .sln in Visual Studio
Build → Release Mode
Run in a VM
