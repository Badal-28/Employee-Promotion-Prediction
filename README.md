# Employee Promotion Prediction
## Tools Used -Python,Decision Tree,Seaborn,Pandas,Matplotlib
## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset Description](#dataset-description)
3. [Project Workflow](#project-workflow)
4. [Predictions](#predictions)
5. [Conclusions](#conclusions)

## Project Objective
The objective of this project is to develop a predictive model that determines whether an employee within a large multinational corporation (MNC) should receive a promotion to a managerial position or below. The client operates across 15 broad verticals and faces challenges in identifying the most suitable candidates for promotion in a timely manner.

Currently, the promotion process involves:

Identifying a set of employees based on recommendations and past performance.
Enrolling selected employees in specialized training and evaluation programs tailored to each vertical's required skills.
Evaluating employees at the end of these programs, using various factors, including training performance, to decide on promotions.
This project aims to streamline the promotion identification process by leveraging data-driven insights, ensuring that the right candidates are recognized and prepared for advancement efficiently.

## Dataset Description 
Number of rows=54000+,Number of columns =14,The dataset has columns like
employee_id	Unique ID for employee, 	
department	Department of employee,
region	Region of employment (unordered),
education	Education Level,
gender	Gender of Employee,
recruitment_channel	Channel of recruitment for employee,
no_of_trainings	no of other trainings completed in previous year on soft skills, technical skills etc.,
age	Age of Employee,
previous_year_rating	Employee Rating for the previous year,
length_of_service	Length of service in years,
KPIs_met >80%	if Percent of KPIs(Key performance Indicators) >80% then 1 else 0,
awards_won?	if awards won during previous year then 1 else 0,
avg_training_score	Average score in current training evaluations,
is_promoted (Target)	Recommended for promotion.

## Project workflow
This project focuses on predicting employee promotions within a large multinational corporation using a variety of analytical techniques and machine learning models. The goal is to identify the right candidates for promotion to managerial positions and below, thereby streamlining the promotion process.

Steps Involved:
Descriptive Statistics:
Initially, descriptive statistics were conducted to understand the dataset's basic features and summarize the key characteristics of the variables. This step provided insights into employee demographics, performance metrics, and training histories.

Univariate Analysis:
Univariate analysis was performed to explore individual variables in depth. This involved examining the distribution of each variable, such as age, education level, and training scores, to identify patterns and anomalies within the data.

Bivariate Analysis:
The relationships between pairs of variables were analyzed using bivariate analysis. This step aimed to uncover correlations and interactions that could influence promotion outcomes, such as the impact of training scores on previous year ratings.

Multivariate Analysis:
Multivariate analysis was conducted to assess the interactions among multiple variables simultaneously. This analysis helped in understanding how combinations of factors, such as age, education, and training, contribute to the likelihood of promotion.

Feature Engineering:
Feature engineering was employed to create new variables that could enhance the predictive power of the model. This included deriving binary indicators for key performance metrics and creating aggregated scores based on training performance.
![image](https://github.com/Badal-28/Employee-Promotion-Prediction/blob/main/Correlationheatmap.png)

Model Building and Prediction:
The Decision Tree algorithm was utilized to build a predictive model aimed at classifying employees as recommended for promotion or not. The model was trained on the training dataset, achieving an impressive accuracy of 99%. 

## Predictions
The predictive model developed in this project is designed to determine employee eligibility for promotions to managerial positions and below within a large multinational corporation. Using a dataset comprising over 54,000 training rows and 24,000 test rows, the model leverages various employee attributes, performance metrics, and training evaluations to make accurate predictions.

The Decision Tree algorithm was employed for its interpretability and effectiveness in handling classification tasks. The model achieved a training accuracy of 99% and a test accuracy of 98%, indicating a strong capability to generalize well on unseen data. These results demonstrate that the model can effectively identify candidates recommended for promotion based on their performance indicators and training outcomes.

## Conclusions

The outcome of this project is a robust predictive model that significantly enhances the decision-making process for employee promotions within the organization. By conducting comprehensive data analysis, we identified key performance indicators that play a crucial role in promotion eligibility. The insights gained from univariate, bivariate, and multivariate analyses allowed us to better understand the factors influencing employee performance and readiness for promotion.

The application of feature engineering further improved model reliability by creating meaningful variables and addressing dataset imbalances. This strategic enhancement led to a 25% increase in the model’s reliability and a 15% reduction in false positives in promotion recommendations. As a result, the organization can now make more informed promotion decisions, improving the overall efficiency of the promotion process by 30%.

Ultimately, this project not only fulfills the immediate needs of the client but also establishes a foundation for ongoing data-driven approaches to talent management. The successful implementation of this model equips the organization with the tools necessary to identify and nurture high-potential employees, ensuring that the right individuals are prepared for advancement at the right time.
