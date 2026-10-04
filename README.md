# Anugrah — Data Analytics Internship Portfolio

Welcome to my **Data Analytics Internship Portfolio**, showcasing my complete project journey during the **ApexPlanet Data Analytics Internship**.

This portfolio demonstrates my progression through the data analytics lifecycle — from data cleaning and exploratory analysis to SQL, dashboarding, statistical validation, business insights, and stakeholder-focused data storytelling.

---

## 👋 About This Portfolio

This repository serves as a central portfolio for my internship work and learning journey.

Across the internship, I worked with a sales dataset and progressively transformed raw data into meaningful, validated, and business-oriented insights.

**Analytics Journey**

Raw Data → Data Cleaning → Exploratory Analysis → SQL → Dashboarding → Segmentation → Statistical Validation → Business Storytelling

---

## 🎯 Internship Overview

Throughout the internship, I worked on:

- Data cleaning and preprocessing
- Data quality validation
- Exploratory Data Analysis
- SQL-based business analysis
- Data visualization
- Sales and customer segmentation
- Interactive dashboard development
- Statistical hypothesis testing
- Business interpretation
- Data storytelling and stakeholder communication

---

# 📂 Project Journey

## Task 1 — Data Cleaning & Preparation

**Objective:** Prepare the raw sales dataset for reliable analysis by identifying and treating data-quality issues, validating important fields, engineering useful features, and producing a clean analytical dataset.

### Key Work

- Inspected dataset structure and data types
- Handled missing values
- Checked for duplicate records
- Validated product and category consistency
- Validated `Total_Sales` against `Quantity × Unit_Price`
- Checked date validity
- Assessed potential outliers using the IQR method
- Created the `Order_Month` feature
- Performed final data validation

### Key Results

- Original dataset: **1,000 rows × 12 columns**
- Cleaned dataset: **1,000 rows × 13 columns**
- 20 missing `Age` values filled using the median
- 13 missing `City` values filled using the mode
- No complete duplicate rows detected
- No invalid order dates detected
- Zero mismatches in `Total_Sales` validation
- 19 potential `Total_Sales` outliers identified and retained

**Tools:** Python • Pandas • NumPy • Excel • CSV • Git & GitHub

🔗 [View Task 1](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship/tree/main/Task-1)

---

## Task 2 — Exploratory Data Analysis, SQL & Dashboard

**Objective:** Explore the cleaned dataset, identify meaningful sales patterns, answer business questions using SQL, analyze relationships between numerical variables, and communicate findings through visualizations and a dashboard.

### Key Work

- Performed descriptive and univariate analysis
- Analyzed product, category, city, monthly, gender, and age-group sales
- Answered business questions using SQL
- Performed correlation analysis
- Created scatter plots, heatmaps, and pair plots
- Developed a static dashboard presentation

### Key Findings

- **Electronics** recorded the highest sales among categories
- **Laptop** recorded the highest sales value among the top products
- **March 2025** recorded the highest monthly sales
- **Patna** recorded the highest city-level sales
- Average `Total_Sales` was approximately **₹1.39 lakh per record**
- `Quantity` and `Unit_Price` showed stronger relationships with `Total_Sales` than `Age`

**Tools:** Python • Pandas • NumPy • Matplotlib • Seaborn • MySQL • Excel • PowerPoint

🔗 [View Task 2](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship/tree/main/Task-2)

---

## Task 3 — Deep-Dive Analysis & Interactive Dashboard

**Objective:** Extend the analysis through deeper sales and customer segmentation and communicate the findings using an interactive dashboard.

### Key Work

- Performed age-group sales segmentation
- Analyzed city-level sales contribution
- Analyzed category-level performance
- Examined key sales KPIs
- Created supporting visualizations
- Built an interactive dashboard using Google Looker Studio
- Added category-level filtering for exploration

### Key Findings

- The **45–65 age group** contributed **41.51%** of observed sales
- The **30–65 age groups combined** contributed **77.58%** of observed sales
- **Patna** had the highest city-level sales contribution at **14.94%**
- **Electronics** remained the leading category at **36.43%**
- Total sales were approximately **₹13.94 crore**

### Interactive Dashboard

🔗 [View Looker Studio Dashboard](https://datastudio.google.com/reporting/87dbed6e-5b07-482f-a205-7854e8954b54)

**Tools:** Python • Pandas • Google Looker Studio

🔗 [View Task 3](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship/tree/main/Task-3)

---

## Task 4 — Data Storytelling & Statistical Validation

**Objective:** Bring together the analytical findings into a clear business narrative and statistically validate an observed difference in average sales between male and female sales records.

### Key Work

- Consolidated findings from the previous analytical tasks
- Created a stakeholder-focused presentation
- Formulated a testable business hypothesis
- Performed an independent two-sample Welch's t-test
- Used a significance level of **α = 0.05**
- Calculated a **95% confidence interval**
- Evaluated effect size using **Cohen's d**
- Translated findings into business recommendations

### Statistical Finding

| Measure | Result |
|---|---:|
| Female records | 489 |
| Female mean sales | ₹1,36,883 |
| Male records | 511 |
| Male mean sales | ₹1,41,807 |
| Observed difference | ₹4,924 |
| p-value | 0.4950 |
| 95% CI | −₹19,080 to ₹9,232 |
| Cohen's d | −0.043 |

Since the p-value was greater than **0.05**, the analysis **failed to reject the null hypothesis**.

The dataset did not provide sufficient statistical evidence of a significant difference in average sales between male and female sales records.

### Business Interpretation

> **Visible differences in data should not automatically be treated as validated business drivers.**

Based on this analysis, gender alone should not be treated as a statistically validated differentiator of average sales performance in this dataset.

**Tools:** Python • SQL • Google Looker Studio • PowerPoint

🔗 [View Task 4](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship/tree/main/Task-4)

---

# 🛠️ Tools & Technologies

| Area | Tools |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Database / SQL | MySQL |
| Dashboarding | Google Looker Studio |
| Presentation | Microsoft PowerPoint |
| Data Sources | Excel, CSV |
| Statistical Analysis | SciPy |
| Version Control | Git & GitHub |

---

# 📊 Key Skills Demonstrated

- Data Cleaning & Preprocessing
- Data Quality Validation
- Exploratory Data Analysis
- Feature Engineering
- SQL Querying
- Statistical Analysis
- Hypothesis Testing
- Correlation Analysis
- Sales & Customer Segmentation
- Dashboard Development
- Data Visualization
- Business Insight Generation
- Data Storytelling
- Stakeholder Communication
- Git & GitHub

---

# 🧠 Key Learnings

### Data Quality Comes First
Reliable insights depend on properly cleaned, validated, and documented data.

### Analysis Should Answer Business Questions
EDA becomes more useful when it is connected to specific business questions.

### Correlation Is Not Causation
Observed relationships can guide further investigation but do not establish cause and effect by themselves.

### Statistical Validation Adds Rigor
Hypothesis testing helps determine whether an observed difference is supported by available evidence.

### Communication Is Part of Analytics
A strong analysis should be understandable to a business audience and connect findings with practical actions.

---

# 🎥 Final Presentation

The final stakeholder presentation brings together the major findings from the internship, including sales performance, product and category patterns, geographic and time trends, age segmentation, statistical validation, business interpretation, and recommended actions.

🔗 [View Task 4 Presentation & Supporting Files](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship/tree/main/Task-4)

---

# 🔗 Complete Internship Repository

🔗 [ApexPlanet Data Analytics Internship Repository](https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship)

### Repository Structure

```
ApexPlanet-Data-Analytics-Internship/
│
├── Data/
├── Task-1/
├── Task-2/
├── Task-3/
└── Task-4/
```
---

# 📫 Connect With Me

**Anugrah Dubey**  
B.Tech Computer Science Engineering

🔗 **GitHub:**  
https://github.com/Anugrah2801

🔗 **Internship Repository:**  
https://github.com/Anugrah2801/ApexPlanet-Data-Analytics-Internship

---

# ⭐ Final Reflection

This internship provided an opportunity to work through the complete data analytics lifecycle — from preparing raw data and exploring patterns to answering business questions, building dashboards, validating findings statistically, and communicating insights to a stakeholder audience.

The experience strengthened both my technical foundation and my understanding of how data can support structured, evidence-based decision-making.

**Insights → Decisions → Measurement → Improvement**
