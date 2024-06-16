# Revenue-Management-Optimization
This repository contains a project on optimizing revenue management strategies through various pricing models. It includes data collection, methodology, and results analysis using human intuition, linear optimization, and non-linear optimization approaches

# Objective
- Implement and compare pricing strategies to maximize revenue and minimize inventory costs over a 15-week period.

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
- Utilizes managers' tacit knowledge and historical data.
- Visualizes sales outcomes under different pricing scenarios.

### 2. Linear Optimization (Linear Demand Variation)
- Employs a linear programming model.
- Assumes a linear relationship between price and market demand.

### 3. Non-linear Optimization (Non-linear Demand Variation)
- Incorporates non-linear consumer responses to pricing.
- Considers factors like price sensitivity and psychological pricing.

# Results
- **Random Strategy (200 runs):** Mean difference of 16.27% from perfect foresight.
- **Simple Linear Optimization (50 runs):** Mean difference of 8.05%.
- **Human Intuition (3 runs):** Mean difference of 4.28%.
- **Complex Linear Optimization (5 runs):** Mean difference of 2.27%.

# Business Impact
- **Human Intuition Matrix Method:** Quick adaptation with 4-11% difference from perfect forecast.
- **Simple Linear Optimization:** Reduces inconsistency and improves revenue prediction accuracy.
- **Complex Linear Optimization:** Captures market dynamics and optimizes revenue effectively.
