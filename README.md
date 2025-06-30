# 🛒 Customer Segmentation & Behavior Analysis – SuperStore Dataset

This project explores customer segmentation and purchasing behavior using the SuperStore dataset. It includes extensive data cleaning, feature engineering, visualization, customer clustering, and simulation of product-level transactions to derive actionable business insights.

## 📊 Key Features

- Created **age** and **age group** features from birth year.
- Engineered features like **Family Status**, **Income Group**, **Preferred Channel**, etc.
- Imputed missing values using linear regression.
- Conducted EDA and **outlier removal** using IQR method.
- Visualized spending patterns by education, age, family status, and income.
- Clustered customers into meaningful segments using **KMeans**.
- Simulated **purchase-level data** including product names, categories, feedback, and locations.
- Analyzed **preferred channels**, **return rates**, and **satisfaction scores** across segments and cities.

## 📦 Tools & Libraries

- Python, NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (for regression and clustering)

## 📁 Files

- `SuperStore-Data.csv`: Source dataset
- `notebook.ipynb`: Main analysis and modeling notebook
- `README.md`: This file
- (Optional) `purchase_data.csv`: Generated synthetic purchase-level dataset

## 📌 Insights

- **Customers with kids** tend to spend less and are more price-conscious.
- **Luxury Loyalists** spend across all channels and categories.
- **Catalog** users show higher conversion when visiting the website.
- City-level analysis reveals high-revenue locations and product preferences.

## 📍 Next Steps

- Integrate with a dashboarding tool (e.g., Power BI or Tableau).
- Expand clustering using customer sentiment and feedback.
- Use RFM modeling to refine customer segmentation further.
