# Retail Sales Analysis using Machine Learning

## Project Overview
Retail businesses generate large volumes of sales data that can be analyzed to uncover insights into customer behavior, product performance, and revenue trends.  
This project focuses on analyzing retail sales data and building a predictive model using **Random Forest Regressor** to forecast future sales.

The insights derived can help businesses improve pricing strategies, inventory planning, and marketing decisions.

---

## Objectives
- Analyze key factors influencing retail sales (product categories, discounts, regions, customer segments)
- Perform data preprocessing and cleaning
- Conduct exploratory data analysis (EDA) using visualizations
- Build a machine learning model for sales prediction
- Evaluate model performance using regression metrics
- Provide actionable business insights

---

## Dataset
- **Dataset Name:** SuperStore Orders Dataset
- **Type:** Historical retail transaction data
- **Key Columns:**
  - Sales, Quantity, Discount, Profit
  - Category, Sub-category
  - Region, Market
  - Order Date, Ship Date

---

## Technologies Used

### Programming Language
- Python 3.x

### Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Tools & Environment
- Spyder (Anaconda)
- Jupyter Notebook
- Microsoft Excel
- Windows OS

---

## Data Preprocessing
- Converted sales and discount columns to numeric format
- Handled missing and infinite values
- Extracted date-based features (year, month)
- Feature engineering:
  - Discounted sales
  - Profit margin
  - Net profit per unit
  - Order fulfillment time
- Applied One-Hot Encoding to categorical variables

---

## Exploratory Data Analysis (EDA)
- Yearly sales comparison across sub-categories
- Discount vs sales analysis
- Correlation analysis using heatmaps
- Trend analysis over time

---

## Machine Learning Model
- **Algorithm:** Random Forest Regressor
- **Target Variable:** Sales
- **Train-Test Split:** 80% training, 20% testing

### Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R²)

---

## Results & Insights
- Product category and discount rates significantly impact sales
- Regional performance varies across markets
- Random Forest model provides reliable sales predictions
- Feature engineering improves predictive accuracy

---

## Challenges & Limitations
- Presence of missing or inconsistent data
- No inclusion of external factors like economic trends or seasonality
- Risk of overfitting without hyperparameter tuning
- Analysis limited to historical data

---

## Future Enhancements
- Integrate external data sources (economic indicators, customer sentiment)
- Experiment with advanced models (XGBoost, LSTM)
- Implement dynamic pricing strategies
- Perform customer segmentation using clustering techniques
- Develop real-time dashboards using Power BI or Tableau

---

## Conclusion
This project demonstrates how retail sales data can be transformed into meaningful insights using data analysis and machine learning.  
Predictive modeling enables better planning, efficient resource allocation, and data-driven decision-making, helping businesses remain competitive in the retail market.

---

## Author
**Joel Chandy**  
Retail Sales Analysis Project  
