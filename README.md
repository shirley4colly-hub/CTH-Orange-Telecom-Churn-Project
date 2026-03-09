# CTH-Orange-Telecom-Churn-Project
Overview
This project analyzes customer churn in a telecom company using Power BI. The goal is to identify key factors that influence customer churn and provide actionable insights that can help telecom companies improve customer retention strategies.

The dashboard explores behavioral, geographic, and service-related patterns that contribute to churn and highlights the most important drivers affecting customer decisions.

Dashboard Highlights
Key Metrics
Total Customers: 2,666
Churned Customers: 388
Churn Rate: 14.55%
Average Revenue Per User (ARPU): $59.36
Customer Service Sensitivity Index: 1.41
Plan Churn Ratio: 3.88

These KPIs provide a quick snapshot of overall customer retention performance.

Key Insights
1. Customer Service Impact
Customers who frequently contact customer service are significantly more likely to churn.
Higher service call frequency indicates dissatisfaction and unresolved issues.

Insight:
Customers with 4+ service calls show the highest churn probability.

2. International Plan Risk
Customers subscribed to the International Plan exhibit significantly higher churn.

Insight:
Customers with an international plan churn almost four times more than those without it.
This may indicate: Pricing dissatisfaction, Billing concerns and Low perceived value of international services

3. Geographic Churn Patterns
Certain states show churn rates exceeding 25%, suggesting geographic variations in customer satisfaction.

Insight:
Regional churn hotspots highlight opportunities for targeted retention campaigns.

4. Usage vs Revenue Patterns
High-usage customers generate higher revenue but are not immune to churn.

Insight:
Some high-value customers leave due to service dissatisfaction rather than price.

This emphasizes the need for proactive customer engagement and support improvements.

Behavioral Analysis
Customer Service Call Frequency:

Churn increases significantly as customer service interactions increase.
Low call frequency → Low churn
Medium call frequency → Moderate churn
High call frequency → Very high churn

This suggests customer support experience is a major churn driver.

Customer Tenure (Account Length):
Customers with shorter account tenure show slightly higher churn tendencies.

Insight:
New customers may leave early if their onboarding experience is poor.

Tools & Technologies Used:

Power BI
DAX (Data Analysis Expressions)
Data Visualization
Customer Segmentation Analysis
Dataset Features

The dataset contains the following attributes:

State, Account length, Area code, International plan, Voice mail plan, Number of voice mail messages,
Total day minutes, Total day calls, Total day charge, Total evening minutes, Total evening calls,
Total evening charge, Total night minutes, Total night calls, Total night charge, Total international minutes
Total international calls, Total international charge, Customer service calls, Churn (Target variable)

New columns were added and Meaures created

Business Recommendations
Based on the analysis, the following actions are recommended:

1. Improve Customer Support
Reduce churn by improving customer service response time and issue resolution quality.

2. Review International Plan Pricing
Evaluate the pricing structure and value proposition of international plans.

3. Identify High-Risk Customers
Use churn indicators such as:
High service call frequency
International plan subscription
High usage complaints

to proactively target retention efforts.

4. Proactive Customer Retention

Implement early warning systems for customers who show high churn risk behaviors.

Project Structure:
Telecom-Churn-Analysis
│
├── dataset
│   └── telecom_churn.csv
│
├── dashboard
│   └── telecom_churn_dashboard.pbix
│
├── presentation
│   └── telecom_churn_analysis_presentation.pptx
│
├── screenshots
│   └── dashboard_overview.png
│
└── README.md

Project Outcome:
This project demonstrates how data analytics and visualization can help businesses understand customer behavior, reduce churn, and improve strategic decision-making.

Through Power BI dashboards and KPI analysis, telecom companies can identify:

High-risk customer segments
Service experience issues
Revenue vs retention patterns
