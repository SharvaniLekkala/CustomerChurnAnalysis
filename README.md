
## Workflow

1. **Data Cleaning (Jupyter Notebooks)**
   - Raw dataset cleaned for missing values, inconsistent types, and outliers.
   - *Notebook:* `01_data_cleaning.ipynb`

2. **Exploratory Data Analysis (EDA)**
   - Univariate, bivariate, and multivariate analysis to understand churn patterns.
   - *Notebook:* `02_eda.ipynb`

3. **Feature Engineering**
   - Creation of tenure bins, churn probability scores, categorical encoding, and customer cohorts.
   - *Notebook:* `03_feature_engineering.ipynb`

4. **Churn Insights Summary**
   - Key findings, visualizations, and interpretation of trends.
   - *Notebook:* `04_insights_summary.ipynb`

5. **Processed Data for Visualization**
   - Final dataset exported as `churn_featured.csv` for Power BI.

6. **Power BI Dashboard**
   - Interactive visual dashboard created using Power BI Desktop:
     - Pie chart (Churn Distribution)
     - KPI cards (Churn Rate, Total Customers, Total Churned)
     - Bar/Column charts (Churn by Contract, Payment Method, Internet Service)
     - Scatter plot (Monthly Charges vs. Tenure, colored by Churn)
     - Histogram (Distribution of Monthly Charges by Churn)
     - Treemap, demographic analysis, and slicers for interactivity
   - *File:* `CustomerChurnDashboard.pbix`

## How to Run

1. Clone the repository:
    ```
    git clone https://github.com/SharvaniLekkala/CustomerChurnAnalysis.git
    ```

2. Explore the data and notebooks:
    - Open Jupyter Notebooks in `/notebooks` for cleaning, EDA, and feature engineering.

3. Power BI Dashboard:
    - Open `CustomerChurnDashboard.pbix` in Power BI Desktop (Windows).
    - To interact, filter, or customize, use Power BI’s visual and slicer tools.

## How to Publish / Share

- Power BI dashboard can be published to Power BI Service for sharing and scheduled refreshes.
- `.pbix` file can be downloaded and opened by others using Power BI Desktop.

## Key Findings

- Churn rate and key drivers identified via visual and statistical analysis.
- Tenure, contract type, payment method, and monthly charges strongly correlate with churn.

## Dependencies

- Python (Jupyter, pandas, numpy, matplotlib, seaborn)
- Power BI Desktop (for dashboard visualization)

##Insights

1.Overall Churn
-26.6% of customers have churned (1,869 out of 7,032).
-This means roughly one in four customers leave, highlighting the importance of strong retention strategies.

2.Churn by Payment Method
Customers paying via electronic check show the highest churn rate.
Customers using automatic payments (bank transfer or credit card) are less likely to churn.
Encouraging customers to switch to auto-pay could improve retention.

3.Churn by Contract Type
Month-to-month contracts have the highest churn.
One-year and two-year contracts show significantly lower churn.
Promoting long-term contracts with incentives or discounts could help reduce churn.

4.Impact of Tenure and Monthly Charges
Customers with lower tenure are more likely to churn.
Churn decreases steadily as tenure increases, indicating that customers become more loyal over time.
Higher monthly charges are associated with higher churn, especially for customers with short tenure.
Improving onboarding experience and clearly communicating value can reduce early churn.

5.Distribution of Monthly Charges
Customers with moderate-to-high monthly charges have a higher churn percentage.
Offering flexible pricing plans or value-added services may help retain price-sensitive customers.

6.Recommendations
Promote long-term contracts through loyalty rewards or discounts.
Encourage auto-pay enrollment with small incentives.
Focus on early-stage customer engagement to reduce churn within the first few months.
Revisit pricing strategy for customers with higher charges.
Consider building a churn prediction model to proactively identify and engage at-risk customers.

## Author

Sharvani Lekkala



