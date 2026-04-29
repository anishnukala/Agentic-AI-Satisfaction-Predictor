# 🤖 Agentic AI Satisfaction Predictor

## 📌 Project Overview

This project analyzes customer support ticket data to predict customer satisfaction levels.

### Main question:  
Can customer satisfaction (Low, Medium, High) be predicted using service-related features?

### Goal:  
Identify which factors influence customer satisfaction and explore patterns in the data.

This submission includes work up to Stage 3 (Exploration). No modeling yet.

---

## 📊 Dataset

Source: Kaggle – Customer Support Ticket Satisfaction Analysis  

- Rows: 2,800  
- Columns: 10  
- Format: CSV  

Target variable:  
- `customer_satisfaction` → Low, Medium, High  

---

## 🧾 Features Used

- issue_category  
- priority  
- first_response_minutes  
- resolution_time_hours  
- agent_experience_years  
- reopened  
- channel  

---

## ⚙️ Data Preparation

- Loaded dataset using pandas  
- Checked:
  - column names  
  - data types  
  - summary statistics  
  - missing values  
  - duplicates  

## 🧹 Cleaning

- Removed duplicate rows  
- Confirmed 0 missing values  

---

## 📈 Key Observations

- Dataset has no missing values  
- Target variable is highly imbalanced  
  - Low: 2061  
  - Medium: 645  
  - High: 94  

- Low satisfaction dominates across:
  - priority levels  
  - issue categories  
  - support channels  

- Important features for future modeling:
  - response time  
  - resolution time  
  - agent experience  
  - reopened status  

---

## ⚠️ Limitations

- Dataset is synthetic  
- Strong class imbalance  
- Patterns may not fully generalize to real-world data  

---

## 🚀 How to Run

1. Download the Jupyter Notebook file from this repository.

2. Open it using:
   - Google Colab (recommended) or Jupyter Notebook locally  

3. Run all cells to reproduce the analysis.

Note:  
The dataset is loaded directly from GitHub, so no manual file upload is required.
