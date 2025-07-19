# Ho Nguyen Gia Linh - Data Analyst Portfolio
## About
Hi, I'm Linh! I’m a final-year Business Administration student specializing in Data Analysis and Accounting & Finance, with a deep interest in using data to drive strategic decision-making and improve business performance. With a strong foundation in analytics and hands-on experience from academic projects and competitions, I’m eager to start my career as a Financial Data Analyst or Data Specialist.

Throughout my journey, I’ve applied tools like SQL, Python, Power BI, Excel, and SAS to conduct meaningful analysis—from predicting customer churn to visualizing performance KPIs for business growth. My background combines both the technical side of data analytics and the financial understanding of business operations, allowing me to interpret complex datasets and translate them into actionable insights.

Beyond the classroom, I’ve worked as a Research Assistant, supported business case competitions, and led communication campaigns using data to improve audience engagement. I’m constantly exploring new tools and sharpening my skills, driven by curiosity and a passion for uncovering patterns that inform smarter decisions. Whether working independently or collaborating in a cross-functional team, I’m motivated by the challenge of transforming data into impactful outcomes.


My CV in [pdf](https://drive.google.com/file/d/1rnv6kYaxM7cAns3IPKJWFHA8WAx9wzR8/view?usp=sharing).

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents
- [About](https://github.com/tiannaparris/Data-Analysis-Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/tiannaparris/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)
  - SAS - Machine Learning
    - [Retail Customer Behavior Analysis](https://drive.google.com/file/d/1ll9fpKqcXbKGV-rWkhDAFV7rZHL9kT_a/view)
    - [Netflix user base Analysis](https://drive.google.com/file/d/1rnhEBWeJ8lmafz2HJNm5ImjbXLQzvAeb/view?usp=sharing)
    - [Predicting Customer Subscription to Term Deposit using Neural Network](https://github.com/jiainho/DA01_sql/wiki/SAS_Projects)

 - Python
- Excel / Google Sheets
  - SQL
    - [Basic Statistics & Clean Data](https://github.com/jiainho/DA01_sql/blob/main/Project%2001.sql)
    - [Cohort Analysis](https://github.com/jiainho/DA01_sql/blob/main/Project%202.sql)
    - [Segmentation Analysis](https://github.com/jiainho/DA01_sql/blob/main/Project%202.sql)
    - [Mini exercise to Extract and Explore data](https://github.com/jiainho/DA01_sql/blob/main/Mini%20exercise%20to%20Extract%20and%20Explore%20data.sql)

  - Power BI
    - [Churn Analysis Dashboard](https://drive.google.com/file/d/1rnhEBWeJ8lmafz2HJNm5ImjbXLQzvAeb/view?usp=sharing)
    - [Competitive Analysis](https://github.com/jiainho/DA01_sql/wiki/SAS_Projects)  

- End-to-end Project: [Highland Coffee | Brand Funnel, Churn Prediction & Segmentation](https://github.com/jiainho/DA01_sql/blob/main/%5BBI9competition%5DHighland%20Coffee%20Analysis.docx%20(1).pdf)


- [Education](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#education)  
- [Certificates](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/jiainho/Data-Analysis-Portfolio/blob/main/README.md#contacts)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Highland Coffee | Brand Funnel, Churn Prediction & Segmentation
**Access:** 
You can view the dashboard, code, and report here:
[`PDF Report`](https://drive.google.com/drive/u/0/folders/1EraYo8K6NqkxSKOsn9hxGKIQNtlACovA)
[`Source Files`](https://drive.google.com/drive/u/0/folders/1EraYo8K6NqkxSKOsn9hxGKIQNtlACovA)
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
**Proposal:** [`Netflix User base Analysis`](https://drive.google.com/drive/u/0/folders/1EraYo8K6NqkxSKOsn9hxGKIQNtlACovA)

**Goal:** What are the key factors influencing monthly revenue among Netflix users, and how do user characteristics differ across subscription types?

**Description:** This project analyzes user data from Netflix to draw meaningful insights about viewer profiles, preferred genres, and subscription trends. Using Distribution Analysis and Linear Regression model, we aim to support Netflix’s marketing and content strategy decisions.

**Skills:** Demographic segmentation, Exploratory data analysis (EDA), Correlation matrix and behavioral clustering, Data storytelling and strategic insight generation

**Technology:** SAS Enterprise Guide
**Key Findings:**
- Young adults (ages 18–34) form the majority of frequent users, with a strong preference for action and thriller genres.
- There’s a positive correlation between monthly watch time and customer retention.
- Personalized content recommendations could significantly boost engagement across age groups.


### Retail Customer Behavior Analysis
**Proposal:** [`Retail Customer Behavior Analysis`](https://drive.google.com/drive/u/0/folders/1EraYo8K6NqkxSKOsn9hxGKIQNtlACovA)
**Goal:** To understand customer purchasing behaviors and preferences by examining the influence of age, gender, transaction, patterns, and seasonal trends

**Description:** This project explores retail sales data to uncover patterns in customer behavior and key drivers of revenue. Using Linear Regression, decision tree and mode comparison model, we aim to help retailers make informed decisions on which product categories or customer segments drive the most value.

**Skills:** Data cleaning & preprocessing, Correlation analysis, Hypothesis testing, Exploratory data analysis (EDA), Data visualization & insight communication

**Technology:** SAS Enterprise Miner 15.2

**Results:**
- Certain product types and customer segments show strong correlations with high sales volume.
- Seasonal purchasing behavior and spending patterns were evident through time-series visualizations.
- Insights can support inventory management, marketing focus, and customer targeting strategies.


### Basic Statistics & Clean Data

**Goal:** To predict Pokémon status based on their characteristics and rank their importance in determining whether a Pokémon is classified as legendary.

**Code:** [`Legendary Pokémon Analysis (Study Project)`](https://github.com/tiannaparris/PortfolioProjects/blob/main/Legendary%20Pok%C3%A9mon%20Analysis.ipynb)

**Description:** The dataset contains a list of  Pokémon.  The records include their characteristics such as attack, defense, type and size. The project includes the following steps: data loading, data cleaning EDA (exploratory data analysis), analyzing characteristics of different Pokémon.

**Skills:** data cleaning, data analysis, data visualization.

**Technology:** Tidyverse 





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
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- SAS Certified Specialist: Machine Learning Using SAS (SAS Institute)
           - Certified in supervised learning, data sources, building models & model assessment and deployment using SAS tools
- AI & Digital Forensics Certification (PAMS) [Research Topic](https://drive.google.com/file/d/1M_T-7wYfzrN_FBYQrGfy0ZpiAHynI2Q1/view?usp=sharing)  [Cert](https://drive.google.com/file/d/1tf87bdd9cdybkZE_sQiPBM0c1Pbflzm5/view?usp=sharing)    
           - Practical knowledge in AI-driven incident response, cybersecurity & digital evidence handling

## Contacts
- LinkedIn: [@jiainho](https://www.linkedin.com/in/jiainho/)
- Email: jiainho.work@gmail.com
- Facebook: [@jiainho](https://www.facebook.com/jiainho/)
