# 📄 VN PDF - Professional & Secure PDF Toolkit

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Privacy: 100% Local](https://img.shields.io/badge/Privacy-100%25%20Local-success.svg)]()
[![Multilingual](https://img.shields.io/badge/Languages-EN%20%7C%20AR-orange.svg)]()

**VN PDF** is a fast, secure, and privacy-focused browser-based PDF toolkit. Unlike traditional online PDF services, VN PDF processes all documents entirely on the client-side (locally in your browser). **Your files never leave your device.**

🌐 **Live Demo:** [Insert your Vercel or custom domain link here]

---

## ✨ Features

* **🔒 100% Privacy-First:** Zero server uploads. All PDF manipulation happens directly in your browser.
* **📄 Merge PDF:** Combine multiple PDF files into a single document effortlessly.
* **✂️ Split PDF:** Extract specific pages or split your PDF into multiple ranges.
* **↕️ Reverse PDF:** Quickly reverse the page order of any PDF document.
* **🖼️ Images to PDF:** Convert various image formats into a standardized A4 PDF.
* **📸 PDF to Images:** Extract PDF pages into high-quality images (downloaded as a ZIP file).
* **📑 Reorder Pages:** Intuitive drag-and-drop interface to rearrange PDF pages.
* **🧠 PDF Mindmap:** AI-free, local text analysis to generate dynamic visual mindmaps from your PDF content.
* **🌓 UI/UX:** Fully responsive design with Dark/Light mode and bilingual support (English & Arabic).

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **PDF Processing:** [pdf-lib](https://pdf-lib.js.org/) & [PDF.js](https://mozilla.github.io/pdf.js/)
* **Data Visualization (Mindmap):** [Markmap](https://markmap.js.org/) & D3.js
* **File Compression:** JSZip
* **Backend / Analytics:** [Supabase](https://supabase.com/) (Used strictly for anonymous visitor statistics and dynamic ad banners, NOT for file storage).

---

## 🚀 Getting Started (Local Development)

Since VN PDF is a strictly client-side application, running it locally is incredibly simple.

### Prerequisites
* A modern web browser (Chrome, Firefox, Safari, Edge).
* *Optional:* A local server like VS Code's "Live Server" extension to avoid CORS issues with certain local font/worker loading.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/vnpdf.git](https://github.com/yourusername/vnpdf.git)
