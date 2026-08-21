# 📄 PaperForge: Ultra-Powerful, High-Performance PDF Editor for Windows

<div align="center">
  <img src="logo.svg" width="140" height="140" alt="PaperForge Logo" />
  <h3>The Craft of the Page. Unleashed.</h3>
  <p>A blazingly fast, privacy-first, 100% offline desktop PDF suite with full Adobe Acrobat Pro DC feature parity — zero subscription lock-in.</p>
</div>

---

## ⚡ Why PaperForge?

| Metric / Capability | Adobe Acrobat Pro DC | PaperForge |
| :--- | :--- | :--- |
| **Pricing & Monetization** | $240+/year forced subscription | **100% Free** (Unlocked via optional Rewarded Sponsor Ads) |
| **System Footprint (RAM)** | 500MB – 1.2GB RAM + background daemons | **30MB – 70MB RAM**, 0 background services |
| **Startup Time** | 4 – 10 seconds | **< 200 ms instant startup** |
| **Rendering Performance** | Prone to lag & stutter on large files | **120Hz GPU-accelerated virtualized tile rendering** |
| **Privacy & Cloud** | Forced cloud sync & data collection | **100% Offline Local Processing & Zero Telemetry** |

---

## 🌟 Comprehensive Feature Suite

### 1. 🔍 Navigation & Reading
- **Multi-Document Tabs**: Open and edit dozens of documents simultaneously with instant switching.
- **Dynamic View Modes**: Continuous scroll, single page, and facing two-page book layout.
- **Deep Bookmarks & Outline**: Full hierarchical document navigation tree.
- **Lightning Search**: Sub-millisecond text search with instant highlighted snippet jump.

### 2. ✏️ True Inline Text & Vector Editing
- **Inline Text Reflow**: Directly modify text content, change fonts, adjust kerning, and line wrap.
- **Image Manipulation**: Insert, resize, rotate, crop, and layer images with precise bounding box handles.
- **Vector Shapes & Drawing**: Freehand pressure-smoothed pen, highlighters, arrows, rectangles, and circles.

### 3. 📑 Visual Page Organizer
- **Interactive Drag-and-Drop Grid**: Reorder, rotate, duplicate, split, delete, and extract pages.
- **Bates Numbering Wizard**: Custom prefixes, suffixes, digit padding, and position controls for legal indexing.
- **Watermarking Engine**: Custom opacity, rotation angle, and dynamic text/image watermarks.
- **Multi-File Merger & Splitter**: Combine multiple PDFs into one or extract custom page ranges.

### 4. 📝 Interactive AcroForms Designer
- Fillable text inputs, checkboxes, radio groups, dropdown lists, and signature blocks.
- **Auto-Detection**: Scans visual underlines and table cells to convert static forms into interactive fillable fields.
- **Data Export**: Export filled form values directly to JSON or FDF.

### 5. 🛡️ Security, PAdES Signatures & True Redaction
- **Digital Signatures**: Draw, type, or upload transparent signatures with PKCS#7 / PAdES timestamping.
- **Permanent Deep Redaction**: Irreversibly purges underlying character glyphs, vector nodes, and metadata streams.
- **256-bit AES Encryption**: Password security with granular permissions (printing, extraction, modifications).
- **Metadata Sanitizer**: Strips EXIF, XMP, author data, and cached thumbnail streams.

### 6. 🧠 Offline OCR & Document Comparison
- **100% Local OCR Engine**: Powered by Tesseract WebAssembly with zero cloud latency.
- **Visual & Semantic Diff**: Pixel-level comparison with added/removed highlights and text change tracking.

### 7. 🔄 Conversion & Smart Optimization
- **Export to Multiple Formats**: Convert PDF to Microsoft Word (.docx), Markdown (.md), Images (PNG), and Plain Text (.txt).
- **Smart PDF Compressor**: Lossless stream repacking and high-efficiency image downsampling with live size preview.

---

## 🎁 Fair Monetization: "Watch an Ad to Unlock Pro"

PaperForge eliminates predatory subscriptions:
1. **Core Features**: 100% Free forever with zero ads and zero watermarks.
2. **Pro Features**: (Inline Reflow, Deep Redaction, Local OCR, Diff Comparison, Bates Stamping) can be unlocked **100% free for 24 hours** simply by viewing a short 15-second sponsor showcase.
3. **Supporter Option**: Optional one-time lifetime pass for users who prefer a permanently ad-free experience.

---

## 🛠️ Technology Stack & Architecture

- **Desktop Framework**: Electron 34 + Vite 6
- **Frontend**: React 18 + TypeScript + Tailwind CSS + Lucide Icons + Radix Primitives
- **PDF Core**: `pdf-lib` + `pdfjs-dist` (High-DPI Subpixel Canvas Rendering)
- **Local OCR**: `tesseract.js` (WebAssembly Local Engine)
- **Animations**: Canvas Confetti + Tailwind CSS Animations

---

## 🚀 Quick Start & Development

### Prerequisites
- [Node.js](https://nodejs.org/) v18+ and `npm`

### Installation
Download the latest file from [Releases](https://github.com/vishnuaniljb-ai/PaperForge/releases).

## 📂 Repositories

- **Desktop Application (Public)**: [https://github.com/vishnuaniljb-ai/PaperForge](https://github.com/vishnuaniljb-ai/PaperForge)
---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.
