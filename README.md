# Sales Forecasting & Business Analysis (Machine Learning Project)

## Project Overview
This project focuses on analyzing and forecasting sales using the Superstore dataset. It applies machine learning regression models to predict sales and extract meaningful business insights from historical data.

The goal is to support data-driven decision-making for improving sales performance and profitability.

---

## Problem Statement
Given historical sales data, the objective is to:
- Predict sales values using machine learning models
- Analyze key business patterns such as region-wise performance, profit trends, and category-based sales behavior

---

## Dataset Information
The dataset includes retail transaction data with features such as:
- Order details (Order Date, Ship Date, Ship Mode)
- Customer information (Segment, Region, City)
- Product details (Category, Sub-Category, Product Name)
- Sales, Quantity, Discount, Profit

---

## Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values
- Processed categorical variables
- Converted date features for time-based analysis

### 2. Exploratory Data Analysis (EDA)
- Monthly sales trends
- Sales by region
- Sales vs profit relationship
- Category-wise performance analysis

### 3. Model Building
Two regression models were used:
- Linear Regression
- Random Forest Regressor

### 4. Model Evaluation
- R² score used for evaluation
- Comparison between models to identify best performance

---

## Model Results

- Linear Regression R² Score: **0.285**
- Random Forest R² Score: **0.506**

### Conclusion:
Random Forest performed better due to its ability to capture non-linear relationships in the data.

---

## Key Findings

- Sales vary significantly across different regions.
- Certain product categories generate higher profits.
- Discounts negatively affect overall profit in many cases.
- Seasonal patterns are visible in monthly sales trends.

---

## Business Recommendations

- Focus marketing efforts on high-performing regions.
- Optimize discount strategies to protect profit margins.
- Invest more in high-performing product categories.
- Use historical trends for better inventory planning.

---

## Visualizations

The project includes:
- Monthly sales trend analysis
- Sales by region
- Sales vs profit relationship
- Actual vs predicted sales comparison

(See `images/` folder for visual outputs)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure
```
Sales-Forecasting-Analysis/
│
├── notebook.ipynb
├── images/
│ ├── actual_vs_predicted.png
│ ├── monthly_sales_trend.png
│ ├── sales_by_region.png
│ └── sales_vs_profit.png
└── README.md
```

---

## Author

Dua Zahra  
LinkedIn: https://www.linkedin.com/in/dua-zahra-ai/  
Email: duazahrazahra344@gmail.com  

---

