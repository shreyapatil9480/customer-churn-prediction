# Customer Churn Prediction Project

This project showcases the creation and analysis of a **synthetic customer churn dataset**.  It is designed to demonstrate data exploration, visualization and predictive modeling skills relevant for roles such as business analysts, program managers, and data analysts.

## Dataset Overview

The dataset `synthetic_customer_churn.csv` consists of 1000 synthetic customer records with the following columns:

- **customer_id**: Unique identifier for each customer.
- **age**: Customer age (18–65).
- **gender**: Gender (Male, Female, Non-Binary).
- **subscription_tenure_months**: Number of months the customer has been subscribed.
- **monthly_charges**: Amount the customer is charged per month (USD).
- **num_support_tickets**: Number of support tickets the customer raised.
- **payment_method**: Payment method used (Credit Card, PayPal, Bank Transfer).
- **plan**: Subscription plan (Basic, Standard, Premium).
- **region**: Geographic region (North, South, East, West).
- **churn**: Binary indicator (1 if the customer churned, 0 otherwise).

The churn labels are generated from a logistic function based on features such as tenure, monthly charges, number of support tickets, subscription plan, and payment method.  Customers with shorter tenure, lower monthly charges, more support tickets, and lower-tier plans have a higher probability of churn.

## Analysis Notebook

The Jupyter notebook `customer_churn_analysis.ipynb` includes:

1. **Loading and inspecting the dataset**.
2. **Exploratory Data Analysis (EDA)**: distribution plots, summary statistics, and correlation heatmap.
3. **Predictive modeling**: logistic regression and random forest classifiers to predict churn, with model evaluation metrics such as accuracy, classification report, and confusion matrix.

To run the notebook, install dependencies listed in `requirements.txt` and open the notebook using Jupyter.

## Getting Started

1. Clone or download this repository.
2. Create a virtual environment (optional but recommended).
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook customer_churn_analysis.ipynb
```

5. Follow the notebook cells to perform EDA and build predictive models.

## Requirements

Dependencies are listed in `requirements.txt`.  The key libraries include `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.

## License

This project uses a synthetic dataset created solely for demonstration purposes.  Feel free to modify and extend the analysis for your learning or portfolio.
