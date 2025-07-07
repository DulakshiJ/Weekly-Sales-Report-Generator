# 📊 Weekly Sales Report Generator (AI-Enhanced)

This project automates the creation of insightful, executive-level PDF reports based on weekly sales data. Designed for business analysts, sales managers, and founders, it uses **Python**, **pandas**, **matplotlib**, **FPDF**, and **Gemini API** to extract, visualize, and summarize key trends.

---

## 🚀 Features

- 📁 Upload sales data (CSV or Excel) via Google Colab
- 📆 Filter by Year, Month, and Week
- 🧮 Analyze:
  - Sales Executive performance
  - Top Customers & Retention Insights
  - Cash vs Credit trends and overdue payments
  - Top Products, Inventory Movement & Category Profitability
- 📊 Visual charts (matplotlib)
- 🤖 AI-Generated Insights via Gemini (per section)
- 📄 Generates clean, structured PDF report with all sections and visualizations

---

## 🛠 Requirements

- Google Colab (or Jupyter Notebook with internet access)
- Python 3.x
- Required packages:
  - `pandas`
  - `matplotlib`
  - `fpdf`
  - `google.generativeai`
- Gemini API Key from [Google AI Studio](https://aistudio.google.com/app/apikey)

---

## 📎 Required Columns in Dataset

Make sure your sales file (CSV/XLSX) includes these columns:
  - `Date`
  - `Week`
  - `Month`
  - `Year`
  - `Customers`
  - `Sales Executive`
  - `Transaction Type`
  - `Amount`
  - `Quantity`
  - `Item Group`
  - `Due Date`

---

## ✅ How to Use (Google Colab)

1. Open the Colab notebook.
2. Upload your sales file (CSV or Excel).
3. Select **Year**, **Month**, and **Week** to analyze.
4. Click **Generate Report**.
5. The notebook creates a structured PDF and auto-downloads it.

---

