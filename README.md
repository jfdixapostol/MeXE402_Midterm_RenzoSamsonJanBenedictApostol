# <h1 align="center">MeXE402_Midterm_RenzoSamson_JanBenedictApostol</h1>

<h1 align="center">Midterm Activity: Linear and Logistic Regression</h1>
<br>

## Table of Contents
  - [I. Introduction](#i-introduction)
  - [II. Dataset Overview](#ii-dataset-overview)
  - [III. Project Objectives](#iii-project-objectives)
  - [IV. Pair](#iv-pair)
  - [V. References](#v-references)
<hr> 
<br>

## I. Introduction

<p align="justify"> 
This project highlights the two fundamental statistical techniques commonly used in data analysis and machine learning, these are the linear regression and logistic regression. 

<p align="justify"> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Let us differentiate the two, first we define what is <i><b>Linear Regression</i></b>, is used to predict the value of a variable based on the value of another variable. The variable that needed to predict is called the dependent variable. The variable that is used to predict the dependent variable is called the independent variable. <i></i>Linear Regression<b></b> models interpret mathematical formula that can generate predictions different datasets. Linear regression can be applied to various areas such as business and even academic study.

<h3><i>Linear Regression : Salary Dataset</h3></i>

<p align="justify"> 
  
  - **Objective**: Use linear regression to analyze and predict salaries based on relevant factors.
  - **Dataset Source**: Collected from various sources, including surveys, job postings, and publicly available databases.
  - **Total Data Points**: 6,704.
  - **Goal**: Build a linear regression model to explore relationships between personal/professional attributes and salary.

<p align="justify"> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On the other hand, <i><b>Logistic Regression</i></b>, it uses the logistic function to model the probability that a given input point belongs to a particular class. Instead of using regression for classification problems, logistic regression is used. It is a method for predicting results that fall into one of two categories, like yes or no, or success or failure, which are represented by 0 or 1.

<h3><i>Logistic Regression : Bank Marketing Dataset</h3></i>
<p align="justify"> 

  - **Objective**: Utilize data from a previous bank telemarketing campaign to predict its success.
  - **Project Title**: *"A Data-Driven Approach to Predict the Success of Bank Telemarketing."*
  - **Dataset**: Sourced from the UCI Machine Learning Repository, containing customer interactions and campaign details.
  - **Goal**: Build a logistic regression model to identify patterns for improved marketing strategy.
<br>
  
## II. Dataset Overview

<h3><i>Linear Regression : Salary Dataset</i></h3>

<p align="justify"> 
  
  - **Variables**:
  - **age**: Age of the individual.
  - **experience**: Years of relevant work experience.
  - **job_role**: Title or designation (e.g., Software Engineer, Data Analyst).
  - **education_level**: Highest level of education completed.
  - **salary**: Annual salary, target variable for prediction.

For more detailed information, you may click [link](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data)

<h3><i>Visual Representation for Linear Regression Dataset</h3></i>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/9197f300913ebb57ae4116aa114d8bf84b7ac70b/Linear_Regression/Educational%20Attainment.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.1.1: Educational Attainment vs Salary</b></i>
</p>
  
<p align="center">
<i>We can see that the people that has a PhD most likely to gain the highest salary. And those with the lowest are High School as their Education Level.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/ac500cc18d3c2757305f6d2f1c03a4ac1530acf6/Linear_Regression/Plot%20of%20Age%20vs%20Salary.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.1.2: Age vs Salary</b></i>
</p>
  
<p align="center">
<i>Based on the graph above, we can see that the higher the age, the higher their salary is.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/ac500cc18d3c2757305f6d2f1c03a4ac1530acf6/Linear_Regression/Plot%20of%20Years%20of%20Experience%20vs%20Salary.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.1.3: Comparison of Years of Experience and their Salary Based on ther Educational Attainment</b></i>
</p>
  
<p align="center">
<i>We can see that the more they gain experience throughtout the years, the higher their possible salary is.</i>
</p>
<br>

<h3><i>Logistic Regression : Bank Marketing Dataset</h3></i>
<p align="justify"> 
  
- **Client Information**:
  - **age**: Client’s age.
  - **job**: Type of job (e.g., admin, blue-collar).
  - **marital**: Marital status (e.g., married, single).
  - **education**: Level of education.
  - **default**: Has credit in default.
  - **balance**: Client’s account balance.
  - **housing**: Has a housing loan.
  - **loan**: Has a personal loan.
  
- **Campaign Information**:
  - **contact**: Type of contact (e.g., cellular, telephone).
  - **day**: Day of last contact.
  - **month**: Month of last contact.
  - **duration**: Duration of last contact in seconds.
  - **campaign**: Number of contacts in the campaign.
  - **previous**: Number of contacts before the campaign.
  - **poutcome**: Outcome of the previous campaign.

- **Target Variable**:
  - **y**: Client's subscription to a term deposit (yes or no).
 
<h3><i>Visual Representation for Logistic Regression Dataset</h3></i>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/6c423c28d04d3a9436574969e754e6356b33d701/Logistic_Regression/Job%20vs%20Campaign%20Success.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.1: Job vs Campaign Success</b></i>
</p>
  
<p align="center">
<i>We can see that customers with job type as 'student' or 'retired' tends to accept the deposit, while 'blue collars' largely refused the deposit.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/062c780c274af827ce53a45da22afde808093aec/Logistic_Regression/Loan%20vs%20Campaign%20Success.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.2: Loan vs Campaign Success</b></i>
</p>
  
<p align="center">
<i>Customers with a personal loan tends to refuse the deposit.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/062c780c274af827ce53a45da22afde808093aec/Logistic_Regression/Housing%20vs%20Campaign%20Success.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.3: Housing vs Campaign Success</b></i>
</p>
  
<p align="center">
<i>Customers without a Housing Loan tends to accept the deposit.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/062c780c274af827ce53a45da22afde808093aec/Logistic_Regression/Month%20vs%20Campaign%20Success.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.4: Month vs Campaign Success</b></i>
</p>

<p align="center">
<i>The graph above shows the customers tends to accept more the deposit on march, april, september and october.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/062c780c274af827ce53a45da22afde808093aec/Logistic_Regression/Poutcome%20vs%20Campaign%20Success.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.5: Poutcome vs Campaign Success</b></i>
</p>

<p align="center">
<i>The graph above shows the customers who previously accepted the deposit tends to accept the deposit by a large margin.</i>
</p>

<p align="center">
<img src=https://github.com/jfdixapostol/MeXE402_Midterm_RenzoSamsonJanBenedictApostol/blob/062c780c274af827ce53a45da22afde808093aec/Logistic_Regression/Balance%20vs%20Age%20by%20Deposit.jpg style="height: 500px; float: center;">
</p>

<p align="center">
<b><i>Figure 2.2.6: Comparison in between Balance and Age by Deposit</b></i>
</p>

<p align="center">
<i>The graph above shows that we can see the older customers tends to have a higher bank balance and the customers who accepted the deposit tended to have a higher balance compared to the customers who refused the deposit.</i>
</p>
  
<br>
  
## III. Project Objectives

<h3><i>Linear Regression : Salary Dataset</h3></i>
<p align="justify"> 
  
  - **Predictive Modeling**: Develop a linear regression model to predict salary.
  - **Feature Analysis**: Identify the variables with the most significant impact on salary.
  - **Insights Generation**: Provide recommendations based on the model to inform salary expectations and career planning.
<br>

<h3><i>Logistic Regression : Bank Marketing Dataset</h3></i>
<p align="justify"> 

- **Predictive Modeling**: Use logistic regression to predict client subscription.
- **Feature Analysis**: Determine key factors affecting the likelihood of subscription.
- **Strategy Recommendations**: Generate actionable insights to improve future campaigns.
<br>

## IV. Pair:
- Samson, Renzo M.
- Apostol, Jan Benedict D.

## V. References
<p align="justify">
  
- Salary Data. (n.d.). M. S. R. Reddy, J. G. Sukumar, N. Sambangi. https://www.kaggle.com/datasets/mohithsairamreddy/salary-data

- Bank Marketing Dataset. (2017). Janio Martinez Bachmann. https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
<hr>
<br>
