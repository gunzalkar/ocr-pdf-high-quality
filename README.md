# OCR PDF High Quality - Web App

A high-quality, browser-based OCR text extraction tool. Processes PDFs and images entirely client-side — no file uploads to any server.

## 🌐 Live Demo
**[Try it live on kshitijgunjalkar.com](https://kshitijgunjalkar.com/projects/ocr-pdf-tool/)**

## Features

- **Multi-format support**: PDF, PNG, JPG, JPEG, BMP, TIFF, WEBP, GIF
- **Multi-file upload**: Drag & drop or browse — process multiple files at once
- **50 MB limit**: Client-side enforcement
- **Multi-language OCR**: English, Hindi, Marathi, Arabic, French, German, Spanish, Japanese, Chinese, Korean
- **ZIP export**: Download all extracted text files in a single ZIP archive
- **100% client-side**: All processing happens in your browser using Tesseract.js and PDF.js
- **No server uploads**: Your documents never leave your device

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| [Tesseract.js](https://tesseract.projectnaptha.com/) | OCR engine (WASM) |
| [PDF.js](https://mozilla.github.io/pdf.js/) | PDF rendering |
| [JSZip](https://stuk.github.io/jszip/) | ZIP generation |
| Vanilla JS/HTML/CSS | Frontend |

## How It Works

1. Drop files (PDFs or images) into the upload zone
2. Select the OCR language
3. Click **Extract Text**
4. PDF pages are rendered to high-resolution canvas images via PDF.js
5. Each image is processed through Tesseract.js OCR engine
6. Results are displayed and can be downloaded as a ZIP

## Original Python Script

The `chunk_ocr.py` script is the original Python-based implementation using Tesseract CLI for server-side batch processing.

## Author

**Kshitij Gunjalkar** — [kshitijgunjalkar.com](https://kshitijgunjalkar.com)
