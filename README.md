# 🏬 Walmart Sales Analysis & Forecasting  
### End-to-End Data Analysis • Machine Learning • Business Insights

## 🔧 Project Summary

**Objective:** Analyze Walmart’s historical weekly sales to identify patterns, trends, and factors affecting store performance.

**Hypotheses:** Weekly sales are influenced by store location, seasonality, and external factors such as temperature, fuel price, CPI, and unemployment.

**Model/Analysis:** Exploratory data analysis using Python, Pandas, Matplotlib, and Seaborn, including distribution, correlation, and trend analysis.

**Key Results:** Top-performing stores were identified, sales show clear seasonal patterns, and external factors like temperature and CPI moderately affect weekly sales.

**Recommendations:** Focus inventory and marketing efforts on high-performing stores and peak weeks, monitor external factors for predictive insights, and consider seasonal patterns for staffing and promotions.


## 📌 Project Overview
This project analyzes weekly retail sales from multiple Walmart stores in the US.  
The goal is to understand the key drivers behind sales variations and build a predictive model to estimate future revenue.

The analysis includes:
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Correlation and feature impact  
- Machine learning model for sales forecasting  
- Business insights & recommendations  

This project demonstrates essential skills for **Data Analyst, Data Scientist, and Business Intelligence roles**.

---

## 📂 Project Structure

```text
Walmart-Sales-Analysis/
│
├── data/                       
│   ├── Walmart_sales.csv
│   └── Walmart_sales_clean.csv
│
├── visualization/                     
│   ├── average_weekly_sales_by_week_of_year.png
│   ├── correlation_matrix.png
│   ├── distribution_of_weekly_sales.png
│   ├── monthly_sales_trend.png
│   ├── random_forest_actual_vs_predicted.png
│   ├── random_forest_freature_importance.png
│   ├── temperature_vs_weekly_sales.png
│   ├── total_weekly_sales_by_store.png
│   └── total_weekly_sales_over_time.png
│
├── scripts/                    
│   └── main_analysis.py
│
├── notebooks/                  
│   └── walmart_analysis.ipynb
│
├── Insights.md
├── README.md                  
└── requirements.txt
```

---

## 📊 Dataset Description
The dataset contains **historical weekly sales** for multiple Walmart departments.  
**Main features include:**

- `Store` : Store ID  
- `Date` : Week of sales  
- `Weekly_Sales` : Total sales for that week  
- `Holiday_Flag` : Holiday week indicator  
- `Temperature` : Regional temperature  
- `Fuel_Price` : Cost of fuel  
- `CPI` : Consumer Price Index  
- `Unemployment` : Regional unemployment rate  

The dataset allows both **time-series and regression analysis**.

---

## 🧼 1. Data Cleaning  
Key steps performed:

- Converted `Date` to datetime format  
- Extracted `Year`, `Month`, and `Week`  
- Checked for missing values (none found)  
- Removed duplicates  
- Verified outliers for sales, CPI, fuel price  
- Normalized column names  
- Prepared clean dataset for modeling  

---

## 🔍 2. Exploratory Data Analysis (EDA)

### ✔ Sales trends over time  
Analyzed weekly revenue to detect seasonality, peaks, and drops.

### ✔ Correlation matrix  
Identified relationships between variables such as CPI, Fuel Price, Temperature, and Sales.

### ✔ Store-level performance  
Compared performance across Walmart stores to detect high- and low-performing locations.

### ✔ Impact of holidays  
Quantified the sales differences between holiday weeks and normal weeks.

📌 *All visualizations are available in the `visualization/` folder.*

---

## 🤖 3. Machine Learning Model

A regression model was trained to predict weekly sales.

### 📐 Model Used
- **Linear Regression**
- (optional) Random Forest Regressor
- (optional) XGBoost Regressor

### 📊 Metrics evaluated:
- R² Score  
- MAE (Mean Absolute Error)  
- RMSE  

The model achieves **solid predictive performance**, demonstrating that external economic factors significantly influence store revenue.

---

## 💡 4. Business Insights

Key insights extracted from the analysis:

- **Holiday weeks systematically show higher sales**, confirming the importance of seasonal promotions.
- **Fuel Price and CPI show moderate correlation with sales**, suggesting sensitivity to economic conditions.
- **Certain stores consistently outperform others**, indicating location-based advantages.
- **Temperature has a seasonal effect** on sales, depending on the region and time of the year.
- **Unemployment impacts purchasing power**, and indirectly affects weekly sales.

These insights can help retail managers optimize marketing, plan inventory, and schedule promotions.

---

## 🧠 Conclusion
This project demonstrates the full data workflow:
- Cleaning  
- Analysis  
- Modeling  
- Interpretation  

It showcases strong analytical and technical skills relevant for **Data Analyst, Data Scientist, and BI roles**.

Future improvements may include:
- Deep learning time-series models (LSTM)  
- Store-specific forecasting  
- Deployment via a dashboard (Power BI or Streamlit)

---
# ▶️ How to Run the Project
## 1️⃣ Installation & Reproducibility

```bash
git clone https://github.com/saad-data-dev/Walmart-Sales-Analysis.git
cd Walmart-Sales-Analysis
pip install -r requirements.txt
```

## 2️⃣ Run the notebook
Open:
notebooks/analysis.ipynb
Then run all cells.
---

## 🧑‍💻 Author

**Saad EL FATINE**  
Data Analyst / Data Scientist  

📩 **Email    :** e.saad@etudiant.edcparis.edu  
🔗 **GitHub   :** https://github.com/saad-data-dev  
🔗 **LinkedIn :** https://www.linkedin.com/in/saad-el-fatine  

---

## 🎉 Final Notes

This project demonstrates:

- **Data Cleaning**
- **Exploratory Data Analysis (EDA)**
- **Business Insights & Interpretation**
- **Feature Engineering**
- **Machine Learning Modeling**
- **Data Visualization**
- **Project Structuring**
- **Professional Documentation**

---



     
