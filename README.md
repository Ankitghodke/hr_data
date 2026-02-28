# 👥 HR Employee Attrition Analysis
### Python | Pandas | Seaborn | Plotly | EDA | Google Colab

---

## 📌 Project Overview

A Python-based exploratory data analysis project analyzing **1,200 employee records across 5 departments** to uncover attrition patterns, salary behavior, and workforce trends — identifying key factors that influence employee exits and supporting data-driven HR decision making.

**Tech Stack:**
- **Python** (Pandas, NumPy) — Data Cleaning, Preprocessing
- **Seaborn & Matplotlib** — Statistical Visualizations
- **Plotly Express** — Interactive Charts
- **Google Colab** — Cloud Development Environment

---

## 🏗️ Project Architecture

```
Raw Dataset (1,200 records | 9 features)
        ↓
Python (Data Cleaning + Outlier Handling)
        ↓
EDA (Attrition + Department + Satisfaction Analysis)
        ↓
Visualizations (Bar Charts, Pie Charts, Box Plots)
        ↓
Business Insights & HR Recommendations
```

---

## 📊 Dataset Overview

| Metric | Value |
|--------|-------|
| Total Employees | 1,200 |
| Employees Who Left | 241 (20.1%) |
| Employees Who Stayed | 959 (79.9%) |
| Avg Monthly Salary | ₹67,003 |
| Avg Tenure | 13 years |
| Max Tenure | 40 years |
| Total Features | 9 |
| Departments | 5 (Sales, IT, Finance, HR, Operations) |
| Performance Levels | 4 (Low, Medium, High, Very High) |
| Work-Life Balance Categories | 4 (Poor, Average, Good, Excellent) |

---

## 🧠 Analysis Performed

### 🔹 Data Cleaning & Preprocessing
- Handled missing values using **median imputation** for Age and **mode imputation** for categorical columns
- Detected and treated outliers in Age and Years_at_Company using **IQR method** (Seaborn Boxplot)
- Standardized categorical columns — Department, Job Satisfaction, Work-Life Balance
- Created **Salary Band** feature using pd.qcut() — Low, Medium, High, Very High

### 🔹 Exploratory Data Analysis
- Department-wise attrition rate comparison across 5 departments
- Job Satisfaction level vs attrition count analysis
- Salary distribution comparison — employees who left vs stayed
- Work-Life Balance category vs attrition breakdown
- Performance Rating distribution across 1,200 employees

### 🔹 Visualizations Used
- **Pie Chart** — Overall attrition rate (20.1% vs 79.9%)
- **Bar Chart** — Department-wise avg monthly salary
- **Bar Chart** — Department-wise attrition count
- **Bar Chart** — Job Satisfaction level vs attrition
- **Box Plot** — Age outlier detection
- **Box Plot** — Years at Company outlier detection

---

## 🔍 Department-wise Attrition

| Department | Employees | Left | Attrition Rate |
|------------|-----------|------|----------------|
| Finance | 183 | 41 | 22.4% — Highest |
| Sales | 309 | 65 | 21.0% |
| IT | 372 | 76 | 20.4% |
| HR | 151 | 26 | 17.2% |
| Operations | 117 | 17 | 14.5% — Lowest |

---

## 📈 Key Business Insights

| Finding | Metric | Insight |
|---------|--------|---------|
| Overall Attrition | 241/1,200 (20.1%) | 1 in 5 employees leaving |
| Highest Risk Dept | Finance — 22.4% | Needs immediate HR intervention |
| Salary Paradox | Left: ₹67,703 vs Stayed: ₹66,828 | Salary alone doesn't prevent attrition |
| WLB Surprise | Good WLB — 23.2% attrition | Hidden dissatisfaction factors exist |
| Low WLB Retention | Poor WLB — only 16.7% attrition | Unexpected retention pattern |
| Avg Tenure | 13 years | Strong long-term employee base |
| Performance Balance | High (301) \| Very High (303) \| Medium (309) \| Low (287) | No single tier dominates attrition |

---

## 📂 File Structure

```
📁 HR-Employee-Attrition-Analysis
├── hrdata.ipynb                          # Python EDA notebook
├── HR_Employee_Attrition_Dataset.csv     # Raw dataset
└── README.md                             # Project documentation
```

---

## 🚀 How to Use

1. Open **hrdata.ipynb** in Google Colab or Jupyter Notebook
2. Upload **HR_Employee_Attrition_Dataset.csv** to your environment
3. Run all cells sequentially — data cleaning → EDA → visualizations
4. All charts are interactive (Plotly) and statistical (Seaborn/Matplotlib)

---

## 🎯 Conclusion

This project analyzes **1,200 employee records** to uncover that:
- 👔 **Finance department leads attrition at 22.4%** — highest risk across all 5 departments
- 💰 **Salary paradox confirmed** — employees who left earned ₹875 more on avg than those who stayed
- ⚖️ **Good work-life balance shows highest attrition (23.2%)** — suggesting deeper dissatisfaction factors
- 📊 **20.1% overall attrition rate** — 241 employees left out of 1,200
- 🏢 **Operations is the most stable department** at only 14.5% attrition

These insights directly support HR teams in building **targeted retention strategies** across high-risk departments.

