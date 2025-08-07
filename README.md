# 🧠 AI/ML Tasks Submission – Mohit

This repository contains 3 tasks completed as part of an AI/ML coding assignment. Each task is organized in its own folder with source code, Jupyter notebooks, and supporting files.

---

## 📁 Task 1 – Exploratory Data Analysis (EDA)

### 🔍 Objective:
Perform EDA on a dataset by cleaning it and visualizing key patterns.

### 🧾 Features:
- Handled missing values, fixed formatting, and corrected invalid entries.
- Visualized data using `matplotlib`, `seaborn`, and/or `plotly`.
- Explained the reasoning behind chosen techniques and visualizations.

### 📂 Files:
- `eda_analysis.py` or `.ipynb` – EDA workflow
- Cleaned dataset (if included)

---

## 📁 Task 2 – LLM-Based Social Media Post Generator

### 🔍 Objective:
Design a system that takes a blog article and uses an LLM to generate social media posts for 5 platforms.

### 🧠 System Design:
- **Input**: Blog article (text or URL)
- **Output**: JSON with platform-specific posts (Twitter, LinkedIn, Instagram, etc.)
- **Techniques**: Prompt engineering, multi-prompt workflows, content adaptation

### 📂 Files:
- `social_post_generator.py`
- `README.md` for system design
- Optional: `.ipynb` version for walkthrough

---

## 📁 Task 3 – PDF Compliance Analyzer

### 🔍 Objective:
Validate PDF documents against formatting and content rules.

### ✅ Features:
- Checks:
  - File type is `.pdf`
  - Font = Times New Roman, Size = 12pt
  - Margins = 1 inch
- Detects required sections:
  - Technical Requirements (≤8 pages)
  - Budget (≤4 pages)
  - Qualification (≤4 pages)
- Outputs a JSON report summarizing all checks

### 📂 Files:
- `pdf_compliance_analyzer.py`
- `sample_proposal.pdf`
- `compliance_report.json`

---

## 📦 How to Run

### Option 1: Python
```bash
python task_folder/script_name.py
