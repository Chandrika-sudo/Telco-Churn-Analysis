# Telco Customer Churn Analysis

## About the Project

This project focuses on understanding why customers leave a telecom company and identifying the factors associated with customer churn.

I worked with a dataset of 7,043 customers and analyzed their contract types, monthly charges, tenure, payment methods, and services to understand which groups were more likely to leave.

The goal was not just to find churn percentages, but to understand the patterns behind them and identify areas where a company could improve customer retention.

## Dataset

I used the IBM Telco Customer Churn dataset, which contains information about 7,043 customers.

The dataset includes:

- Customer details and tenure
- Contract types and payment methods
- Monthly and total charges
- Internet and other subscribed services
- Whether a customer has churned

## Tools Used

- **Python:** Data cleaning and analysis
- **Pandas and NumPy:** Data processing
- **SciPy:** Statistical hypothesis testing
- **Matplotlib and Seaborn:** Data visualization
- **Power BI:** Interactive dashboards

## What I Did

### 1. Data Cleaning

I started by checking the dataset for missing values, incorrect data types, and inconsistencies.

Some values in the `TotalCharges` column were blank for customers with zero tenure. I handled these cases before moving on to the analysis.

### 2. Exploratory Data Analysis

I explored how churn varied across different customer groups, including contract types, tenure, monthly charges, and payment methods.

This helped me understand which customer segments had higher churn rates.

### 3. Statistical Analysis

I used statistical tests to check whether the relationships I observed were meaningful.

- **Chi-square test:** To examine relationships between categorical variables and churn.
- **Welch's t-test:** To compare numerical variables between churned and retained customers.
- **Cramér's V:** To measure the strength of associations between categorical variables and churn.

### 4. Power BI Dashboard

I created Power BI visualizations to make the findings easier to understand and compare.

The dashboard helps explore churn patterns across customer segments and highlights areas that may need attention.

## Key Findings

- **Overall churn rate:** Around 26.5% of customers had churned.
- **Contract type:** Contract type showed the strongest categorical association with churn, with a Cramér's V of approximately 0.41.
- **Customer tenure:** Churn patterns differed across customer tenure groups, making tenure an important area to examine.
- **Customer segmentation:** Comparing different customer groups helped identify segments that may benefit from targeted retention efforts.

These findings show associations in the data, rather than proving that any individual factor directly causes churn.

## What I Learned

This project helped me understand how statistical analysis can be used to solve business problems.

I learned how to move beyond basic charts, test relationships between variables, and turn analytical findings into useful business insights.

It also gave me practical experience with customer segmentation, churn analysis, and communicating results through Power BI.

## Conclusion

Customer churn is an important challenge for subscription-based businesses. Understanding which customer groups are more likely to leave can help companies make better decisions about customer engagement and retention.

Through this project, I explored how data cleaning, statistical testing, and visualization can work together to provide a clearer picture of customer churn.

## Data Source

IBM Telco Customer Churn Dataset — available through Kaggle and IBM sample data resources.
