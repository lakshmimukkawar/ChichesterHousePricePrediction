# Chichester House Price Prediction
This is task about predicting the house prices in Chichester district. The dataset provided has features like 'Price', 'Street', 'Postcode',
'Property_Type', 'Old_New', etc. My task is to do Exploratory analysis on the given data and applying models to predict the prices of house. Then researching and enriching
the model with socio-demo/economical data.

## Steps followed for prediction -
* Exploratory analysis on the given dataset(stats, correlations, etc) - 
Analysing the number of records, columns, column type, checking missing values, checking value counts of each column, finding correlations, 
checking distributions of the features, etc.
* Visualizations for understanding data - 
Understanding the distribution of data by plotting graphs like boxplot, scatterplot, bar chart. 
* cleaning data to apply models (LASSO, Elastic Net, RandomForestRegressor, GradientBoostingRegressor, LGBMRegressor) - 
Removing irrelevant columns like street, locality. creating new columns like high_season, transfer_year, postcode with 4 character, etc. Checking for outliers, scaling the data and then applying models.
* Improvising performance of models - 
Model performance checked by adding/removing columns, changing hyperparameters, creating new columns
* Adding socio-demo/economical data - 
Given dataset does not have lot of features which helps in predicting the price. So, research is done about how can we add new features to improve model performance. With the help of google API's I took the data average ratings of school nearby in the given postcode which influence the house price. Like that we can take into consideration the number of stores available, population of the area/postcode can also help us to make the model more accurate.
