# EDA-and-Feature-Engineering-on-M5-Forecasting-Accuracy
Dataset: https://www.kaggle.com/c/m5-forecasting-accuracy

This is one of the two complementary competitions that together comprise the M5 forecasting challenge. Can you estimate, as precisely as possible, the point forecasts of the unit sales of various products sold in the USA by Walmart? If you are interested in estimating the uncertainty distribution of the realized values of the same series, be sure to check out its companion competition

How much camping gear will one store sell each month in a year? To the uninitiated, calculating sales at this level may seem as difficult as predicting the weather. Both types of forecasting rely on science and historical data. While a wrong weather forecast may result in you carrying around an umbrella on a sunny day, inaccurate business forecasts could result in actual or opportunity losses. In this competition, in addition to traditional forecasting methods you’re also challenged to use machine learning to improve forecast accuracy.

The Makridakis Open Forecasting Center (MOFC) at the University of Nicosia conducts cutting-edge forecasting research and provides business forecast training. It helps companies achieve accurate predictions, estimate the levels of uncertainty, avoiding costly mistakes, and apply best forecasting practices. The MOFC is well known for its Makridakis Competitions, the first of which ran in the 1980s.

In this competition, the fifth iteration, use hierarchical sales data from Walmart, the world’s largest company by revenue, to forecast daily sales for the next 28 days. The data, covers stores in three US States (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events. Together, this robust dataset can be used to improve forecasting accuracy.



There are 5 files present-

calendar.csv - Contains information about the dates on which the products are sold.

sales_train_validation.csv - Contains the historical daily unit sales data per product and store [d_1 - d_1913]

sample_submission.csv - The correct format for submissions. Reference the Evaluation tab for more info.

sell_prices.csv - Contains information about the price of the products sold per store and date.

sales_train_evaluation.csv - Includes sales [d_1 - d_1941] (labels used for the Public leaderboard)
