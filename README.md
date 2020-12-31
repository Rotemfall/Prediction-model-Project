# Prediction-model-Project


•	Developed using python – pandas, numpy, matplotlib, sklearn, seaborn.

Salary Prediction Project (Python)

# Methods Used
Data Analysis and Visualization
Linear Regression
Polynomial Transformation
Ridge Regression
Random Forest

# Technologies/Libraries Used
Python 3
Pandas
NumPy
Seaborn
Scikit-learn
Matplotlib
SciPy
Jupyter

# Description
The purpose of this project is to use data cleaning & transformation and create prediction models based on different algorithms and properties from the machine learning world in order to find the best way to predict a individual salary.


# Data
The data for this model is fairly simplified as it has very few missing pieces. The raw data consists of a training dataset with the features listed above and their corresponding salaries. Twenty percent of this training dataset was split into a test dataset with corresponding salaries.

There is also a testing dataset that does not have any salary information available and was used as a substitute for real-world data.

# Information Used To Predict Salaries
Years Experience: How many years of experience
Job Type: The position held (CEO, CFO, CTO, Vice President, Manager, Janitor, and senior or junior position)
College Degree: Doctoral, Masters, Bachelors, High School, or None
College Major: Biology, Business, Chemistry, Computer Science, Engineering, Literature, Math, Physics, or None
Industry: Auto, Education, Finance, Health, Oil, Service, or Web
Miles From Metropolis: How many miles away from a major city

# Summary
Applying second order polynomial transformation to the features used gave the most accurate predictions with the least error when using a linear regression model. The result was a mean squared error of 354 with a 76% accuracy rate.

This model can be used as a guide when determining salaries since it shows reasonable predictions when given information on years of experience, miles from metropolis, job type, industry, and college degree and major.
