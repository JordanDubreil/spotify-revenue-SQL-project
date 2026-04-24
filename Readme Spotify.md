Readme Spotify



**End-to-End Data Workflow**



This project demonstrates a complete data workflow across data engineering, data analytics, and data science, showing how raw data can be transformed into actionable insights and predictive capabilities.



**Data Engineering**

Overview



The foundation of this project is a fully designed and implemented relational database built in Azure SQL to simulate a real-world music streaming platform.



Key Contributions

Designed a normalized database schema with 11 interconnected tables

Implemented primary and foreign key relationships to ensure data integrity

Created bridge and lookup tables (e.g., track\_genres, genres)

Structured data ingestion from Excel into Azure SQL

Ensured scalability and flexibility for analytical and modeling use cases

Outcome



A clean, structured, and query-ready database that supports complex joins, aggregations, and downstream analysis.





**Data Analytics**

Overview



SQL was used to analyze revenue performance, user behavior, and content engagement to generate business insights.



Key Analyses

Revenue performance by subscription plan

Net revenue accounting for refunds

Payment success, failure, and refund trends

Revenue distribution by country

Promotion effectiveness

Subscription lifecycle and tenure analysis

User engagement (streams, sessions, listening duration)

Content performance (top genres and artists)

SQL Techniques Used

Complex joins (INNER, LEFT)

Aggregations (SUM, COUNT)

Conditional logic (CASE WHEN)

Common Table Expressions (CTEs)

Window functions (RANK, NTILE)

Outcome



Identified key drivers of revenue, user engagement patterns, and content performance, providing actionable insights for business strategy.



**Data Science**

Overview



The project was extended into a predictive analytics framework to identify high-value users based on behavioral and subscription data.



Problem Definition



Predict which users are likely to generate high revenue.



Approach

Engineered a user-level dataset using SQL

Aggregated features including:

total paid revenue

subscription tenure

auto-renew behavior

listening activity (streams, sessions, duration)

skip rate

Created a target variable:

high\_value\_user = 1 for top 25% of users by revenue

high\_value\_user = 0 otherwise

Techniques Used

Feature engineering using SQL

Window functions (NTILE) for segmentation

Data preparation for machine learning models

Outcome



A modeling-ready dataset that can be used for classification models such as logistic regression to predict high-value users.



Business Value

Enables targeted marketing for high-value users

Supports retention and upselling strategies

Helps optimize customer lifetime value

