# 🗂️ PDF Merger

> A simple **command-line Python script** that merges multiple PDF files into a single PDF — fast and hassle-free.

---

## 🔍 Overview

**PDF Merger** is a lightweight Python CLI tool that allows users to merge any number of PDF files into one. Simply run the script, enter the number of PDFs and their filenames, and the tool will combine them into a single output file — `merged-pdf.pdf`.

---

## ✨ Features

- 📁 Merge any number of PDF files into one
- 🖊️ Enter PDF filenames dynamically at runtime
- ⚡ Instant output — no UI or heavy software required
- 🧹 Clean and minimal command-line interface

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| `Python 3.11.9` | Core programming language |
| `PyPDF2` | PDF reading & merging |

---

## 🚀 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/ajajmahmudaquil/PDFMerger.git
cd PDFMerger
```

### 2. Install Dependencies

```bash
pip install PyPDF2
```

### 3. Run the Script

```bash
python main.py
```

### 4. Follow the Prompts

```
How many pdfs do you want to merge?
> 2
Enter the name of PDF 1: file1.pdf
Enter the name of PDF 2: file2.pdf
PDF merged Successfully
```

The merged file will be saved as **`merged-pdf.pdf`** in the same directory.

---

## ⚙️ How It Works

1. The script asks the user how many PDF files they want to merge.
2. It collects the filename of each PDF one by one.
3. `PyPDF2.PdfWriter` appends each PDF file in order.
4. The final merged PDF is written as `merged-pdf.pdf` and the writer is closed.

---

## 👤 Author & Contact

**Ajaj Mahmud Aquil**
- GitHub: [@ajajmahmudaquil](https://github.com/ajajmahmudaquil)
- Portfolio: [aquils-portfolio](http://portfolio.ajajaquil.dev/)

---

> ⭐ If you found this project helpful, please give it a star on GitHub!
