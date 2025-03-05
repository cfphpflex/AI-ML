# Coupon Acceptance/Rejection Feature Analysis

This repository presents an analysis of features influencing coupon acceptance. 
The analysis compares features for customers who accepted a coupon (Y=1) versus those who did not (Y=0) and provides insights on feature importance and actionable recommendations.

Disclaimer: 
The dataset is limited but drives home the point.
With a larger dataset, savings & discount value, relevance & personalization, and expiration date & urgency would likely have a much greater impact on coupon campaign success.

Summary of Findings
- **Problem Statement:** Determine which features significantly impact coupon acceptance and provide actionable recommendations for targeted promotions.
- **Key Observations:**  Travel Distance, dining preference have stronger correlation to coupon acceptance than other features like direction, temperature.
  - The most critical factors for coupon acceptance are distance to the coupon location and dining preferences, while demographics play a secondary role. 
  - Travel direction and time are insignificant factors in the decision-making process
  - Conversely, features such as **time,direction_opposite, direction_same, carryaway**   are more associated with coupon rejection.


- ## Actionable Recommendations:
  - Targeting Strategy: Based on the analysis, target by demographics shor distance, lower age to restauratn and type of restaurant
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

