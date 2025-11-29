# A-B-Testing
This project analyses the effectiveness of three different marketing promotions used by a fast-food chain to launch a new menu item. The goal is to identify which promotion generates the highest sales and whether the differences are statistically significant.

ABOUT DATASET:-
The dataset contains 548 records collected across 137 store locations over four weeks.
It includes details such as
Store age
Market size (small, medium, large)
Promotion type (1, 2, 3)
Weekly sales (in thousands of dollars)

PROCESS:-
Performed data exploration and visualisation of promotions and market sizes
Studied store age distribution and checked for well-controlled experimental groups
Calculated the average, standard deviation and count of sales for each promotion
Performed independent t-tests to compare promotions
Interpreted t-values and p-values to determine statistical significance

FINDINGS
The three promotion groups have similar store age distributions, meaning the experiment is fair and controlled.
Promotion 1 consistently generated higher average sales than Promotion 2.
A t-test comparing Promotion 1 vs Promotion 2 resulted in a very low p-value (≈ 0) → this means Promotion 1 significantly outperformed Promotion 2.
Comparing Promotion 1 vs Promotion 3 gave a p-value ≈ 0.121, which is higher than 0.05 → meaning the difference between Promotion 1 and Promotion 3 is not statistically significant.

Conclusion
Promotion 1 is statistically better than Promotion 2, but not significantly different from Promotion 3.
Based on these results, the company should choose Promotion 1 if they want the most reliable sales lift for the new product.
