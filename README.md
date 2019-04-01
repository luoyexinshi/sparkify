# Sparkify Capstone Project

## Overview
This project manipuated large and realistic data set with Spark to predict customer churn, which is one of the most important decision the business such as Spotify, Pandora would like to investigate.

The data provided has each user's log, which includes variables such as artist, first name and last names, gender, length, level, location, page, registration, session ID, song, status, ts, user ID.

I constructed the customer churn as users who canceled the service, and I plotted the number of songs for users who canceled the service and users who stayed. And I noticed that users who canceled the service listen to significantly less songs than users who stayed. Then I also plotted the number of song for users who downgraded and the users who did not downgrade, because downgrading is correlated with the possibility of canceling the service. And similar pattern also exists, that users who downgraded listened to significantly less song than users who did not downgrade. Hence, it's important for Sparkify to to attract users to use their service more to avoid customer churn.

More detailed explanation can be found here.

## Packages:
PySpark, Pandas, Matplotlot.pylpot

## Models:
Logistic Regression, Gradient Boosted Trees, Support Vector Machine

## Methodology:
  1. ETL
  2. Exploratory Data Analysis
  3. Feature Engineering
  4. Model Building
  5. Model Evaluation
