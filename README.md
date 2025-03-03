# Coupon Acceptance/Rejection Feature Analysis

This repository presents an analysis of features influencing coupon acceptance. 
The analysis compares features for customers who accepted a coupon (Y=1) versus those who did not (Y=0) and provides insights on feature importance and actionable recommendations.

Summary of Findings
- **Problem Statement:** Determine which features significantly impact coupon acceptance and provide actionable recommendations for targeted promotions.
- **Key Observations:** Age and Travel Distance have stronger correlation to coupon acceptance than other features like Temp.
  - **tocoupon_geq25min, tocoupon_geq15min, restaurant20to50, coffeehouse,  age ** show the strongest positive correlation with coupon acceptance.
  - Others are less so.
  - Conversely, features such as **time,direction_opposite, direction_same, carryaway**   are more associated with coupon rejection.
 


- ## Actionable Recommendations:
  - Targeting Strategy: Based on the analysis, target by demographics distance, age to restauratn and type of restaurant
  - Deep Dive Analysis: Conduct additional analyses to validate the findings using inferential statistics.
  - Feature Engineering: Experiment with AWS DataBrew additional transformations 
  - Campaign Testing: Implement A/B tests using the insights to optimize future coupon campaigns and marketing strategies and confirm distance, age, time are successful targeting strategies

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

