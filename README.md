# E-commerce Sales Analysis Project

---

## Project Overview

This project aims to explore and analyze the sales trends, patterns, and profitability factors of an e-commerce business over the span of one year. Using real sales data, I will investigate how different variables such as product categories, pricing, commission rates, and city-based orders influence of my Trendyol e-commerce shop's overall performance. The ultimate goal is to derive actionable insights to optimize sales strategies, improve profitability, and enhance customer targeting.

By utilizing data visualization, statistical analysis, and machine learning techniques, the project will answer critical business questions and forecast future trends, providing a data-driven roadmap for growth.

---

## Objectives

1. **Understand Sales Trends**  
   Analyze seasonal and city-based trends to identify peak sales periods and location-based patterns.

2. **Price Sensitivity Analysis**  
   Investigate how different price ranges affect sales volume and identify the most profitable pricing strategies.

3. **Profitability Analysis**  
   Evaluate the impact of commission rates on net revenue and identify which products and categories are most profitable.

4. **Data-Driven Optimization**  
   Utilize the analysis to recommend targeted strategies for improving sales and profitability.

5. **Apply Data Science Techniques**  
   Leverage data processing, visualization, and statistical models to uncover deep insights and actionable conclusions.

---

## Motivation

This project stems from the need to understand key business drivers in an e-commerce context. Here's why it matters:

- **Strategic Growth**  
  By identifying seasonal and regional patterns, the business can better plan marketing campaigns and inventory management.

- **Profit Maximization**  
  Understanding which price ranges and commission rates yield the best results can directly impact the bottom line.

- **Customer Insights**  
  City and product-based analyses will help in better customer segmentation and targeted promotions.

- **Practical Application**  
  This project applies real-world data science concepts to improve business decision-making and strategy.

---

## Dataset

The dataset consists of one year of sales data with the following features:

- **Product Name:** Name of the sold product.  
- **Brand:** The brand of the product.  
- **Category:** The category to which the product belongs.  
- **Order Quantity:** The quantity of products ordered.  
- **Order Amount:** Total revenue generated from the order.  
- **Order Date and Season:** The date and season when the order was placed.


## Tools and Technologies

The following tools and technologies will be used for data analysis and visualization:

- **Python:** For data processing and analysis.  
- **Pandas:** For data manipulation and cleaning.  
- **Matplotlib and Seaborn:** For creating visualizations (bar charts, heatmaps, trend lines).  
- **Scikit-learn:** For potential predictive modeling and trend analysis.  
- **Jupyter Notebook:** For documenting the data exploration and insights.

---

## Analysis Plan

1. **Data Preparation**  
   - Import the dataset and handle missing or inconsistent data.  
   - Convert dates to datetime format and categorize price ranges if necessary.

2. **Exploratory Data Analysis (EDA)**  
   - Analyze sales trends over time, segmented by months and seasons.  
   - Visualize the distribution of sales across different cities and product categories.  
   - Identify top-performing products and cities.  
   - Assess the impact of price ranges on sales volume.

3. **Profitability and Commission Analysis**  
   - Calculate the net revenue after commissions.  
   - Identify products and categories that yield the highest profitability.  
   - Analyze which commission rates result in the best margins.

4. **Seasonality and Forecasting**  
   - Identify seasonal trends in sales and determine peak periods.  
   - Forecast future sales using simple statistical models.

5. **Visualization and Reporting**  
   - Create detailed visualizations to support each analysis point.  
   - Summarize key insights and recommendations.

---

## Example Analysis

1. **Sales Trend Over Months**  
   - A time series line chart illustrating monthly sales volumes to identify peak and low seasons.

2. **City-Based Sales Distribution**  
   - A heatmap to visualize which cities generate the most orders and revenue.

3. **Profitability by Price Range**  
   - A bar chart showing net profitability across different price categories.

4. **Impact of Commission Rates**  
   - A scatter plot to explore how various commission rates affect net revenue.

---
## 🔍 Analysis and Machine Learning
1. **Sales Trend Analysis**: Monthly and seasonal trends visualized using line plots and pie charts.
2. **Category and Seasonal Analysis**: Identified top-selling product categories across seasons.
3. **Logistic Regression – High vs Low Sales Classification**:
   - Predicted whether a sales record would be high or low based on month, season, and category.
   - Achieved **77% accuracy**, with strong low-sales prediction performance.
4. **Random Forest Regression – Sales Quantity Prediction**:
   - Predicted continuous **net sales quantity** (`Net Sats Adedi`).
   - Achieved **MAE of 96.84** and **R² score of 0.79**.
5. **Result of ML Tasks**:
   - Logistic Regression classified sales records (binary: high/low).
   - Random Forest predicted continuous net sales quantity.
   - Key insights highlighted and suggestions for future improvements (e.g., hyperparameter tuning, feature engineering).

## Conclusion

By the end of this project, we aim to answer key business questions such as:

- Which seasons and cities drive the highest sales?  
- Which product categories and price ranges are the most profitable?  
- How do commission rates impact overall profitability?  
- What strategic adjustments can be made to maximize future sales and revenue?

The insights derived from this analysis will not only help optimize current strategies but will also provide a strong foundation for data-driven decision-making in future business planning.

---

I'm excited to uncover meaningful insights from this data and drive actionable business strategies that contribute to long-term success!
