### Problem Statement : 


Real estate transactions are quite opaque sometimes and it may be difficult for a newbie to know the fair price of any given home. Thus, multiple real estate websites have the functionality to predict the prices of houses given different features regarding it. Such forecasting models will help buyers to identify a fair price for the home and also give insights to sellers as to how to build homes that fetch them more money. Chennai house sale price data is shared here and the participants are expected to build a sale price prediction model that will aid the customers to find a fair price for their homes and also help the sellers understand what factors are fetching more money for the houses?


**About Dataset**

The Chennai_House_Predictions data set is a collection of 7109 houses records from 2004 to 2015 with 21 features. It contains attributes like AREA ,INT_SQFT', DATE_SALE, DIST_MAINROAD,N_BEDROOM,N_BATHROOM,N_ROOM, SALE_COND, PARK_FACIL, DATE_BUILD, BUILDTYPE UTILITY_AVAIL, STREET,MZZONE, SALES_PRICE etc

**MAIN OBJECTIVE**

The main objective is to predict Sales Price using various independent features provided in the dataset. Here, following Regression method are used :
* Vanila Linear Regression 
* Lasso
* Ridge
* KNN Regressor
* Decision Tree
* Bagging
* Boosting

Performance of each regression is evaluated using __R2_score__. 

**INDEX**

* Import Libraries
* Read Data
* Data Cleaning and EDA
* Data Prepartion
* Model Training
* Conclusion
