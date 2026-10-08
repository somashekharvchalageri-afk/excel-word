# 📊 Excel to Notepad Documenter

A lightweight, zero-dependency browser tool that automatically converts Excel files into beautifully aligned, human-readable plain text documents (`.txt`). 

No more manually typing out any separator strings. This tool dynamically analyzes your spreadsheet rows and scales column whitespace padding to match your longest text entry perfectly.

---

## ✨ Features
*   🚀 **100% Client-Side:** Your data never leaves your computer. Runs completely offline.
*   📐 **Smart Padding Alignment:** Dynamically calculates maximum character lengths per column.
*   💧 **Drag & Drop UI:** Toss any `.xlsx` or `.xls` file into the window for a 1-click download.
*   📝 **Notepad-Ready:** Tailored spacing optimized for monospaced plain-text documentation.

---

## 🛠️ Quick Start

### Prerequisites
To use this entirely offline without cross-origin issues, ensure you have both files in the same directory:
```text
your-repository/
├── excel-word-converter.html
└── xlsx.full.min.js
```

### Installation & Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd YOUR_REPO_NAME
   ```
2. **Launch the tool:**
   Simply **double-click** `excel-word-converter.html` to open it locally inside Google Chrome, Microsoft Edge, Safari, or Mozilla Firefox.
3. **Convert:**
   Drag and drop your spreadsheet file onto the dashed box. Your formatted documentation file will instantly download to your **Downloads** folder.

---

## 💡 Pro Tip for Notepad Users
Plain text files require a **Monospaced Font** to align correctly because variable-width fonts make space characters (` `) narrower than text characters. 

If your columns look unaligned in Notepad:
1. Open the exported `.txt` file.
2. Click **View** (or **Format**) ➔ **Font**.
3. Change the font family to **Consolas**, **Courier New**, or **Lucida Console**.


