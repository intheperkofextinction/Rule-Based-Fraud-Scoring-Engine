# Rule-Based-Fraud-Scoring-Engine

This project implements a fraud detection system using a rule-based approach to score and classify users into High, Medium, and Low risk levels based on transaction behaviors.

## Dashboard Preview
![Click here](https://github.com/user-attachments/assets/4af7679c-094c-4e8f-9175-11c090520906)


## Logic & Rule Description

**Rule 1 (Low Balance)**: Users flagged for having critically low balances.

**Rule 2 (High Frequency)**: Users flagged for abnormally high number of transactions.

**Rule 3 (Abnormal Amount)**: Users flagged for suspiciously high transaction amounts.

Users are assigned a risk_score based on the number of rules triggered, and classified as:

High Risk: 3 rules triggered

Medium Risk: 2 rules triggered

Low Risk: 1 or 0 rules triggered

## Dataset Information

This project uses a synthetically generated dataset created using the Faker Python library to simulate realistic transaction behavior for 1000+ users.

Features include:

user_id

timestamp

amount

transaction_type

balance

This allows for safe experimentation without using any sensitive or real-world financial data.

##  How the Data Was Generated

The dataset was generated using the following Python libraries:

Faker: to generate user names, timestamps, and random transaction types.

NumPy & random: to simulate transaction amounts and account balances with realistic distributions.

Code for data generation is included in the notebook for full transparency and reproducibility.

## Tools & Technologies Used

Python (Data preprocessing & Rule Engine)

Power BI (Interactive Dashboard)

Pandas, NumPy, Faker (Synthetic data generation)

## Key Visuals in Dashboard

Risk Level Distribution – Donut & Bar Chart

Daily Risk Trend Over Time – Line Chart

Summary Metrics – Risk user counts & percentage, total transactions, and unique users

Slicer – Risk-level based filtering

## How to Run
Clone the repo:

git clone https://github.com/intheperkofextinction/Rule-Based-Fraud-Scoring-Engine

Open the Rule_Based_Fraud_Scoring_Engine.ipynb to generate the dataset.

Open Fraud_Risk_Scoring_Dashboard.pbix in Power BI Desktop to explore the visuals.

## Use Cases

AML & Fraud Analytics

Client Risk Categorization

Early Warning System for Suspicious Activities

 Contact
If you have any questions or suggestions, feel free to reach out via

Gmail: amal17ek@gmail.com

[GitHub](https://github.com/intheperkofextinction)

LinkedIn : linkedin.com/in/amal-s-9a5b86310


