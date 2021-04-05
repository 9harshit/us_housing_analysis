# US Housing Analysis 

 - Clean and preprocessed data used in this EDA is present in repo ***team_est.csv***
 - Details of preprocessing present in eda.ipynb file

## Data Analysis

   ### House precise in US over 20 years

   ![Screenshot](https://github.com/9harshit/fellowshipai-resnet-challenge/blob/main/images/houseprice.png)
   
   - Average hosue price in the country increased steadily over the the before 2008.
   - During 2009 house price valuation of the house decreased steeply.

   ### Average Rent in US over 10 years

   ![Screenshot](https://github.com/9harshit/fellowshipai-resnet-challenge/blob/main/images/rent.png)

   ### Co relation between features

   ![Screenshot](https://github.com/9harshit/us_housing_analysis/blob/main/images/corelation.png)

     - The correlation between a house price and the number of hospitals is: -0.10979622877935635
     - The correlation between a house price and the average hospital rating is: -0.30849722716408334
     - The correlation between a house price and the number of schools is: 0.10923147385165584
     - The correlation between a house price and the unemployment rate is: 0.01700132949276519
     - The correlation between a house price and the average rent is: 0.8402757243440176
     - The correlation between a house price and the average price per sqr_feet is: 0.8762089824059839



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
