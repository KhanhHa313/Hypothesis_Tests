# 📱 Social Media Usage & Stress Level Analysis

## 📌 Overview

This project investigates the relationship between social media usage and stress levels using statistical hypothesis testing and regression modelling. The analysis examines group differences, identifies key predictors of stress, and evaluates whether demographic and socioeconomic factors improve predictive performance.

## 🛠️ Tools & Technologies

* Python (Pandas, NumPy, SciPy, Statsmodels)
* Matplotlib & Seaborn 
* Pingouin

## 📂 Dataset

* Kaggle dataset on social media usage and stress levels (1.5+ million)
* Includes demographic information (e.g., age, socioeconomic status)
* Records time spent on social media features such as Explore, Feed, and Sessions
* Contains stress and happiness level measurements (self-measured) and user characteristics

## 🔍 Key Analysis

* Tested statistical assumptions using the D'Agostino-Pearson normality test and Levene's test
* Compared stress levels between groups using Independent t-tests, Mann-Whitney U tests, effect size measures, and bootstrap confidence intervals
* Built multiple OLS regression models to predict stress levels from social media usage variables
* Evaluated regression assumptions through residual analysis and partial regression plots
* Investigated whether demographic variables, particularly age, improved predictive performance
* Examined differences in stress levels across socioeconomic groups using the Kruskal-Wallis test and Holm-corrected post-hoc comparisons

## 📈 Key Insights

* Significant differences in stress levels were identified between the compared groups, supported consistently by parametric, non-parametric, effect size, and bootstrap analyses
* Time spent on **Explore**, **Feed**, and **Sessions** explained approximately **67%** of the variation in stress levels, making them strong predictors of stress
* **Age** was the only additional demographic variable that significantly improved the regression model, increasing the explained variance to over **69%** when combined with social media usage variables
* Socioeconomic status did not show an overall significant relationship with stress levels, although one post-hoc comparison suggested a difference between the **Low** and **Middle** income groups that should be interpreted cautiously
