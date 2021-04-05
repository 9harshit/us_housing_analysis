# us_housing_analysis

Data Cleaning and Preprocessing

  After downloading the data, I needed to clean it up so that it was usable for my model. I made the following changes and created the following variables:

  Handled NULL values in the dataset
  Made columns for Size in Mb, Size in Kb and Size that can varies
  Converted the price into float values
  Seprate out the genres list
  Grouped Android versions
  Added a column for last updated year

Model Building

  First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.

  I tried six different models and evaluated them using R2. I chose MAE because it is relatively easy to interpret and outliers aren’t particularly bad in for this type of model.

  Linear Regression
  Random Forest Regressor
  Xgboost

  Model performance

  Linear Regression: MAE = 0.34
  Random Forest Regressor: MAE = 0.31
  Xgboost: MAE = 0.33


### Links

  1) Zillow Economics Dataset : https://www.kaggle.com/zillow/zecon
  2) Crime rate Dataset — US Crime rates by County : https://www.kaggle.com/mikejohnsonjr/united-states-crime-rates-by-county
  3) School Dataset — USA Public Schools : https://www.kaggle.com/carlosaguayo/usa-public-schools
  4) Hospital Dataset : https://www.kaggle.com/carlosaguayo/usa-hospitals/version/1
  5) Hospital Rating Dataset : https://www.kaggle.com/center-for-medicare-and-medicaid/hospital-ratings
  6) Unemployment Dataset — USA Unemployment rate Dataset ; https://www.kaggle.com/carlosaguayo/2018-unemployment-rate-by-county/version/1
