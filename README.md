# AuraPass - Secure Local Password Vault

<p align="center">
  <img alt="AuraPass Banner" src="https://raw.githubusercontent.com/bplrdev/AuraPass/main/resources/aurapass_banner.png">
</p>

<div align="center">

[![Latest Release](https://img.shields.io/github/v/release/bplrdev/AuraPass?style=for-the-badge&color=8257E6)](https://github.com/bplrdev/AuraPass/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6.svg?style=for-the-badge)](https://github.com/bplrdev/AuraPass/releases/latest)
[![License](https://img.shields.io/badge/license-PolyForm%20Noncommercial-informational?style=for-the-badge)](https://github.com/bplrdev/AuraPass/blob/main/LICENSE)
[![Website](https://img.shields.io/badge/Website-bplr.dev-22D3EE.svg?style=for-the-badge)](https://bplr.dev)

</div>

<br/>

**AuraPass is a modern, beautiful, and secure password manager that runs entirely on your local machine.** Your privacy is paramount; your data is encrypted with a master password using the Web Crypto API and never leaves your device. Built for those who value security, privacy, and a clean user experience.

<br/>

<!-- 
  TODO: SCREENSHOT HERE! 
-->
<p align="center">
  <img src="https://raw.githubusercontent.com/bplrdev/AuraPass/main/assets/screenshot-placeholder.png" alt="AuraPass Application Screenshot" width="80%">
</p>


## ✨ Key Features

*   🔐 **Local-First & Private:** Your vault is a single file on your computer. No servers, no clouds, no tracking. You are in complete control of your data.
*   🛡️ **Strong Encryption:** Secures your vault with **AES-256-GCM** encryption. Your master key is derived using **PBKDF2** with 500,000 iterations, providing robust protection against brute-force attacks.
*   🔑 **Password Recovery:** Forget your master password? No problem. Each vault is created with a unique 24-word mnemonic recovery phrase, allowing you to regain access and set a new password.
*   🎨 **Beautiful & Customizable UI:** Choose from multiple themes (including light and dark modes), adjust UI transparency, and even change the font to create an experience that's uniquely yours.
*   👁️‍🗨️ **Security Auditing:**
    *   **Weak Password Detection:** Identifies simple and easy-to-guess passwords.
    *   **Reused Password Check:** Alerts you if you're using the same password across multiple accounts.
    *   **Breached Password Check:** Securely and anonymously checks your passwords against the Have I Been Pwned database.
*   🌐 **Automatic Icon Fetching:** Integrates with BrandFetch to automatically find and display official logos for your providers, making your vault clean and easy to navigate.
*   🔒 **Auto-Lock & Secure Clipboard:** Automatically locks the application after a period of inactivity and clears copied passwords from your clipboard after a configurable timeout.
*   ⚡ **Modern Tech Stack:** Built with Electron, React, TypeScript, and Vite for a fast, reliable, and cross-platform desktop experience.

## 🚀 Installation

AuraPass is currently available for **Windows** only.

1.  Go to the [**Latest Release**](https://github.com/bplrdev/AuraPass/releases/latest) page.
2.  Download the `AuraPass-Setup-x.x.x.exe` installer.
3.  Run the installer.

That's it! You can now launch AuraPass and create your first secure vault.

## 🛠️ Technology Stack

AuraPass is built with a modern and powerful set of technologies:

*   **Framework:** [Electron](https://www.electronjs.org/)
*   **UI Library:** [React](https://reactjs.org/)
*   **Language:** [TypeScript](https://www.typescriptlang.org/)
*   **Bundler:** [Vite](https://vitejs.dev/)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
*   **Animations:** [Framer Motion](https://www.framer.com/motion/)

## ❤️ Support the Project

AuraPass is an independent project built with care, not capital. It's free, open-source, and contains no ads, investors, or compromises.

If AuraPass brings you peace of mind and you'd like to support its continued development, please consider making a donation. Every contribution helps keep the project alive and independent.

<p align="center">
  <a href="https://ko-fi.com/bplr" target="_blank">
    <img src="https://storage.ko-fi.com/cdn/kofi3.png?v=3" alt="Donate on Ko-fi" height="45">
  </a>
</p>

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://aurapass.dev">Project Website</a> &nbsp;&middot;&nbsp;
  <a href="https://bplr.dev">Developer</a> &nbsp;&middot;&nbsp;
  <a href="mailto:contact@aurapass.dev">Contact</a>

</p>


