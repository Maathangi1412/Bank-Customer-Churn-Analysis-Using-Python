# Bank Customer Churn Analysis Using Python

A Python-based exploratory and statistical analysis of bank customer churn, investigating customer demographics, geographical patterns, account balances, and membership activity to identify factors associated with customer exits and support data-driven customer retention strategies.

## Project Overview

Customer churn is an important challenge in the banking industry because losing customers can affect long-term relationships and business performance. Understanding customer characteristics and behaviours associated with churn can help banks identify retention concerns and make informed business decisions.

This project analyzes the Bank Customer Churn dataset from Maven Analytics using Python. It applies data inspection, cleaning, statistical analysis, and data visualization to explore churn patterns and identify customer segments that warrant further investigation.

## Objectives

- Analyze customer churn distribution and calculate the overall churn rate.
- Explore customer demographics, including age and geography.
- Examine relationships between churn, membership activity, and account balances.
- Apply statistical techniques to understand distributions, variability, skewness, and potential outliers.
- Perform univariate, bivariate, and multivariate analysis.
- Identify actionable business insights and recommend customer retention strategies.

## Dataset Information

- **Dataset Name:** Bank Customer Churn
- **Source:** [Maven Analytics Data Playground](https://mavenanalytics.io/data-playground/bank-customer-churn)
- **Domain:** Banking and Finance
- **File Format:** CSV
- **Records:** 10,000 customer records
- **Features:** 13 columns
- **Target Variable:** `Exited`

### Dataset Features

| Column | Description |
|---|---|
| `CustomerId` | Unique customer identifier |
| `Surname` | Customer surname |
| `CreditScore` | Customer credit score |
| `Geography` | Customer's country |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `Tenure` | Number of years the customer has been with the bank |
| `Balance` | Customer account balance |
| `NumOfProducts` | Number of bank products held |
| `HasCrCard` | Whether the customer has a credit card |
| `IsActiveMember` | Whether the customer is an active member |
| `EstimatedSalary` | Customer's estimated salary |
| `Exited` | Customer churn indicator: 1 = exited, 0 = stayed |

## Tools and Technologies

- **Python** – Programming and analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Notebook development and execution
- **GitHub** – Project version control and documentation

## Project Workflow

### Stage 1: Project Setup and Initial EDA

- Loaded the dataset from GitHub into a Pandas DataFrame.
- Inspected the dataset structure, column names, and data types.
- Examined the first few records and generated descriptive statistics.
- Reviewed the dataset for initial data quality issues.

### Stage 2: Data Cleaning and Transformation

- Checked for duplicate records.
- Identified and handled missing values.
- Reviewed and transformed data types where necessary.
- Performed data wrangling and feature engineering.
- Prepared the dataset for statistical analysis and visualization.

### Stage 3: Statistical Analysis and Visualization

Applied statistical techniques and created nine visualizations across three analytical categories.

**Univariate Analysis**
- Customer churn distribution.
- Age distribution of customers.
- Box plot of customer age.

**Bivariate Analysis**
- Customer churn rate by geography.
- Customer churn rate by active membership.
- Customer age by churn status.
- Account balance by churn status.

**Multivariate Analysis**
- Customer churn rate by age group and geography.
- Customer churn rate by geography and active membership.

Each visualization was accompanied by an interpretation explaining the observed patterns and their potential business implications.

Statistical analysis also included measures of central tendency, variance, standard deviation, skewness, kurtosis, and potential outlier detection, as covered in the project workflow.

### Stage 4: Documentation and Business Insights

- Summarized key findings in plain English.
- Identified customer segments with elevated churn rates.
- Classified the work under descriptive, diagnostic, predictive, and prescriptive analysis.
- Developed recommendations to support customer retention.
- Documented future enhancements for predictive modelling and automated reporting.

## Key Findings

### 1. Overall Customer Churn

Out of 10,000 customers:

- **Customers who stayed:** 7,963 (79.63%)
- **Customers who exited:** 2,037 (20.37%)

Approximately one in five customers exited the bank, establishing an important baseline for customer retention analysis.

### 2. Geographical Differences

The overall churn rates varied across the three countries:

| Geography | Churn Rate |
|---|---:|
| Germany | 32.44% |
| Spain | 16.67% |
| France | 16.15% |

Germany had the highest churn rate, suggesting that customer retention challenges may differ across geographical markets.

### 3. Membership Activity and Churn

| Membership Status | Churn Rate |
|---|---:|
| Inactive | 26.85% |
| Active | 14.27% |

Inactive members had a higher churn rate than active members, indicating an association between membership activity and customer retention.

### 4. Age and Churn Patterns

Customers who exited had an average age of 44.84 years, compared with 37.41 years among customers who stayed.

The multivariate analysis identified customers aged 51–60 in Germany as the segment with the highest observed churn rate, at 69.55%.

### 5. Account Balance and Churn

| Customer Status | Average Balance | Median Balance |
|---|---:|---:|
| Exited | 91,108.54 | 109,349.29 |
| Stayed | 72,745.30 | 92,072.68 |

Customers who exited had higher average and median account balances than customers who stayed. Further investigation is needed to understand the relationship between account balances and customer exits.

## Business Recommendations

Based on the observed patterns, the following actions could be investigated:

1. **Prioritize Germany:** Investigate the factors associated with the higher churn rate in Germany, particularly among customers aged 51–60.
2. **Improve Customer Engagement:** Explore targeted engagement initiatives for inactive members.
3. **Investigate Age-Related Patterns:** Examine whether customer needs, product suitability, and service experiences differ across age groups.
4. **Review Higher-Balance Customers:** Investigate the experiences and requirements of customers with higher account balances.
5. **Monitor Retention Metrics:** Track overall and segment-level churn rates over time to evaluate retention performance.

These recommendations are based on observed associations and should be validated through further analysis and business evidence.

## Limitations

- The analysis uses a single dataset and may not reflect current customer behaviour.
- The findings identify associations rather than proving causal relationships.
- The analysis is exploratory and does not establish that any particular factor causes customer churn.
- Predictive performance has not been evaluated because a machine learning model is not included in the current project.

## Future Enhancements

- Incorporate a larger or more recent dataset for deeper analysis.
- Automate repetitive data cleaning and reporting tasks using Python scripts.
- Develop interactive dashboards using Power BI or Tableau.
- Build machine learning classification models to estimate customer churn risk.
- Evaluate predictive models using accuracy, precision, recall, F1-score, and a confusion matrix.
- Evaluate retention initiatives using customer outcomes and churn trends over time.

## Conclusion

This project demonstrates the application of Python, statistical analysis, and data visualization to investigate bank customer churn. The analysis identified geographical differences, membership activity patterns, age-related differences, and account-balance variations associated with customer exits.

The findings provide a foundation for further investigation into customer retention and demonstrate practical skills in data cleaning, exploratory data analysis, statistical interpretation, and business-focused visualization.

## Repository Structure

```text
Bank-Customer-Churn-Analysis-Using-Python/
│
├── Source_File.csv
├── Bank_Customer_Churn_Analysis.ipynb
└── README.md
```

*Update the notebook filename in this structure if your actual file has a different name.*

## Author

**Maathangi P**

Aspiring Data Analyst | Python | SQL | Data Analytics | Data Visualization

- GitHub: [Maathangi1412](https://github.com/Maathangi1412)
- LinkedIn: [Maathangi P](https://www.linkedin.com/in/maathangi-p-analyst)


