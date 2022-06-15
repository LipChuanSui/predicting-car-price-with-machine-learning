# predicting-car-price-with-machine-learning

The aim of this case study is to build Regression models on the given dataset for predicting the selling price.

The dataset given has less features compared to last assessment. Age column is removed and thus extra work is needed to fetch age from year of registration. Standard model and body type has more rare categories and are needed to properly addressed. Huge attention on feature engineering are needed to produce good dataframe for training.

After that , datasets will be split into training and test sets and a number of different models such as Random forests, Gradient Boosted Tree with XGBoost and linear model with selected interactions will be implemented using them. An esemble method will also be used to combine all 3 models.

In Model Analysis, Predicted vs True plot, residual plot and SHAP value will be used to analysis the results. Google Colab will be used to carry out this case study.

## Random Forest RMSE: 0.394800 r2_score: 0.843145 score: 0.830813

## Gradient boost with XGBoost RMSE: 0.486077 r2_score: 0.764086 score: 0.762313

## Linear Regression RMSE: 0.549821 r2_score: 0.697006 score: 0.696851

## Voting RMSE: 0.405164 r2_score: 0.835949 score: 0.829753

According to the results, RandomForest Regressor produces the best result with lowest RMSE, high r2_score and high cross val score. Voting method also produces good results.

## Thus, RandomForestRegressor is highly recommened.
