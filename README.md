# Kaggle-M5-Forecasting
To get further information of this Kaggle competition, please check: https://www.kaggle.com/c/m5-forecasting-accuracy

Goal:
The goal of this project is to estimate the unit sales of Walmart retail goods to support their strategic development and plan demand for the supply chain. This will be achieved through exploratory data analysis, feature engineering, and modeling.

Exploratory Data Analysis:
The exploratory data analysis will include analyzing the sales trend by state, store, category, department, and rolling mean. Additionally, we will examine the price trend by calculating the average price, and we will analyze the calendar distribution.

Feature Engineering:
To enhance the predictive power of the model, we will perform feature engineering by extracting event-related features such as event count, post-event, pre-event, and type. Additionally, we will analyze price-related features such as mean and unique items, and sales-related features such as lag and rolling mean in different periods. We will also identify the top 20 important features in three states.

Modeling:
We will use LightGBM, inspired by the MLForecast function, to predict sales of 45 stores in three states (WI, CA, TX). To generate the final result, we will train four models with different features and store/state combinations. We will then ensemble these four models to obtain a new score.

Result:
The success of the project will be measured by achieving a private score of 0.56337.
