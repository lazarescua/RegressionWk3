# RegressionWk3
Regression models course, week 3, Optional quiz

## Synopsis

We will study how income varies across college major categories. Specifically answer: “Is there an association between college major category and income?” 

## Method

By looking at the data we can see the sample size for computing the income medians is rather small. So we take two approaches: 
  1. Check if the Major Category has any impact on the income median
  2. Check if the Major Category has any impact on the percentage of employed persons (because the sample size is very small for income calculation)
 We fit a linear regression model to see the impact on income based on the Major Category (treated as factor) but the results show that there is no link between the income (either the median or the percentage of employed persons) and the Major Category. The p-values are considerably higher than the 0.05. We could try to test all combinations but we would just test for p-hacking in this case :) 
