# 🌍 Country Risk Analysis & Segmentation

## 📌 Project Overview

This project performs an **end-to-end data analysis pipeline** to identify and classify countries based on socio-economic and health indicators.

The workflow integrates:

* **Python (Data Cleaning & Processing)**
* **SQL (Data Extraction)**
* **Power BI (Dashboard & Visualization)**

The final outcome is an **interactive dashboard** that highlights high-risk countries and supports data-driven decision-making.

---

## 🎯 Objectives

* Identify **high-risk countries** based on socio-economic indicators
* Analyze relationships between **income, health, and mortality**
* Classify countries into **meaningful segments**
* Build a **clear and interactive dashboard** for insights

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* SQL (MySQL with mysql-connector-python)
* Power BI
* Jupyter Notebook

---

## 📂 Project Structure

```
global-development-risk/
│
├── data/raw/
│     └── country_data.csv
│── data/  processed/
│       └── country_clean.csv
├── notebooks/
│   └── analysis.ipynb
|
├── powerbi/
│   └── dashboard.pbix
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🔄 Data Pipeline

1. Data extracted from MySQL using SQL queries
2. Loaded into Python using `mysql-connector-python`
3. Cleaned and transformed using Pandas
4. Exported as `country_clean.csv`
5. Visualized in Power BI dashboard

---

## 📊 Key Features

* Country segmentation based on risk levels
* KPI cards for quick insights
* Scatter plots (Income vs Life Expectancy)
* Health & mortality analysis
* Interactive filtering and drill-down

---

## 📈 Sample KPIs

* Total Countries
* High Risk Countries
* Average Income
* Life Expectancy
* Child Mortality Rate

---

## ⚙️ Setup Instructions

### 1. Clone repository

```
git clone <https://github.com/s-niharika09/country-segmentation-analysis>
cd project
```

### 2. Create virtual environment (recommended)

```
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run data processing

```
python src/data_processing.py
```

### 5. Open dashboard

* Open `dashboard.pbix` in Power BI
* Ensure it connects to `country_clean.csv`

---

## 🧠 Key Insight

The project demonstrates how combining **economic and health indicators** can effectively identify vulnerable countries, enabling **better prioritization for policy and aid decisions**.

---

## 📌 Note

Power BI does not require dependency management;
`requirements.txt` is included for the **Python-based data processing components**.

---

## 🚀 Future Improvements

* Add machine learning for advanced segmentation
* Automate data pipeline
* Deploy dashboard online

---

## 👤 Author

[Sakiley Niharika]
