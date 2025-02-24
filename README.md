# Coupon Acceptance/Rejection Feature Analysis

This repository presents an analysis of features influencing coupon acceptance. 
The analysis compares features for customers who accepted a coupon (Y=1) versus those who did not (Y=0) and provides insights on feature importance and actionable recommendations.

Summary of Findings
- **Problem Statement:** Determine which features significantly impact coupon acceptance and provide actionable recommendations for targeted promotions.
- **Key Observations:** Age and Travel Distance have stronger correlation to coupon acceptance than other features like Temp.
  - **Age** shows the strongest positive correlation with coupon acceptance.
  - **toCoupon_GEQ15min** and **toCoupon_GEQ25min** are also strongly associated with coupon acceptance.
  - Conversely, features such as **temperature** and **toCoupon_GEQ5min** are more associated with coupon rejection.

- ## Actionable Recommendations:
  - Targeting Strategy: Based on the analysis, target by demographics age and consider adjustments in coupon delivery timing for temperature variations.
  - Deep Dive Analysis: Conduct additional analyses to validate the findings using inferential statistics.
  - Feature Engineering: Experiment with AWS DataBrew additional transformations 
  - Campaign Testing: Implement A/B tests using the insights to optimize future coupon campaigns and marketing strategies.

## Jupyter Notebook
For a detailed analysis and reproducible code, please refer to the [Coupon Acceptance Analysis Notebook](./UCB_5_1_Coupon_Study_EmilianoGaytan.ipynb).

## Project Organization
- **Data:** Contains the `coupons.csv` dataset.
- **Notebook:** `UCB_5_1_Coupon_Study_EmilianoGaytan.ipynb` with step-by-step analysis.
- **Images:** Visualizations are stored in directory.
- **Naming:** Self Documenting and sequentially organized by prefix number

## How to Run
1. git clone repo
2. Open  Notebook (`UCB_5_1_Coupon_Study_EmilianoGaytan.ipynb`) in your preferred environment (Jupyter Notebook, Jupyter Lab, or Google Colab).
3. Run the cells to reproduce.

## License
This project is licensed under the MIT License.
