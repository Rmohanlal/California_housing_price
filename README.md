# California_housing_price
CALIFORNIA HOUSING PRICE
-Description
This project utilizes a dataset containing the following data attributes: longitude, latitude, housingMedianAge, totalRooms, totalBedrooms, population, households, medianIncome, and medianHouseValue. The purpose of this project is to perform analysis and modeling on the dataset, with the objective of predicting the median house value based on the other attributes.
-Dataset
The dataset used in this project is the "California Housing Prices" dataset from the Kaggle, which contains information collected from the 1990 California census. The dataset contains a total of 20,640 instances.
-Dependencies
Python 3.7+
pandas
scikit-learn
matplotlib
jupyter notebook
RandomsearchCV
-Model
The model used in this project is a Random Forest Regressor implemented using the SKLEARN ensemble. The model was trained on the training set and evaluated on the testing set. The evaluation metrics are as follows:
Train accuracy: 94.87%
Test accuracy: 81.22%
Mean absolute error: 32984.13
Mean absolute percentage error: 0.1866
Mean squared error: 2485470008.31
R squared: 0.8122
Adjusted R squared: 0.8118
-Conclusion
The results of this project suggest that the Random Forest Regressor model can be an effective tool for predicting housing prices in California. However, there is still room for improvement, and future work could explore alternative models and feature engineering techniques to improve the accuracy of the predictions.
