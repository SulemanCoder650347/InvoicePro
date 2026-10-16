# ⚡ InvoicePro — Modern Mobile & Web Invoice Studio

<div align="center">

[![Download Android APK](https://img.shields.io/badge/📥_Download-Android_APK-22c55e?style=for-the-badge&logo=android&logoColor=white)](https://github.com/SulemanCoder650347/InvoicePro/raw/main/GitHub.apk)
[![Launch Live Web App](https://img.shields.io/badge/🌐_Launch-Live_Web_App-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://sulemancoder650347.github.io/InvoicePro/)

</div># ⚡ InvoicePro — Modern Mobile & Web Invoice Studio

InvoicePro is a sleek, responsive, and mobile-first invoice generator built for freelancers, agencies, and logistics operators. It supports instant PDF exports, real-time interactive invoice previews, direct WhatsApp sharing, and full offline PWA capabilities.

---

## ✨ Features

- 🎨 **4 Dynamic FinTech Themes**:
  - 🟣 **Electric Indigo** (Cyber SaaS / Modern Web3)
  - 🟢 **Emerald Mint** (Finance, Wealth & Classic Invoicing)
  - 🔵 **Sapphire Sky** (Corporate FinTech)
  - 🟠 **Sunset Amber** (Warm & High-contrast)
- 📦 **Dual Invoice Modes**:
  - **Products & Professional Services**: Line items, quantity, unit rate, automatic subtotal calculation.
  - **Freight & Logistics**: Route origin, destination, cargo load/weight, trip charges, driver & truck info.
- 👁️ **Live Interactive Preview**: Pixel-perfect printable invoice sheet preview with real-time computations.
- 📄 **Crisp PDF Generation**: High-resolution vector PDF generation via `jsPDF` styled dynamically with the selected theme accent.
- 💬 **WhatsApp Direct Share**: Automatically formats invoice details and opens a direct chat with the client's phone number.
- 📁 **Local Storage History**: Save, restore, and delete past invoices without any backend database.
- 🖼️ **Brand Logo Support**: Upload company logo to embed directly on preview sheets and downloaded PDFs.
- 📱 **Progressive Web App (PWA)**: Includes `manifest.json` and `sw.js` for 100% offline support and native home-screen installation on Android & iOS.

---

## 🚀 Quick Start

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/InvoicePro.git
   ```
2. Open `index.html` in any modern web browser:
   - Double click `index.html` OR
   - Run a local server: `npx serve .`

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Modern CSS3 (Glassmorphism, CSS Custom Properties), Vanilla JavaScript
- **Libraries**: [jsPDF](https://github.com/parallax/jsPDF) (Client-side PDF generation)
- **Typography**: Plus Jakarta Sans, Outfit, JetBrains Mono
- **Offline / PWA**: Service Workers Cache API, Web App Manifest
