# Automatic File Sorter

## Project Overview
The **Automatic File Sorter** is a Python script that organizes files in a folder by moving them into subfolders based on file type. It’s ideal for keeping messy folders organized automatically.  

Supported file types by default:
- PDFs → `pdf files`
- TXT → `txt files`
- Excel (`.xlsx`) → `xlsx files`

---

## Features
- Automatically creates folders for PDFs, TXT, and XLSX files.
- Moves files to the appropriate folder based on extension.
- Avoids overwriting existing files.
- Easy to extend for more file types.

---

## Requirements
- Python 3.x
- Standard libraries: `os`, `shutil`
