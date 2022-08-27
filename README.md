# Python Project 3: HR Analytics Case Study 

**Author**: Chinh X. Mai, **Date**: August 24, 2022

![image](https://user-images.githubusercontent.com/89245616/187050037-2b64801d-6a18-4873-ae45-433016659e43.png)

## Project description

A large company named XYZ, employs, at any given point of time, around 4000 employees. However, every year, around 15% of its employees leave the company and need to be replaced with the talent pool available in the job market. The management believes that this level of attrition (employees leaving, either on their own or because they got fired) is bad for the company, because of the following reasons -

The former employees’ projects get delayed, which makes it difficult to meet timelines, resulting in a reputation loss among consumers and partners A sizeable department has to be maintained, for the purposes of recruiting new talent More often than not, the new employees have to be trained for the job and/or given time to acclimatise themselves to the company Hence, the management has contracted an HR analytics firm to understand what factors they should focus on, in order to curb attrition. In other words, they want to know what changes they should make to their workplace, in order to get most of their employees to stay. Also, they want to know which of these variables is most important and needs to be addressed right away.

Since you are one of the star analysts at the firm, this project has been given to you.

## Goal of the case study

You are required to model the probability of attrition using a logistic regression. The results thus obtained will be used by the management to understand what changes they should make to their workplace, in order to get most of their employees to stay.

Reference: [Kaggle HR Analytics Case Study](https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study?select=in_time.csv)

## Executive summary

In this analysis, a logistic model is used to analyze the impacts of many fators on the attrition in order to understand what makes employees quit their job. The analysis employs `numpy`, `pandas`, `statsmodels`, and `plotly` as the main packages and the main steps include importing and wrangling data, linear regression, model validation, and interpretation of the results. The data includes 6 different tables including information about employees and managers as well as their working time, the final table consists of around 4,400 observations and 26 variables. The regression analysis shows that

* `Average_duration_hr`, `BusinessTravel`, and `JobRole_Research` Director are the main factors that increase the attrition probability
* `WorkLifeBalance`, `JobSatisfaction`, and `EnvironmentSatisfaction` are the main factors that help reduce the attrition probability

Furthermore, this model is also good for predicting attrition rate with an out-of-sample accuracy of approximately 86 percents. In conclusion, the attrition rate is well explained and predicted by the employed model.
