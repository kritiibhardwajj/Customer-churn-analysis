# Telecom Customer Churn Analysis

## Project Overview

Exploratory Data Analysis (EDA) of customer churn patterns in a telecom company. This project analyzes 7,043 customer records to identify key factors influencing customer retention and churn behavior, providing actionable insights for business strategy.

## Dataset Information

The dataset contains comprehensive customer information with 21 features:

**Demographic Features:** Customer ID, gender, senior citizen status, dependents, partnership status

**Service Features:** Internet service type, phone service, online security, online backup, device protection, tech support, streaming TV, streaming movies

**Account Features:** Contract type, paperless billing, payment method

**Billing Information:** Monthly charges, total charges, tenure

**Target Variable:** Churn (whether customer left in the last month)

Total Records: 7,043 customers
Total Features: 21

## Analysis Sections

**1. Dataset Exploration**
- Data structure and dimensions
- Feature identification and data types
- Statistical summary and distributions
- Missing value analysis

**2. Churn Distribution**
- Overall churn rate calculation
- Class distribution analysis
- Churned vs. retained customer counts

**3. Demographic Analysis**
- Churn patterns by gender
- Senior citizen vs. regular customer churn comparison
- Impact of family structure (dependents, partners) on retention

**4. Service Utilization Impact**
- Internet service type influence on churn
- Contract type analysis (month-to-month vs. long-term)
- Service bundle effect on customer retention
- Individual service adoption patterns

**5. Financial Analysis**
- Monthly charges distribution by churn status
- Total charges correlation with tenure
- Payment method preferences
- Billing impact on retention

## Key Findings

**1. Contract Type Significance** - Month-to-month customers demonstrate substantially higher churn rates compared to annual or two-year contracts, indicating contract commitment as a critical retention lever.

**2. Internet Service Quality** - Fiber optic internet users exhibit different churn patterns than DSL users, suggesting potential service quality or pricing considerations.

**3. Tenure Effect** - Strong inverse correlation between customer tenure and churn—newer customers show markedly higher churn risk.

**4. Service Bundling** - Customers with multiple service subscriptions demonstrate lower churn rates, indicating cross-service adoption reduces churn.

**5. Payment Method Variation** - Churn rates vary by payment method, suggesting friction points in certain payment experiences.

## Technologies Used

- Python 3.13 - Core programming language
- Pandas 3.0.1 - Data manipulation and analysis
- NumPy 2.4.3 - Numerical computing
- Matplotlib 3.10.8 - Data visualization
- Seaborn 0.13.2 - Statistical visualization
- Jupyter Notebook - Interactive analysis environment

## Project Structure
```
customer-churn-analysis/
├── README.md
├── requirements.txt
├── data/
│   └── telecom_customer_churn.csv
├── notebooks/
│   └── churn_analysis.ipynb
└── results/
    └── visualizations/
```

## Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

4. Run analysis cells sequentially to reproduce findings

## Key Visualizations

- Churn distribution (count plot)
- Demographic breakdown by churn status
- Contract type impact on retention
- Service type analysis
- Financial metrics comparison
- Correlation heatmap

## Business Insights

The analysis reveals actionable retention strategies:

- Convert month-to-month customers to longer-term contracts through promotional incentives
- Investigate fiber optic service quality and competitive positioning
- Implement early engagement programs for customers in first 3 months
- Promote service bundle adoption to increase customer stickiness
- Streamline payment processes to reduce friction points

## Future Work

- Predictive modeling for churn prediction
- Customer segmentation analysis
- Lifetime value estimation by segment
- Churn propensity scoring model
- Survival analysis for customer retention

## Author

Machine Learning Engineer | Data Science Professional

## License

Open source - available for educational and professional purposes
