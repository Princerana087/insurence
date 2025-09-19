# insurence
📊 Insurance Data Analysis – Colab Notebook
📌 Overview

This project explores an insurance dataset using Python (Pandas & Seaborn) in Google Colab.
It covers data cleaning, exploration, and visualization to understand customer attributes and their insurance premium categories.

🗂️ Dataset

Rows: 100

Columns: 8

Features:

👤 age

⚖️ weight

📏 height

💰 income_lpa

🚬 smoker (True/False)

🏙️ city

💼 occupation

🏷️ insurance_premium_category (Low / Medium / High)

🔧 Tools & Libraries

🐼 Pandas → Data handling

🎨 Seaborn → Visualizations (distribution plots, count plots, boxplots)

📈 Analysis Performed

✅ Data loading & inspection (head(), tail(), info(), describe())

✅ Missing values & unique values check

✅ Summary statistics (mean, min, max, std)

✅ Value counts for age distribution

📊 Visualizations:

Distribution plots (distplot for age, weight)

Count plots (age, weight, city, income_lpa)

Boxplots (age, weight, city, income, height, age vs weight)

⚠️ Notes

sns.distplot is deprecated in Seaborn v0.14+. Use histplot or displot instead.

Dataset is balanced with no missing values.

🚀 Next Steps

🔍 Explore correlations (e.g., income vs premium category)

🧠 Apply ML models for premium prediction

📊 Create dashboards for interactive analysis
