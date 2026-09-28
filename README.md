# Decoding Starbucks: An Exploratory Analysis of Calories, Sugars, and Nutritional Metrics

A comprehensive data analysis and business intelligence project examining the nutritional profile of Starbucks beverages, developed during the Data Analyst Internship at **ShadowFox**.

---

## 📌 Project Overview
This project explores the Starbucks beverage menu dataset (`starbucks_drinkMenu_expanded.xlsx`) to uncover key insights regarding calories, sugar content, total fat, and caffeine levels across diverse drink categories. By combining Python-powered exploratory data analysis (EDA) with a dynamic, interactive Power BI dashboard, the project highlights high-energy menu items, nutritional correlations, and actionable menu optimization strategies for health-conscious consumers.

---

## 🚀 Key Features & Execution Workflow
The project follows a structured 5-stage workflow:
1. **Data Exploration & Setup (Task 1):** Ingestion, schema validation, and integrity profiling of the dataset.
2. **Statistical Modeling (Task 2):** Utilization of Python (`pandas`) to compute descriptive statistics (mean, median, min, max, percentiles) and isolate high-calorie outliers.
3. **Dashboard UI/UX Design (Task 3):** Designing a professional Power BI interface using a Starbucks Dark Green theme, custom canvas formatting, and structured layout panels.
4. **Visual Analytics & Interactivity (Task 4):** Implementation of clustered bar charts, scatter plots, funnel charts, KPI summary cards, and multi-level category slicers for real-time cross-filtering.
5. **Business Insights & Reporting (Task 5):** Translating technical findings into strategic recommendations for menu transparency and health-centric consumer alternatives.

---

## 📊 Key Findings & Insights
* **Overall Metrics:** The average calorie count across the menu is **193.87**, ranging from **0 to 510 calories**.
* **High-Calorie Drivers:** Specialty categories such as *Smoothies*, *Frappuccino® Blended Coffee*, and *Signature Espresso Drinks* represent the primary high-calorie and high-sugar outliers on the menu.
* **Nutritional Correlation:** Demonstrated a clear positive correlation between sugar/fat content and total caloric load, with heavy specialty drinks clustering at the upper limits.
* **Healthy Alternatives:** Isolated low-calorie/low-sugar baseline options (such as plain brewed coffees and teas) to support transparent, health-conscious consumer choices.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x[cite: 2]
* **Data Processing & EDA:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Business Intelligence & Dashboards:** Power BI
* **Dataset Source:** Microsoft Excel (`starbucks_drinkMenu_expanded.xlsx`)

---

## 📂 Repository Structure
```text
├── starbucks_drinkMenu_expanded.xlsx   # Source dataset file
├── analysis_script.py                  # Python script for EDA & statistical modeling
├── dashboard.pbix                      # Interactive Power BI dashboard file
├── outputs/                            # Generated charts and visualization exports
└── README.md                           # Project documentation
