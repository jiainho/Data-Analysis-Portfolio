# Ho Nguyen Gia Linh - Data Analyst Portfolio
## About
Hi, I'm Linh! I’m a final-year Business Administration student specializing in Data Analysis and Accounting & Finance, with a deep interest in using data to drive strategic decision-making and improve business performance. With a strong foundation in analytics and hands-on experience from academic projects and competitions, I’m eager to start my career as a Financial Data Analyst or Data Specialist.

Throughout my journey, I’ve applied tools like SQL, Python, Power BI, Excel, and SAS to conduct meaningful analysis—from predicting customer churn to visualizing performance KPIs for business growth. My background combines both the technical side of data analytics and the financial understanding of business operations, allowing me to interpret complex datasets and translate them into actionable insights.

Beyond the classroom, I’ve worked as a Research Assistant, supported business case competitions, and led communication campaigns using data to improve audience engagement. I’m constantly exploring new tools and sharpening my skills, driven by curiosity and a passion for uncovering patterns that inform smarter decisions. Whether working independently or collaborating in a cross-functional team, I’m motivated by the challenge of transforming data into impactful outcomes.


My CV in [pdf](https://drive.google.com/file/d/1rnv6kYaxM7cAns3IPKJWFHA8WAx9wzR8/view?usp=sharing).

This is a repository to showcase skills, share projects and track my progress in Data Analytics related topics.

## Table of Contents
- [About](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)
  - SAS - Machine Learning
    - [Retail Customer Behavior Analysis](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#retail-customer-behavior-analysis)
    - [Netflix user base Analysis](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#netflix-user-base-analysis-revenue-insights-and-strategies)
    - [Predicting Customer Subscription to Term Deposit using Neural Network](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#predicting-term-deposit-subscription-with-neural-networks-sas)

  - Python
  - Excel / Google Sheets
  - SQL
    - [Basic Statistics & Clean Data](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#basic-statistics--clean-data)
    - [Cohort Analysis](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#cohort-analysis)
    - [Segmentation Analysis](https://github.com/jiainho/Data-Analysis-Portfolio#Segmentation-Analysis)
    - [Mini exercise to Extract and Explore data](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#mini-exercise-to-extract-and-explore-data)

  - Power BI
    - [Churn Analysis Dashboard](https://drive.google.com/drive/folders/1Csc8aF8-dy4SjkVRHVkQb784VLGPkQSn)
    - [Competitive Analysis](https://drive.google.com/drive/folders/1Csc8aF8-dy4SjkVRHVkQb784VLGPkQSn)  

  - End-to-end Project: [Highland Coffee | Brand Funnel, Churn Prediction & Segmentation](https://github.com/jiainho/Data-Analysis-Portfolio?tab=readme-ov-file#highland-coffee--brand-funnel-churn-prediction--segmentation)

- [Education](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#education)  
- [Certificates](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#contacts)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Highland Coffee | Brand Funnel, Churn Prediction & Segmentation
**Access:** 
[`PDF Report`](https://drive.google.com/file/d/1-iIL5KIf9G9wOxRqZiIeSLU_MxpxNkqx/view?usp=sharing)
[`Source Files`](https://drive.google.com/file/d/1pUJADw4IOoNVOojtdo6h8P3hXadFe1tA/view?usp=sharing)
[`Power BI Dashboard`](https://drive.google.com/drive/folders/1Csc8aF8-dy4SjkVRHVkQb784VLGPkQSn)

**Goal:** 
- Brand Funnel Analysis: Evaluate awareness, consideration, purchase, and loyalty stages for Highland vs. competitors.
- Churn Analysis: Identify high-risk segments using behavioral, perceptual, and demographic patterns.
- Customer Segmentation: Use clustering to group customers based on key attributes.
Churn Prediction: Build a machine learning model to predict which customers are likely to churn.

**Description:** This project was developed as part of the Business Intelligence 9 competition. We analyzed customer data from Highland Coffee to uncover brand performance insights, segment customer behavior, and build a churn prediction model to improve customer retention.

**Technology:** 
- SQL: Data cleaning, feature engineering, churn flag logic.
- Power BI: Dashboard for churn rate and brand funnel visualization with drill-down analysis.
- Python: K-means clustering and classification models for churn prediction.

**Results:** 
- Highland Coffee shows high awareness but lower loyalty than its competitors, suggesting issues in conversion and retention.
- Churn rate is higher among passive customers who visit during weekdays and are price-sensitive.
- Segmentation identified distinct clusters based on age, visit time, brand perception, and need states.
- A decision tree classifier achieved [insert metric] accuracy in identifying likely churners.

**Dashboard Preview:** 
- Churn rate by segment, age, need states, daypart
- Drill-down from NPS group to customer-level insights
- Brand funnel comparison vs. competitors
- Strategic recommendation visuals


### Predicting Term Deposit Subscription with Neural Networks (SAS)

**Goal:** To build a neural network model that predicts whether a bank client will subscribe to a term deposit, using demographic and behavioral data collected from previous marketing campaigns.

**Process:** [`Predicting Term Deposit Subscription`](https://github.com/jiainho/DA01_sql/wiki/SAS_Projects)

**Description:** The data set, Bank, is made available by the UCI Machine Learning Repository, and includes information about the clients of a bank and the bank’s marketing efforts for a “term deposit” subscription. The data are from a Portuguese bank. Each row in the data set pertains to one client. There is a total of 9,280 clients in the data set. Predict whether a client opened a term deposit (coded as 1) or not (coded as 0).


**Skills:**
- Neural Network Modeling (AutoNeural & Manual settings)
- Model Optimization (Hidden Units, Training Iterations, Backpropagation)
- Misclassification Rate & Model Evaluation
- SAS Enterprise Miner Workflow Design
- Overfitting Diagnosis & Model Comparison


**Technology:** SAS Enterprise Miner 15.2

**Results:** 
- Final model achieved a Validation Misclassification Rate of 26.36%, significantly outperforming the 50% baseline.
- No evidence of overfitting was detected — model performance was consistent across Training, Validation, and Test sets.
- Manual tuning (number of hidden units, optimization method) performed better than AutoNeural default settings.



### Netflix User base Analysis: Revenue Insights and Strategies
**Proposal:** [`Netflix User base Analysis`](https://drive.google.com/file/d/1rnhEBWeJ8lmafz2HJNm5ImjbXLQzvAeb/view?usp=sharing)

**Goal:** What are the key factors influencing monthly revenue among Netflix users, and how do user characteristics differ across subscription types?

**Description:** This project analyzes user data from Netflix to draw meaningful insights about viewer profiles, preferred genres, and subscription trends. Using Distribution Analysis and Linear Regression model, we aim to support Netflix’s marketing and content strategy decisions.

**Skills:** Demographic segmentation, Exploratory data analysis (EDA), Correlation matrix and behavioral clustering, Data storytelling and strategic insight generation

**Technology:** SAS Enterprise Guide

**Key Findings:**
- Young adults (ages 18–34) form the majority of frequent users, with a strong preference for action and thriller genres.
- There’s a positive correlation between monthly watch time and customer retention.
- Personalized content recommendations could significantly boost engagement across age groups.


### Retail Customer Behavior Analysis
**Proposal:** [`Retail Customer Behavior Analysis`](https://drive.google.com/file/d/1ll9fpKqcXbKGV-rWkhDAFV7rZHL9kT_a/view?usp=sharing)

**Goal:** To understand customer purchasing behaviors and preferences by examining the influence of age, gender, transaction, patterns, and seasonal trends

**Description:** This project explores retail sales data to uncover patterns in customer behavior and key drivers of revenue. Using Linear Regression, decision tree and mode comparison model, we aim to help retailers make informed decisions on which product categories or customer segments drive the most value.

**Skills:** Data cleaning & preprocessing, Correlation analysis, Hypothesis testing, Exploratory data analysis (EDA), Data visualization & insight communication

**Technology:** SAS Enterprise Miner 15.2

**Results:**
- Certain product types and customer segments show strong correlations with high sales volume.
- Seasonal purchasing behavior and spending patterns were evident through time-series visualizations.
- Insights can support inventory management, marketing focus, and customer targeting strategies.


### Basic Statistics & Clean Data

**Code:** [`Basic Statistics & Clean Data`](https://github.com/jiainho/DA01_sql/blob/main/Project%2001.sql)

**Description:** This project was developed as a classroom practical exercise to apply fundamental SQL techniques in data cleaning and preparation. The goal was to create a cleaned version of a retail sales dataset for further RFM (Recency-Frequency-Monetary) analysis.

**Skills:** ALTER, UPDATE, ADD COLUMN, CASE, string functions

**Technology:** PostgreSQL

### Cohort Analysis 

**Code:** [`Cohort Analysis`](https://github.com/jiainho/DA01_sql/blob/main/Project%202.sql)
**Chart cohort final:** [`Cohort chart`](https://docs.google.com/spreadsheets/d/1KT6kU-WSc6_qrohmylYGuGhpAznP0vwb/edit?usp=sharing&ouid=113831551563412238237&rtpof=true&sd=true)

**theLook eCommerce dataset:**[`dataset`](https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce?q=search&referrer=search&project=sincere-torch-350709&pli=1&inv=1&invt=Ab3Lnw)

**Description:** Ecommerce Dataset: Exploratory Data Analysis (EDA) and Cohort Analysis in SQL

**Skills:** SQL Querying (Advanced SQL):
- SELECT, WHERE, GROUP BY, ORDER BY
- Aggregation functions: COUNT(), SUM(), AVG(), MAX(), MIN()
- Window functions: DENSE_RANK() for ranking top products
- String & Date functions: FORMAT_DATE(), DATE_TRUNC(), EXTRACT(), etc.
- UNION: combine queries (e.g., youngest + oldest customers)
- Subqueries and CTEs: for cleaner and modular logic
- Creating VIEWs

**Technology:** PostgreSQL


### Mini exercise to Extract and Explore data
[`Code file 1`](https://github.com/jiainho/DA01_sql/blob/main/Day3_baitap.sql)
[`Code file 2`](https://github.com/jiainho/DA01_sql/blob/main/Day5_baitap.sql)
[`Code file 3`](https://github.com/jiainho/DA01_sql/blob/main/Day9_baitap.sql)
[`Code file 4`](https://github.com/jiainho/DA01_sql/blob/main/MID-TERM.sql)
[`Code file 5`](https://github.com/jiainho/DA01_sql/blob/main/Buoi11_baitap.sql) 
[`Code file 6`](https://github.com/jiainho/DA01_sql/blob/main/buoi12_baitap.sql)
[`Code file 7`](https://github.com/jiainho/DA01_sql/blob/main/Buoi%2015_baitap.sql) 
[`Code file 8`](https://github.com/jiainho/DA01_sql/blob/main/Buoi16_Baitap.sql)

Skills: Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types

Technology: PostgreSQL




## Education
SolBridge International School of Business - South Korea: 
Business Administration - Data Analysis, Accounting & Finance,
Expected in 06/2026
- GPA: 4.5/4.5
- 100% tuition scholarship from Dean's List - Spring 2025, Fall 2025 [Dean's List Invitation](https://drive.google.com/file/d/1pVzHXwr4ZGK0FyI1wmn9QgjNLTKFF_DY/view?usp=sharing)

Foreign Trade University - HCM City, Viet Nam:
Business Administration
2022 - 2024


## Certificates
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have:
- SAS Certified Specialist: Machine Learning Using SAS (SAS Institute)
           - Certified in supervised learning, data sources, building models & model assessment and deployment using SAS tools
- AI & Digital Forensics Certification (PAMS) [Research Topic](https://drive.google.com/file/d/1M_T-7wYfzrN_FBYQrGfy0ZpiAHynI2Q1/view?usp=sharing)  [Cert](https://drive.google.com/file/d/1tf87bdd9cdybkZE_sQiPBM0c1Pbflzm5/view?usp=sharing)    
           - Practical knowledge in AI-driven incident response, cybersecurity & digital evidence handling

## Contacts
- LinkedIn: [@jiainho](https://www.linkedin.com/in/jiainho/)
- Email: jiainho.work@gmail.com
- Facebook: [@jiainho](https://www.facebook.com/jiainho/)
