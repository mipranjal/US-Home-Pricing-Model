# Factors Impacting U.S. Home Prices Over the Last 20 Years 🏡📈

![home](https://github.com/mipranjal/US-Home-Pricing-Model/assets/110101325/0c828624-849b-4333-aa9c-467a30c2258a)

## Introduction 🌐
The analysis explores key factors influencing U.S. home prices over the past two decades, utilizing supply and demand datasets. We delve into the relationship between various economic indicators and the S&P/Case-Shiller U.S. National Home Price Index.

## Data Overview 📊
The datasets include quarterly data on supply factors (e.g., construction spending, housing units authorized) and demand factors (e.g., interest rates, GDP). The S&P/Case-Shiller index serves as the dependent variable.

## Exploratory Data Analysis 🧐
Correlation analyses reveal intriguing insights:
- Positive correlation between housing units authorized (PERMIT) and home prices.
- Strong positive correlation with total construction spending (TLRESCONS), indicating a robust connection to higher home prices.

## Visualization Analysis 📉
Visualizations showcase trends:
- Monthly Supply of New Houses (MSACSR) exhibits a negative correlation, suggesting an increase may lead to a price decrease.
- Total Construction Spending (TLRESCONS) correlates positively, indicating higher spending boosts home prices.

## Model Evaluation 📈
Linear Regression Model Insights:
- MSE on testing set: 33.18
- R-squared score: 97.23%

### Coefficients:
- 'PERMIT': Small positive coefficient (0.0197), weakly linking authorized housing units to higher predicted home prices.
- 'MSACSR': Positive coefficient (8.17), indicating a positive association with predicted home prices.
- 'TLRESCONS': Positive coefficient (5.693), implying a minimal impact on predicted home prices.
- 'EVACANTUSQ176N': Negative coefficient (-0.00133), associating increased vacant housing units with slightly lower predicted home prices.
- 'MORTGAGE30US': Negative coefficient (-14.994), suggesting higher mortgage rates relate to lower predicted home prices.
- 'GDP': Very small negative coefficient (-0.00303), indicating a link between higher GDP and lower predicted home prices.
- 'UMCSENT': Negative coefficient (-0.18699), linking lower consumer sentiment to lower predicted home prices.
- 'INTDSRUSM193N': Positive coefficient (3.97), suggesting higher interest rates relate to higher predicted home prices.
- 'MSPUS': Small positive coefficient (0.000455), indicating a weak positive relationship.

## Interpretation and Insights 🤔
- **Supply Factors:** Housing units and construction spending positively impact home prices.
- **Demand Factors:** Mortgage rates and consumer sentiment show a negative relationship.
- **Economic Factors:** GDP positively influences, reflecting a strong economy.

## Conclusion 🚀
Understanding these factors is crucial for stakeholders. Positive trends in construction spending and housing units authorized indicate potential growth, while economic stability remains pivotal. This analysis equips stakeholders with valuable insights for informed decision-making in the dynamic real estate market. 🏡💡
