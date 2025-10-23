# E-Commerice-Sales-Analysis
> An end-to-end data analytics project analyzing e-commerce sales, discounts, and purchase efficiency to uncover business insights and actionable strategies.

---

## Tableau Dashboard
Explore the interactive dashboard here: [Business Portfolio Tableau Dashboard](https://public.tableau.com/app/profile/galen.pike/viz/BusinessProjectPortfolio/Dashboard1#1)

---

## Dataset
- **Source:** 42k+ transactions dataset from Kaggle  
- **Link:** [Amazon Products Sales Dataset](https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025)  
- **Instructions:** Download the CSV and place it in the `data/` folder before running the analysis.

---

## Project Overview
This project analyzes e-commerce sales data to derive insights about pricing, discounts, popularity, and purchase efficiency. Using Python (Pandas, Seaborn, Matplotlib), the workflow covers **data cleaning, metric derivation, EDA, predictive modeling, and visualization**.

Key business questions addressed:
- Which products drive the most purchases relative to reviews?  
- How do discounts impact sales?  
- Which price brackets dominate revenue and purchase efficiency?  
- How can product popularity and high-value items inform targeted marketing?

---

## Objectives
- Clean and standardize raw e-commerce data.  
- Derive metrics like purchase efficiency, discount effectiveness, and price brackets.  
- Conduct exploratory data analysis to uncover trends, outliers, and anomalies.  
- Build predictive models (Linear Regression & Random Forest) to understand sales drivers.  
- Generate actionable business insights for pricing, marketing, and discount strategy.

---

## Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  
- **Tools:** Jupyter Notebook, VS Code  
- **Workflow:** Automated ETL (Extract → Transform → Clean → Aggregate → Analyze)  
- **Visualization:** Seaborn, Matplotlib, Tableau

---

## File Structure
Business-Portfolio-Project
│
├── data/
│ ├── raw/ # Original e-commerce CSV files (from Kaggle)
│ ├── processed/ # Cleaned & aggregated datasets
│ └── final_dataset.csv # Aggregated, derived dataset ready for analysis
│
├── notebooks/
│ ├── data_cleaning.ipynb # Full cleaning and transformation workflow
│ ├── metrics_eda.ipynb # Metric calculation, EDA, and visualization
│ ├── modeling.ipynb # Predictive modeling and feature importance analysis
│
├── scripts/
│ └── cleaning_functions.py # Reusable Python functions for cleaning & aggregation
│
├── visuals/ # Plots, histograms, and model visualizations
│
└── README.md # Project documentation and insights


---

## Key Python Concepts Demonstrated
- Data cleaning, transformation, and aggregation  
- Feature engineering for derived business metrics  
- Skewed data handling and log-scale visualization  
- Grouping and segment analysis  
- Predictive modeling with Linear Regression & Random Forest  
- Feature importance interpretation and actionable insight derivation  

---

## Next Steps / Future Work
- Integrate Tableau dashboards for interactive visualization  
- Include time-based sales trends if temporal data is available  
- Automate ETL for live e-commerce datasets  
- Expand modeling to include promotions, seasonal effects, and customer segmentation

Tableau Link: https://public.tableau.com/app/profile/galen.pike/viz/BusinessProjectPortfolio/Dashboard1#1

**Dataset:** The dataset used in this project (42k+ transactions) is available on [Kaggle] https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025 Download it and place it in the `data/` folder before running the analysis.
