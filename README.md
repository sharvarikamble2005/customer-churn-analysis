#  Customer Churn Analysis
##  Project Overview
This project performs an end-to-end customer churn analysis using Python, SQLite, Pandas, Matplotlib, and Seaborn. The objective is to identify customer churn patterns, analyze customer behavior, and generate business insights through data visualization.
##  Objectives
- Analyze customer churn trends.
- Clean and preprocess customer data.
- Perform Exploratory Data Analysis (EDA).
- Visualize important KPIs.
- Generate actionable business insights.
##  Technologies Used
- Python
- SQLite
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
##  Data Cleaning
The following preprocessing steps were performed:
- Renamed inconsistent column names
- Removed unnecessary columns (`interests`, `pincode`)
- Converted `dob` to datetime format
- Standardized gender values
- Handled missing values
- Created new analytical features
##  Visualizations
The project includes:
- Monthly Churn Trend
- Churn by Plan Type
- Churn by State
- Correlation Heatmap
- Customer Segmentation
- Monthly Charges Analysis
- Churn Risk Analysis
##  Key Insights
- Monthly churn fluctuates over time with noticeable peak periods.
- Standard plan customers show a slightly higher churn rate.
- Uttar Pradesh recorded the highest churn among analyzed states.
- Churn Score is strongly correlated with Churn Risk and Churn Flag.
- Monthly charges alone are not a strong indicator of churn.
- Customer churn occurs across all subscription plans, indicating multiple influencing factors.
##  Business Recommendations
- Focus retention campaigns during high churn months.
- Improve customer engagement for Standard plan subscribers.
- Investigate reasons for higher churn in specific states.
- Use churn score for proactive customer retention.
- Monitor high-risk customers before contract renewal.
##  Project Structure
Customer-Churn-Analysis
│
├── churn_analysis.ipynb
├── customer_churn_1000.db
├── requirements.txt
├── README.md
└── .gitignore
```
**## ** Run the Project****


```bash
pip install -r requirements.txt
```

Open:

```
churn_analysis.ipynb
```

Run all cells in Jupyter Notebook.

---

##  Author

**Sharvari Kamble**

Computer Engineering Student

Mumbai University
