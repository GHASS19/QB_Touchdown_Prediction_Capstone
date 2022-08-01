# QB_Project
## Predicting How Many Touchdowns a Quaterback Will Throw in a Game

![image](https://user-images.githubusercontent.com/86930309/182204292-9bba47db-947a-47fd-acde-dfd9c76246f6.png)

   *Analytics in football has become a more accepted concept in football over the past few years. The probability of an event occuring has become useful to coaches in situtations during a game. Brian Burke made analytics in football popular in the mid 2000s with Advanced Football Anlytics.  Data-driven strategies and aggressive decisionmaking can help a team win more games. Predicting how many touchdowns a QB will throw in a game is argueably the most important statistic in football besides the final score. In this project I created a random forest model to predict how many TDs a QB will throw based upon their statistics.*

## 1. The Data
The database is the largest collection of quarterback data on Kaggle, (https://www.kaggle.com/datasets/speckledpingu/nfl-qb-stats). The stats are from every National Football League game from 1996-2016. This was a CSV file.

## 2. Models
This was a regression problem as touchdowns in a game is a continous quantity. I did a train test split on the data to see how accurate each of the four models I examined performed on the data. The four models I tried were linear regression, lasso regression, ridge regression and random forest regression. The best performing model was random forest regression.
The Random Forest R2 score was nearly perfect at .997. It had a very solid MAE of .006 and RMSE of .06 on the test data. The CV average & Grid Search CV for Random Forest was a very high score of .9977 and .9979.
	               
## 3. Data Wrangling & Cleaning 
[Data Wrangling & Cleaning] (https://github.com/GHASS19/QB_Project/blob/main/Notebooks/2.%20QB_Data_Wrangling.ipynb) 

