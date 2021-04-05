# US Housing Analysis 

 - Clean and preprocessed data used in this EDA is present in repo ***team_est.csv***
 - Details of preprocessing present in eda.ipynb file

## Data

 - Data is considered only for period between 2000 and 2020
 - Unemployment rate is calculated by taking average of values from 2000 to 2018 state wise.
 - Hospital rating is calculated by taking average of values of all hospitals in state based on latest values present.
 - Average rent price and average price of house per sqrfeet is calculated by taking average price from 2010 to 2017.
 - Average house price is calculated by taking average price from 2000 to 2017.

 ***Assumptions***
 - Main objective of this EDA is to find relation between house price and other factors hence some assumptions are made.
    - By taking average we are assuming value of that particular feature before or after in that time period was same. This allows us to use average rent price from 2010-2017 with average house price from 2000-2017.

 - More information for the data is present in the links provided for each dataset
   

## Data Analysis

   ### House precise in US over 20 years

   ![Screenshot](https://github.com/9harshit/us_housing_analysis/blob/main/houseprice.png)
   
   - Average hosue price in the country increased steadily over the the before 2008 hosuing crisis.
   - During 2009 house price valuation of the house decreased steeply.
   - Prices kept decresing for next 3 years.
   - Prices started stablising in 2012 and after that kept increasing year by year.

   ### Average Rent in US over 10 years

   ![Screenshot](https://github.com/9harshit/us_housing_analysis/blob/main/rent.png)
   
   - Trends of the rental price has been same in 2010 to 2017.
   - Rent increased in mid-year and decreased towards the end of the year.
   - This trend can be the result of end of summer break, starting of college sem and students moving. Families tend to shift during this time of year

   ### Co relation between features

   ![Screenshot](https://github.com/9harshit/us_housing_analysis/blob/main/corelation.png)

     - The correlation between a house price and the number of hospitals is: -0.10979622877935635
     - The correlation between a house price and the average hospital rating is: -0.30849722716408334
     - The correlation between a house price and the number of schools is: 0.10923147385165584
     - The correlation between a house price and the unemployment rate is: 0.01700132949276519
     - The correlation between a house price and the average rent is: 0.8402757243440176
     - The correlation between a house price and the average price per sqr_feet is: 0.8762089824059839

  - House price has highest corelation with price per sqaure feet naturally and least with hospital rating in the area.
  - House price have good relation with schools displaying hosue buyers tendacy to buy house near schools.


## Model Building

  - The data is split into train and tests sets with a test size of 20%.
  - Models performance is measured using R2 score.

  - Model used :
     - Linear Regression
     - Random Forest Regressor
     - Xgboost

 - Model performance :

    - Linear Regression: R2 Score = 0.81
    - Random Forest Regressor: R2 Score = 0.72
    - Xgboost: R2 Score = 0.44


### Links to Raw Dataset

  1) Zillow Economics Dataset : https://www.kaggle.com/zillow/zecon
  2) Crime rate Dataset — US Crime rates by County : https://www.kaggle.com/mikejohnsonjr/united-states-crime-rates-by-county
  3) School Dataset — USA Public Schools : https://www.kaggle.com/carlosaguayo/usa-public-schools
  4) Hospital Dataset : https://www.kaggle.com/carlosaguayo/usa-hospitals/version/1
  5) Hospital Rating Dataset : https://www.kaggle.com/center-for-medicare-and-medicaid/hospital-ratings
  6) Unemployment Dataset — USA Unemployment rate Dataset ; https://www.kaggle.com/carlosaguayo/2018-unemployment-rate-by-county/version/1
