# AIML_PA2_M11_1

Analysis Goal
The analysis goal is to provide the list of data features that impacts the used car price the most using the 426k dataset containing various car attribute data.

Used ML Techniques
CRISP-DM Framework

Within CRISP-DM, followed the steps of business understanding, data understanding, data preparation, modeling and evaluation cycle and finally providng the deployment/report.
Data Understanding - Data Observation Steps

Checked for data info, description, samples, and unique values and value counts first.
Checked for the feature correlation.
Created plots using Seaborn library for visual to understand data more.
Data Prepapration - Data Cleaning Steps

Checked the the data to see if there are any actual data value problems.
Using domain knowledge, saw if there are features that can be eliminated.
Updated data types as needed.
Checked for duplicates and remove.
Checked for nulls and remove with valid reasoning such as proportion of null for the feature is insignicant or significant but feature is absolutely necessary for ML based on the domain knowledge and etc.
If features are remove after removing duplicates, need to check for duplicates again and remove them again.
Modeling - Selecting the Best Model

Did preprocessing using following methods
Used PolynomialFeatures to transform linear to higher degree polinomial combination to capture non-linear relationship
Used OneHotEncoder to make object features to numeric features for better understanding by ML
Used Regression models - Supervised Learning
LinearRegression
Ridge
Lasso
Evaluation - Evaluation Steps

Found MSE and RMSE to see how well the model performs.
Reviewed the sign of overfitting per MSE and RMSE values.
Reviewed the sign of overfitting visually with residual distribution histogram plot.
Reviewed the list of features in the order of importance for the used car price.*
Re-visited data preparation to remove least important feature and re-ran the model and evaluted again.*
Deployment - Report

Final Report
Goal
The goal is to provide the list of data features that impacts the used car price so this will be able to tell the used car dealership what drives the car prices or in another words, what the consumers want in a used car

Findings
Year and odometer are the primary significant features that impacted the used car price. Type and cylinders played secondary significant features.

Recommendation
The used car dealership should keep the inventory of better year, odometer and cylinders and more attractive types of cars so the car prices are higher and at the same time, those are significant features that consumers look at in the used car
