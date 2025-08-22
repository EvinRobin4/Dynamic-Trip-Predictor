Dynamic Trip Predictor
Overview

This project predicts bike trip durations using the Divvy bike-sharing dataset. Divvy is a bike-sharing company based in Chicago, and the dataset used here is the official open-source trip data published on their website.

I collected four quarters of trip data and merged them into a single dataset. The following steps were performed:

Exploratory Data Analysis (EDA) to identify patterns and trends.

Data cleaning to handle missing and inconsistent values.

Outlier treatment using the Interquartile Range (IQR) method.

Data visualization to uncover insights about trip durations and user behavior.

Linear Regression modeling to predict trip duration, achieving an accuracy of approximately 70%.

Features

Comprehensive Exploratory Data Analysis with trend visualizations.

Data Cleaning and Preprocessing.

Outlier Detection using the IQR method.

Linear Regression model for trip duration prediction.

Tech Stack

Python (NumPy, Pandas for preprocessing)

Matplotlib and Seaborn for visualizations

Scikit-learn for regression modeling

Jupyter Notebook for implementation

Results

Model Accuracy: ~70%

Maximum number of trips occurred in August.

Minimum number of trips occurred in February.

Users aged 25–30 years made the most trips.

The analysis and visualizations provide insights into:

Peak trip times and durations

Seasonal and quarterly usage trends

How factors like user type and time of day affect trip duration
