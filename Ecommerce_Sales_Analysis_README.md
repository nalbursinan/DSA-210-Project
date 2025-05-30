
# 📊 E-commerce Sales Analysis Project

## 📖 Overview
This repository analyzes e-commerce sales data over a full year to uncover trends, category performance, and sales predictions. Real-world sales data was processed and analyzed to answer key business questions and support data-driven decision making.

## 🎯 Objectives
- Analyze monthly and seasonal sales trends.
- Identify top-performing product categories.
- Use machine learning models to classify high vs low sales and predict net sales quantities.
- Provide actionable insights for sales optimization.

## 📂 Dataset
- **Product Name**: Name of the sold product.
- **Category**: Product category.
- **Order Quantity**: Number of items sold.
- **Order Date and Season**: Date and season of the order.
- **Net Sales Quantity**: Total sales quantity.

## 🛠️ Tools and Technologies
- Python, Jupyter Notebook
- Pandas, Matplotlib, Seaborn
- Scikit-learn (Logistic Regression, Random Forest)

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

## 🔑 Key Findings
- High sales are more common in certain categories during specific seasons.
- Logistic Regression effectively classified sales records as high or low.
- Random Forest Regression captured complex data patterns for sales quantity prediction.
- Combining classification and regression provided a comprehensive sales analysis.

## 📈 Conclusion
This analysis revealed valuable insights into sales behavior, including category-season performance and quantity forecasts. These findings provide a strong foundation for data-driven sales strategy development.

## 💾 Next Steps
- Enhance models with advanced techniques (e.g., XGBoost, hyperparameter tuning).
- Explore additional features and datasets.
- Incorporate model explainability tools (e.g., SHAP) to understand decision drivers.

---

_Explore the accompanying Jupyter Notebook to view detailed analyses, visualizations, and model performance._

---
