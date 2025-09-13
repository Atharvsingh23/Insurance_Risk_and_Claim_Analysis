# Insurance_Risk_and_Claim_Analysis
📊 Insurance Risk & Claim Analysis — Exploratory Data Analysis (EDA)
📌 Project Overview

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) on an insurance dataset containing over 37,000 policy records. The goal is to understand customer demographics, risk patterns, claim behaviors, and other business-critical insights.
We combine Python-based EDA with visualizations and a Power BI dashboard to provide both granular analysis and an interactive overview.

🏦 What is Insurance Risk & Claim Analysis?

Insurance risk & claim analysis is the process of evaluating how different factors (such as age, gender, car use, education, household income, and claim frequency) impact the overall risk exposure and financial outcomes of an insurance company.

It helps insurers identify high-risk groups.

Provides insights into claim frequency and severity.

Improves pricing models, fraud detection, and customer segmentation.

Enhances business decision-making and profitability.

📂 Dataset

Source: insurance_policies_data.xlsx (Excel dataset provided).

Rows: ~37,500

Columns: 16 (covering demographics, vehicle info, coverage, income, claims, etc.)

Key Fields:

BirthDate (used to calculate policyholder age)

Gender, Marital Status, Education, Parent

Car Make, Car Model, Car Year, Car Use

Coverage Zone (Urban, Rural, Suburban, etc.)

Claim Amount, Claim Freq, Household Income, Kids Driving

🛠 Tools & Libraries Used
Python (EDA & Visualization)

pandas — data handling & cleaning

numpy — numerical computations

matplotlib & seaborn — data visualization (histograms, bar charts, line plots, scatter plots, heatmaps, pie charts)

openpyxl — Excel file reading

Power BI (Dashboard)

Interactive visuals summarizing total claims, policy counts, and distributions by demographics, coverage zones, and car usage.

KPIs like: Total Policies, Total Claim Amount, Avg Claim Frequency, Avg Claim Amount, Male vs Female split

Insurance_Riskand Claim Analysis

📊 Analysis & Visuals
Python EDA Includes:

Missing value heatmap

Univariate analysis: histograms & boxplots for claims, income, car year

Bivariate analysis: claim amount by gender, education, marital status, coverage zone, car use

Correlation heatmap of numeric features

Age group analysis (derived from BirthDate)

Scatter plots: income vs claim amount (by gender)

Trend analysis: claim amount by car year

Power BI Dashboard Highlights:

Total Policies: 37.5K

Total Claim Amount: $187.8M

Average Claim Frequency: 0.5

Top Claim Segments:

Car Use → Private policies dominate

Coverage Zone → Spread across Urban, Suburban, Rural

Education → College graduates contribute highest claim amounts

Kids Driving → Significant impact on claim amount

🚀 Key Insights

Gender: Nearly equal male-female split in claim amounts.

Education: Higher education levels correlate with higher claim amounts.

Coverage Zone: Urban & Highly Urban zones account for the majority of claims.

Car Use: Private use vehicles generate far higher total claims compared to commercial.

Age Groups: Middle-aged groups (30–50) show higher claim activity.

Household Income: Weak correlation with claim amounts, but outliers exist.

📌 Importance of this Analysis

Provides risk assessment for insurers.

Helps in policy pricing & premium optimization.

Detects high-claim customer segments.

Aids in strategic decision-making for underwriting & marketing.

📂 Project Structure
├── insurance_policies_data.xlsx   # Raw dataset
├── Insurance_Riskand Claim Analysis.pdf  # Power BI dashboard
├── notebooks/
│   └── eda_insurance.ipynb        # Python EDA with visualizations
├── eda_outputs/                   # Generated plots & heatmaps
├── README.md                      # Project description

🔮 Future Work

Apply machine learning models for claim prediction & risk scoring.

Build an automated pipeline for data cleaning & visualization.

Extend Power BI with real-time dashboards linked to a database.

📌 Author

👨‍💻 Atharva Singh — 4rd Year BTech (AI & ML), GGSIPU
Passionate about data analysis and  AI/ML applications.
