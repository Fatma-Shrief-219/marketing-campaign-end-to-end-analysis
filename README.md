# 📊 Marketing Campaign Analysis: End-to-End Data Analytics Project

An end-to-end analysis of 2,236 customers to understand **who responds to marketing campaigns and why**, built as the final project of my Data Analysis training at **Orange Digital Center (ODC)**.

## 🎯 Business Problem
Marketing teams have limited budgets and can't target everyone. Which customers are most likely to accept a new campaign, and what characteristics drive that response?

## 🛠️ Tools & Workflow
| Stage | Tool | What I did |
|---|---|---|
| Cleaning & EDA | **Python** (Pandas, Matplotlib, Seaborn) | Handled missing values, outliers, invalid birth years, inconsistent categories, and fixed data types |
| Exploration | **Excel** | Sanity checks and initial exploration |
| Dashboard | **Power BI** | 4-page interactive dashboard with DAX measures |
| Storytelling | **PowerPoint** | Business-oriented presentation of findings |

## 🧹 Data Cleaning Highlights
- 2,240 → 2,236 rows, 29 → 27 columns
- Handled 24 missing Income values
- Removed impossible birth years (1893, 1899, 1900) and an extreme income outlier (666,666)
- Standardized Marital_Status categories ("Alone", "Absurd", "YOLO")
- Converted `Dt_Customer` to a proper date type
- Dropped 2 constant columns
- Engineered features: Age, Total Spending, Total Children, Tenure

## 📈 Key Insights
- 🍷 **Wine ≈ 50%** of total spending, followed by meat (~27%)
- 🎓 **PhD holders** respond to campaigns ~5x more than customers with basic education
- 💸 **Widowed customers** have the highest average spend despite being the smallest segment
- 🏬 **Store** is the strongest purchase channel
- 📣 **Campaign 4** performed best, **Campaign 2** performed far below the rest
- Overall response rate: **14.94%**

## 🖥️ Dashboard Pages
1. **Overview**: KPIs, response rate vs target, response by education
2. **Customer Demographics**: age, education, children, income
3. **Spending by Product Category**: spend breakdown and income vs spending
4. **Purchase Channels & Campaign Performance**: channel mix and past campaign acceptance

## 📁 Repository Files
- `Marketing_Campaign_Analysis.ipynb`: Python cleaning + EDA
- `marketing_campaign_cleaned.csv`: cleaned dataset
- `Final_Orange.pbix`: Power BI dashboard
- `Dashboard_Documentation_Report.pdf`: dashboard design documentation
- `Dataset_Description (1).pdf`: dataset description and business problem

## 📦 Dataset
[Customer Personality Analysis](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign) by Rodrigo Saldanha (Kaggle).

## 👩‍💻 Author
**Fatma Shrief** | [GitHub](https://github.com/Fatma-Shrief-219) | 
