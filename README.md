# House_prices | Kaggle
## Description
A tutorial project based on https://www.kaggle.com/c/house-prices-advanced-regression-techniques.
The project included:
1. Primary analysis and processing of tabular data;
2. Development of a model that predicts the cost of houses depending on their parameters.
## The Goal
The main aim of the project was gain experience in data processing. 
There was no goal to achieve highest score, so model is quite simple and final score is moderate - 0.14925 (61th percentile).
## Preprocessing
1. Errors correction in data;
2. Detection features with NaNs and defining ways to work with them;
3. Replacing NaNs;
4. Detection of categorical features that has low STD/Mean coefficient by price and excluding them from further analysis (LandSlope, MoSold and YrSold);
5. One-hot encoding of categorical features;
6. LotFrontage calculation based on other available features:
    1. Normalization data using StandardScaler from sklearn;
    2. LotFrontage prediction using Lasso Regression.
7. Saving cleaned data in CSV for further work.
## Model
There were experiments with different types of regression (Linear, Lasso and Ridge) and Random Forrest, but the highest score was achieved by using Lasso Regression.
## Score
Best Kaggle score - 0.14925 (61th percentile)
## Next steps
Scores achieved by all models were quite moderate. In order to increase score it's worth to put more time and efforts on data exploration, work more on preprocessing, use log transformation of SalePrice and probably stack different models.
