# 📷 ExifTool Windows Archive

This repository provides a collection of **ExifTool** for Windows, including previous versions, in a portable `.exe` format.

ExifTool is a powerful open-source command-line tool for reading, writing, and editing metadata of a wide variety of file types, including images, videos, PDFs, and more.

---

## 📦 Available Versions

| Version | File Name                 | SHA256 Checksum (optional) |
|---------|---------------------------|-----------------------------|
| 13.32   | exiftool.exe        | B397E34867020FFECA49F2A648C14C033ADFED931FE659E643E615F772521E44            |
| 12.99   | exiftool.exe        | A731BD095AC9075E54CB0AD8DAF85951EEFCD87F6D52F44AE711D3BC7AFA03C5            |

> 📁 All binaries are renamed to `exiftool.exe` for consistency. Original downloads are from [https://exiftool.org](https://exiftool.org)

---

## ✅ Features

- 📑 Read and edit EXIF, IPTC, XMP, and other metadata
- 🖼️ Supports images (JPEG, PNG, TIFF, HEIC), video (MP4, MOV), audio, documents
- 🧱 Works via CLI and within scripting environments (e.g. Python, PowerShell)
- ⚡ Portable and does not require installation

---

## 🚀 How to Use

### 🖥️ Download

1. Go to the [Releases](https://github.com/your-username/exiftool-windows-archive/releases) section
2. Download the required version of `exiftool.exe`
3. (Optional) Verify using the checksum provided

---

### 🛠️ Installation (Optional)

If you want to use `exiftool` from any folder in the command prompt:

1. Move `exiftool.exe` to a folder like:
    - `C:\Windows\`
    - or `C:\Program Files\ExifTool\`

2. Add that folder to your system's `PATH`:
    - Search for **"Environment Variables"**
    - Edit `Path` and add the folder where `exiftool.exe` resides

3. Confirm installation:

```bash
exiftool -ver
