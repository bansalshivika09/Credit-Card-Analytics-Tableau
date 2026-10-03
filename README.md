# Credit Card Portfolio, Customer & Campaign Analytics

 Overview

This project focuses on analyzing credit card customer behavior, transaction activity, portfolio risk, and marketing campaign performance.

The project combines customer-level credit information with transaction and campaign data to understand how customers use their credit cards, how spending varies across different segments and channels, how payment and utilization patterns relate to portfolio risk, and how marketing campaigns perform.

Python and SQL were used for data preparation and analysis, while Tableau was used to build interactive dashboards for business reporting.

What I Analyzed

* Customer spending and transaction patterns
* Credit utilization and credit limits
* Payment and billing behavior
* Default rates across customer segments
* Transaction categories and channels
* Marketing campaign response and conversion
* Campaign costs, revenue, and ROI

 Dataset

The project contains five datasets:

 `customers.csv` – customer information, credit limits, billing, payments, utilization, default status, and customer segments
 `transactions.csv` – transaction dates, categories, channels, amounts, rewards, and transaction status
 `campaigns.csv` – campaign details, campaign type, target segment, dates, and budget
 `campaign_contacts.csv` – customer contacts, responses, conversions, channels, and contact costs
 `campaign_performance.csv` – campaign-level revenue, costs, net revenue, and ROI

The customer dataset contains around 30,000 records, the transaction dataset contains 120,000 records, and the campaign contact dataset contains 50,000 records.

The transaction and campaign datasets are synthetic and were created to extend the customer data for transaction and marketing campaign analysis.

 Tools Used

* Python
* Pandas
* NumPy
* SQL
* MySQL
* Tableau
* Jupyter Notebook
* Excel

 Analysis

 Customer Analysis

Customer data was analyzed to understand credit limits, utilization, billing and payment behavior, customer segments, and default patterns.

Customer segments were used to compare spending and risk characteristics across different groups.

 Transaction Analysis

Transaction data was analyzed across different categories and channels to understand spending behavior and transaction activity.

The analysis includes approved and declined transactions, transaction volume, average ticket size, rewards earned, and monthly spending trends.

 Credit Risk & Portfolio Health

The risk analysis focuses on default rates, credit utilization, billing and payment behavior, and customer payment status.

The analysis also compares risk patterns across customer segments, utilization bands, age groups, and education levels.

 Campaign Analysis

Marketing campaign data was used to analyze customer responses, conversions, contact costs, campaign revenue, budget utilization, and ROI.

Campaign performance was compared across campaigns, contact channels, and target customer segments.

 Tableau Dashboard

The Tableau dashboard is divided into four sections.

 Executive Overview

Provides a summary of portfolio performance including:

* Total Spend
* Active Customers
* Default Rate
* Average Utilization
* Campaign Revenue
* Decline Rate
* Monthly spending trends
* Spend by customer segment
* Spend by transaction category

 Spending Behaviour

Looks at:

* Spending by category and channel
* Transactions by channel
* Average ticket size by age band
* Rewards earned by segment
* Approved versus declined transactions
* Top transaction categories

 Credit Risk & Health

Analyzes:

* Default rate by customer segment
* Default rate by utilization band
* Default rate by age and education
* Billed versus paid amounts
* Payment status
* Credit limit versus utilization

 Campaign Performance

Tracks:

* Campaign revenue and ROI
* Response and conversion
* Conversion by contact channel
* Campaign budget versus contact cost
* Campaign performance over time
* Response rate by target segment

 Key Metrics

The dashboard includes metrics such as:

* Total Spend
* Transaction Count
* Average Ticket Size
* Decline Rate
* Rewards Earned
* Active Customers
* Default Rate
* Average Utilization
* Total Billed
* Total Paid
* Payment Ratio
* Contact Response Rate
* Conversion Rate
* Conversion of Responders
* Cost per Conversion
* Campaign Revenue
* Contact Cost
* Budget Used
* ROI

 Project Files

```text
Credit-Card-Analytics-Tableau/
│
├── README.md
├── Credit_Card_Analytics.ipynb
│
├── customers.csv
├── transactions.csv
├── campaigns.csv
├── campaign_contacts.csv
├── campaign_performance.csv
│
├── dashboard.html
├── Credit_Card_Analytics.twbx
│
├── screenshots/
└── calculations/
```

 Dashboard Preview

Screenshots of the Tableau dashboards are included in the `screenshots` folder.

The original HTML dashboard is also included as a reference for the dashboard design and layout.

Analysis Workflow

```text
Customer Data
      ↓
Data Preparation
      ↓
Python / SQL Analysis
      ↓
Feature Engineering
      ↓
Customer & Campaign Analysis
      ↓
Tableau Calculations
      ↓
Interactive Tableau Dashboard
      ↓
Business Insights
```

 Project Objective

The main objective of this project is to bring customer, transaction, risk, and campaign information together into a single analytical view.

The dashboards are designed to make it easier to understand portfolio performance, customer behavior, credit risk, and campaign effectiveness through interactive visual analysis.
