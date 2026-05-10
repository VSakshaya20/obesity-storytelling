# Why Are We Getting Heavier? Understanding Obesity Beyond the Numbers

This project was developed as part of IS630 — Statistical Thinking with Data Science coursework for our Master of IT in Business programme at Singapore Management University.

A data storytelling project that explores obesity through demographic, dietary, and lifestyle factors. The goal is to go beyond headline statistics and explain the patterns behind obesity levels in a clear and accessible way.

## Overview

This project investigates the relationship between obesity and several factors related to demographics, diet, and lifestyle. Using statistical testing and logistic regression, the analysis examines which variables are associated with obesity levels and how these relationships can be interpreted in context.

The final story is also published on Medium:
[Why Are We Getting Heavier? Understanding Obesity Beyond the Numbers](https://medium.com/@akshaya.v.s/why-are-we-getting-heavier-understanding-obesity-beyond-the-numbers-e4541c8cd18e)

## Problem Statement / Objective

The objective of this project is to identify factors associated with obesity and present the findings in a way that is easy to understand for a wider audience. The project aims to provide insights that can support awareness and decision-making for relevant stakeholders.

## Dataset / Inputs

The project uses the 2019 obesity [dataset](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition) by Palechor and De la Hoz Manotas, which covers obesity levels and lifestyle habits in Colombia, Peru, and Mexico.

- Number of records: 2,111
- Number of attributes: 17
- Target variable: Obesity Levels (7 groups)

The dataset includes:
- Demographic variables such as age, gender, height, weight, and family history of overweight.
- Dietary habits such as high-calorie food consumption, vegetable intake, number of main meals, and eating between meals.
- Lifestyle behaviours such as smoking, physical activity, technology use, alcohol consumption, water intake, calorie monitoring, and mode of transportation.

## Tools and Libraries

- Python for data analysis and modeling.
- Jupyter Notebook for exploratory work and documentation.
- Pandas and NumPy for data cleaning, preparation, and exploratory data analysis.
- SciPy and Statsmodels for statistical tests and regression analysis.
- Matplotlib, Seaborn, and Plotly for data visualization.

## Key Features / Methods

- Data type checking and cleaning.
- Removed synthetic records.
- Feature engineering, including creation of BMI categories.
- Descriptive statistics for participant, dietary, and lifestyle profiles.
- Mann-Whitney U test.
- Kruskal-Wallis test.
- Chi-square test.
- Logistic regression for obesity classification.
- Summary of insights across demographic, dietary, and lifestyle categories.

## Main Results / Findings

The analysis found several significant associations with obesity:
- Older individuals were more likely to be in the obese group.
- Family history of overweight was associated with higher obesity risk.
- Physical activity was linked to lower obesity risk.
- Smoking and technology use were also associated with obesity.
- Regular eating patterns appeared to be associated with lower odds of obesity.

The logistic regression model achieved about 70% accuracy, but it performed better at identifying non-obese cases than obese cases.

## Team Members and Role

- Akshaya Vijayakumar Sivakami: Data preparation, logistic regression coding
- Carina Faith Peh Xin Yi: Chi-square test coding
- Gyanada Chowdary Myneni: Mann-Whitney U test and Kruskal-Wallis test coding
- He Xiaoyi: Data preparation and descriptive statistics coding
- Lei Yuhe: Mann-Whitney U test and logistic regression coding
- Zhou Ziying: Descriptive statistics coding
