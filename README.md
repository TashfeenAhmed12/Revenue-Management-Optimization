# Revenue-Management-Optimization
This repository contains a project on optimizing revenue management strategies through various pricing models. It includes data collection, methodology, and results analysis using human intuition, linear optimization, and non-linear optimization approaches

# Revenue Management Optimization

# Objective
- The primary goal of this project is to develop, implement, and compare various pricing strategies to maximize revenue and minimize inventory costs for a retail product over a 15-week selling period.

# Data Collection and Description
- **Data Source:** Simulated retail environment.
- **Tools Used:** Selenium WebDriver for automated web scraping.
- **Data Points Collected:**
  - Week Number
  - Price
  - Sales
  - Remaining Inventory
  - Total Revenue and Optimal Revenue

# Methodology
### 1. Human Intuition Matrix Method
- Utilizes managers' intuition to decide prices for each week.
- Adaptable but may suffer from subjectivity, leading to inconsistent pricing unless carefully controlled.

### 2. Linear Optimization (Linear Demand Variation)
- Overview:
This method uses a linear programming model to determine the best pricing strategy over a 15-week period, based on the assumption that there is a straightforward relationship between price and market demand.
- Assumption:
The model assumes that consumer demand changes in a predictable, linear way when prices are adjusted. This makes it easier to create a systematic pricing strategy.
- Regression Analysis:
To understand how price affects sales, we performed a regression analysis on historical sales data.
This analysis provided insights into how different factors like price and time (week number) influence sales, giving us specific values (coefficients) that describe these relationships.
- Optimization Algorithm:
We developed an optimization algorithm using the insights gained from the regression analysis.
- Objective: The main goal of the algorithm is to maximize total revenue by setting the best prices each week based on predicted sales and available inventory.
- Function: Each week, the algorithm sets a price that is expected to generate the most revenue without exceeding the available inventory.

# Results
- **Random Strategy (200 runs):**
  - Mean difference of 16.27% from perfect foresight.
  - High variability due to lack of systematic approach.
- **Simple Linear Optimization (50 runs):**
  - Mean difference of 8.05% from perfect foresight.
  - More consistent and reliable due to systematic, data-driven pricing.
- **Human Intuition (3 runs):**
  - Mean difference of 4.28% from perfect foresight.
  - Relies heavily on experienced managers' insights, leading to quick adaptation but potential subjectivity.

# Business Impact
- **Human Intuition Matrix Method:**
  - Enables quick adaptation to market changes with a 4-11% difference from perfect forecast.
  - Utilizes managers' expertise but may lead to inconsistent pricing without careful control.
- **Simple Linear Optimization:**
  - Reduces inconsistency and improves revenue prediction accuracy.
  - Systematic and unbiased, making it suitable for markets with predictable consumer price reactions.
  - Optimizes pricing decisions to maximize total revenue while considering inventory constraints.
  


