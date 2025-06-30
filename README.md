# 🧾 PDF Page Range Split and Merger with Python

This is a simple PDF processing tool written in Python using `pypdf`.

### 🔧 What it does:

- Takes an original PDF
- Extracts a specified page range (e.g. pages 1–4)
- Replaces the last page with a new PDF page
- Outputs a new merged PDF

---

## 🧠 How It Works

1. Load `original.pdf` and `new_page.pdf`
2. Extract pages 1 to 4 (or any range you specify)
3. Append the first page from `new_page.pdf`
4. Save as `merged_output.pdf`

---

## ▶️ Usage

### 1. Install dependencies

```bash
pip install pypdf
