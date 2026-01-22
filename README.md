# Conagra-Brand
Project Title: Create data-driven strategies to help Conagra unlock future growth potential in the Meat Substitutes category
📊 Optimizing Sales Strategy: Meat Substitute Product Analysis
Retail Sales Analytics | Predictive Modeling | Data Mining

This project analyzes sales performance and promotional effectiveness for meat substitute products using real-world retail data.
The goal is to understand how discount strategies and merchandising presence influence sales outcomes and to provide data-driven recommendations for optimizing marketing and inventory decisions.



🔍 Project Overview

Consumer demand for plant-based and meat substitute products has grown rapidly, driven by sustainability concerns and changing dietary preferences.
This project evaluates sales dynamics across multiple product categories to determine:

Whether discounts impact high- and low-performing products differently

Whether merchandise presence vs. no merchandise affects sales volume

How correlations between sales metrics inform merchandising decisions

The analysis leverages predictive modeling, regression techniques, and correlation analysis.

🎯 Objectives

The primary objectives of this project are to:

Analyze the impact of discounts on sales performance

Evaluate merchandise vs. non-merchandise sales behavior

Identify overfitting and model stability issues

Provide actionable business recommendations based on analytical findings

📊 Data Description

The dataset consists of retail point-of-sale (POS) data across multiple frozen and refrigerated food categories, including:

Meat substitutes

Poultry

Seafood

Processed meats

Breakfast and dinner meat products

Time Period: 2020 – 2024
Source: Enterprise retail sales data

Each dataset includes variables related to:

Unit sales

Dollar sales

Volume sales

Discount presence

Merchandise vs. no-merchandise conditions

🧹 Data Preparation

The data preparation process included:

Data consolidation across multiple product categories

Cleaning and standardization of sales metrics

Feature selection for predictive modeling

Correlation analysis to identify multicollinearity

🧠 Analytical Approach
Predictive Analysis 1

Question:
Does discounting impact sales differently for high-performing vs. low-performing products?

Methods Used:

Linear regression

Hypothesis testing

Correlation analysis

Predictive Analysis 2

Question:
Does merchandise presence vs. no merchandise significantly impact sales volume?

Methods Used:

Ridge Regression

Model performance evaluation (MSE, R², Adjusted R²)

📈 Model Evaluation & Findings

Initial Ridge Regression showed very high R², indicating overfitting

Attempts to reduce overfitting by removing highly correlated variables (>0.7) led to:

Significant model performance degradation

Lower predictive accuracy

Key Correlations Identified:

Unit Sales (No Merch) vs. Volume Sales (No Merch): Strong positive correlation (0.97)

Dollar Sales (Any Merch) vs. Dollar Sales (No Merch): Weak negative correlation (-0.2)

These results highlight complex and non-linear relationships between merchandising and sales performance.

💡 Key Insights

Discounts tend to benefit lower-performing products more than bestsellers

Aggressive discounting on high-performing products may reduce profitability

Merchandise presence alone does not guarantee higher sales

Overfitting is a critical risk in retail predictive models with highly correlated variables

✅ Recommendations

Refine Discount Strategy:
Use targeted discounts rather than blanket promotions, especially for top-selling products.

Merchandise Optimization:
Focus merchandising efforts on high-margin items instead of relying on merchandise to boost volume universally.

Inventory Management:
Avoid overstocking low-performing merchandise by aligning inventory with demand patterns.

Customer Experience Focus:
Enhance in-store experience through better product placement, staff training, and store layout.

Continuous Data Monitoring:
Apply ongoing model validation and market research to adapt strategies dynamically.

🛠 Tools & Techniques

Predictive Modeling (Linear & Ridge Regression)

Correlation & Feature Analysis

Sales & Retail Analytics

Data Mining Techniques

Statistical Evaluation Metrics

🚀 Why This Project Matters

This project demonstrates how data mining and predictive analytics can be applied to real-world retail challenges, enabling organizations to:

Optimize pricing and promotional strategies

Improve merchandising effectiveness

Reduce financial risk from over-discounting

Make informed, data-driven business decisions
