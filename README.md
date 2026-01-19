# Healthcare Insurance Claims Analysis

## Overview
Exploratory data analysis on synthetic insurance claims data to identify factors influencing claim amounts.

## Dataset
- Source: Kaggle (insurance claims data)
- Original rows: 1340
- Columns: age, gender, bmi, bloodpressure, diabetic, children, smoker, region, claim
- Cleaning steps: Filled missing age (median) and region (mode), standardized categories (lowercase/strip), converted age to int.

## Key Insights
- Smokers pay ~280.6% more on average ($32,050 vs $8,421 for non-smokers)
- Average claim by gender: Male $13,920, Female $12,570
- Average claim by region: Northeast highest (~$16,889), Northwest lowest (~$11,672)
- BMI similar across diabetic status (~30.4–30.9)

## Visualizations (saved as PNGs)
- avg_claim_by_smoker.png: Bar chart of average claim by smoker
- claim_distribution.png: Histogram of claim amounts
- bmi_vs_claim.png: Scatter plot of BMI vs claim, colored by smoker

## Tools Used
- Python, Pandas (cleaning/EDA)
- Matplotlib & Seaborn (visualization)
- Jupyter Notebook in VS Code

## Next Steps
- Potential for predictive modeling (e.g., regression on claim amount)
- Deploy as interactive dashboard (Power BI / Fabric)

Built as part of portfolio for data analyst / data engineer roles.
