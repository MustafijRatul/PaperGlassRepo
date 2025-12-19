# 💎 PaperGlass Pro | Enterprise Document Studio

![License](https://img.shields.io/badge/License-Proprietary-orange) ![Python](https://img.shields.io/badge/Python-3.10%2B-blue) ![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue) ![Status](https://img.shields.io/badge/Status-Stable-green)

**PaperGlass Pro** is a next-generation desktop utility designed for seamless document conversion and management. Built on the robust **PySide6** framework, it bridges the gap between powerful functionality and stunning aesthetic design.

It features a native **Windows 11 Acrylic/Mica interface**, physics-based animations, and a multi-threaded conversion engine that ensures your workflow never freezes.

---

## ✨ Key Features

### 🎨 Premium User Experience
*   **True Glassmorphism:** Real-time Windows DWM Acrylic blur effects.
*   **Adaptive Themes:** Deep "Obsidian" Dark Mode and "Frost" Ambient Mode.
*   **Fluid Animations:** Hover effects, sliding page transitions, and glass-glow buttons.
*   **Native Integration:** Custom dark title bar with native Windows snap/minimize support.

### ⚡ Intelligent Conversion Engine
*   **Smart Detection:** Automatically validates file formats before processing.
*   **Multi-Threaded:** Conversions run in background threads to keep UI responsive.
*   **Supported Formats:**
    *   📝 **MD to DOCX** (Preserves formatting, headers, and code blocks)
    *   📘 **DOCX to PDF** (Enterprise-grade rendering)
    *   📕 **PDF to DOCX** (OCR-capable extraction)
    *   📊 **XLSX to PDF** (Spreadsheet formatting)
    *   🔨 **PDF Flattener** (300/600/900 DPI options for legal compliance)

### 🛡️ Enterprise Control (Admin Mode)
*   **Remote Management:** Connects to a cloud-based JSON controller.
*   **Update System:** Auto-detects critical updates and forces patches if required.
*   **Security:** UUID-based licensing with remote ban capability.
*   **Broadcast System:** Send global announcements to all active users instantly.

---

## 🛠️ Tech Stack

*   **Core:** Python 3.12
*   **UI Framework:** PySide6 (Qt for Python)
*   **Styling:** QSS (Qt Style Sheets) & Windows DWM API (`ctypes`)
*   **Engines:** `pymupdf` (fitz), `pdf2docx`, `docx2pdf`, `htmldocx`, `pandas`
*   **Icons:** FontAwesome 5 (`qtawesome`)

---

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MustafijRatul/PaperGlassRepo.git
   ```
2. Install dependencies:
   ```bash
   pip install PySide6 pymupdf pdf2docx docx2pdf markdown python-docx pandas reportlab qtawesome htmldocx
   ```
3. Run the application:
   ```bash
   python main.py
   ```

---

## 👤 Author

**Designed & Developed by Ratul**
*   [GitHub](https://github.com/MustafijRatul)
*   [Facebook](https://facebook.com)

---
*© 2025 PaperGlass Pro. All rights reserved.*
