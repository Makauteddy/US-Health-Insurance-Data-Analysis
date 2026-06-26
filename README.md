# US-Health-Insurance-Data-Analysis
## 1. Introduction

The health insurance industry relies heavily on data analytics to understand customer risk, optimize premium pricing, and improve underwriting decisions. By analyzing demographic, lifestyle, and health-related factors, insurers can identify key drivers of medical costs and develop more accurate pricing strategies.



## 2. Project Description

This project performs an end-to-end analysis of a US health insurance dataset using Python. The analysis includes data cleaning, exploratory data analysis (EDA), business intelligence reporting, statistical hypothesis testing, and multiple linear regression modeling to identify the major factors affecting insurance charges.

The project demonstrates how data analytics can support insurance companies in improving underwriting accuracy, pricing policies appropriately, identifying high-risk customer segments, and enhancing profitability through data-driven decision-making.

## 3. Business Problem

Health insurance providers face the challenge of accurately estimating customer risk while maintaining competitive premium pricing. Incorrect risk assessment may lead to financial losses, adverse selection, and reduced profitability.

## 4. Data Description

The dataset contains 1,338 customer records and 7 variables, with no missing values.


Age: 	Age of the insured individual

Sex: Gender of the insured

BMI: Body Mass Index

Children: Number of dependents covered

Smoker: Smoking status (Yes/No)

Region: Residential region in the United States

Charges: Individual medical insurance charges

## 5. Objectives and Research Questions
#### 5.1 Project Objectives
1. Perform data cleaning and preprocessing.   
2. Explore the demographic and health characteristics of insured customers.
3. Identify factors influencing insurance charges.
4. Answer key business questions through descriptive analytics.
5. Validate relationships using statistical hypothesis testing.
6. Develop a multiple linear regression model to predict insurance charges.
7. Generate actionable recommendations for underwriting and pricing strategies.
   
#### 5.2 Research Questions
1. What is the average insurance charge?
2. Which age group contributes the highest premium revenue?
3. What percentage of customers are smokers?
4. How much more do smokers pay than non-smokers?
5. Which region generates the highest insurance charges?
6. Does obesity significantly affect insurance costs?
7. Does family size influence insurance premiums?
8. Which customer segment poses the highest financial risk?

## 6. Findings and Results

1. The customer portfolio is dominated by young adults aged 18–20, while the remaining age groups are evenly distributed across the dataset.
2. Most policyholders have a BMI around 30, indicating that a large proportion of customers fall within the overweight to obese range.
3. Insurance charges are highly right-skewed, with most customers incurring relatively low medical costs and a smaller group generating exceptionally high claims.
4. The customer base is almost equally split between males and females, suggesting balanced gender representation across policyholders.
5. Approximately 20.49% of policyholders are smokers, while nearly four out of five customers are non-smokers.
6. The southeast region has the largest customer population and generates the highest total insurance charges, making it the most costly region in the portfolio.
7. Medical charges generally increase with age, with older customers experiencing substantially higher healthcare costs than younger customers.
8. Customers with a BMI above 30 are more likely to incur significantly higher insurance charges, indicating obesity as an important cost driver.
9. Smoking is the strongest determinant of insurance costs, with smokers paying an average of $32,050.23 compared to $8,440.66 for non-smokers, a difference of $23,609.57.
10. Obese customers incur average medical charges of $15,580.70, approximately 49% higher than customers with a normal BMI.
11. Premiums generally increase as family size grows from zero to three children before declining among larger families, suggesting that family size alone is not a consistent predictor of insurance costs.
12. Customers aged 46–60 contribute the highest total premium revenue, generating approximately $6.68 million in insurance charges.
13. The highest-risk customer segment comprises smokers aged 60 years and above, with average medical charges of $38,929.62, followed by smokers aged 46–60.
14. Correlation analysis shows that smoking status has the strongest positive relationship with insurance charges, while age and BMI have moderate positive relationships and gender and number of children have minimal influence.

## 7. Recommendations

1. Strengthen risk-based pricing by incorporating smoking status, age, and BMI more prominently into premium calculations, as these variables have the greatest impact on medical costs.
2. Invest in smoking cessation programs by offering premium discounts, wellness incentives, or cessation support to reduce long-term claims and improve customer health outcomes.
3. Introduce obesity and preventive health initiatives, such as weight management programs, nutrition counseling, and fitness incentives, to lower healthcare costs among high-BMI customers.
4. Enhance underwriting strategies for older policyholders, particularly smokers aged 46 years and above, through more comprehensive health assessments and tailored risk management practices.
5. Review regional pricing and healthcare partnerships in the southeast, where the highest total insurance charges occur, to improve cost control and optimize provider networks.
6. Develop targeted retention strategies for middle-aged customers (46–60 years), as they contribute the highest premium revenue and represent a valuable customer segment.
7. Expand preventive care benefits for younger customers to encourage healthier lifestyles early, potentially reducing future claims as they age.
8. Continuously monitor high-risk customer segments using predictive analytics and machine learning models to identify customers likely to generate high future claims and enable proactive intervention.
9. Use data-driven underwriting models that combine smoking status, BMI, age, and historical claims to improve pricing accuracy, profitability, and overall risk assessment.
10. Regularly evaluate product offerings for families since insurance costs do not increase consistently with additional children, indicating opportunities to refine family-based pricing structures.
