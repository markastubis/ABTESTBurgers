# Fast-Food Chain Marketing Campaign Analysis
I took a dataset from a marketing campain, where a firm ran 3 different promotions and A/B tested which of the promotions were the most efficient 

# Project Overview
A fast-food chain plans to add a new item to its menu and is undecided between three possible marketing campaigns to promote the new product. To determine which campaign has the greatest effect on sales, the new item is introduced at various locations, each using a different promotion. This project analyzes the sales data from these campaigns to identify the most effective promotion strategy.

# Dataset
The dataset contains the following columns:

MarketID: Unique identifier for the market
MarketSize: Size of the market area by sales
LocationID: Unique identifier for the store location
AgeOfStore: Age of the store in years
Promotion: One of three promotions tested
week: One of four weeks during which the promotions were run
SalesInThousands: Sales amount in thousands for a specific LocationID, Promotion, and week

# Project Goals
Perform Exploratory Data Analysis (EDA) to understand the dataset.
Test the assumptions for ANOVA and perform an appropriate statistical test to compare promotions.
Conduct pairwise comparisons to identify significant differences between promotions.
Calculate effect sizes to understand the scale of differences.
Evaluate the impact of market size on sales.
Use bootstrap methods to calculate confidence intervals for median sales.
Identify the best promotion based on statistical analysis.

# Conclusion (key question)
Based on the statistical analysis, Promotion 1 is the most effective in terms of median sales and overall performance. Promotion 2 consistently underperforms across various metrics. Promotion 3 shows higher variability and performs well in large markets but does not significantly outperform Promotion 1.

# Recommendation: The fast-food chain should adopt Promotion 1 as it demonstrates the highest and most consistent sales performance.
