# 🚀 Lead Generation Cleaning & Validation Tool

This project is built as part of the **Caprae Capital Partners AI-Readiness Pre-Screening Challenge**.  
It demonstrates how **data cleaning + validation** can improve lead generation quality and business outcomes.

---

## 📌 Problem Statement
Raw lead data is often noisy:
- Duplicate entries
- Invalid or missing emails
- Poorly formatted websites
- Inconsistent columns

This reduces sales efficiency and wastes time.  
Our tool **cleans, validates, and enhances lead data** before it enters a CRM or sales pipeline.

---

## ✅ Features
- 📊 **Cleans Data** → removes duplicates, empty rows, standardizes column names.  
- 📧 **Validates Emails** → checks if each email is in a valid format.  
- 🌐 **Validates Websites** → checks if website URLs are valid.  
- 📂 **Exports Clean Leads** → saves a `cleaned_leads.csv` for direct use.  

---

## ⚙️ Tech Stack
- **Python 3.12+**
- **Pandas** (data cleaning)
- **Validators** (email & URL validation)
- **Google Colab / Jupyter Notebook** for execution

---

## 📥 Setup Instructions

### 1. Clone Repo
```bash
```bash
git clone https://github.com/yourusername/leadgen-tool.git
cd leadgen-tool

pip install -r requirements.txt

python leadgen_tool.py
