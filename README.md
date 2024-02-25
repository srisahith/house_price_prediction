## Abstract
A minimum mean square error of 0.3769 was obtained on the test dataset with a Stacked Regressor model to predict the sale price of a house with the dataset.Stacked Regressor model helped to improve the performance of all its constituent models.


## Dataset
The housing dataset “House Prices". size of 1000 samples with 10 features were provided

## Feature Engineering
-
-checking the skewness and applied  logarithmic transformation was applied skewed features to the sale price for prediction.
 New columns were added to the data frame such as total bathrooms.
 
## Data Modelling
A total of seven different models were used for prediction.mean square error and mean absolute error were the primary metrics used for evaluating the models. 

#Model,	RMSE on validation set,  Mean CV Score

- XG boost   Mean Squared Error (MSE): 0.30931216726429683
             Mean Absolute Error (MAE): 0.46997580766677854

- K- Nearest Neighbour: Mean Squared Error (MSE): 0.25367346938775515
                        Mean Absolute Error (MAE): 0.45000000000000007
	
- Decision Tree:	Mean Squared Error (MSE): 0.32809958074198
                    Mean Absolute Error (MAE): 0.44365821240163344

- Random Forest:	Mean Squared Error (MSE): 0.2772254851584415
                    Mean Absolute Error (MAE): 0.44727570731965677

- Support Vector Regressor:	Mean Squared Error (MSE): 0.24197994548117127
                            Mean Absolute Error (MAE): 0.33200770719754774

- Gradient Boosting Regressor:	Mean Squared Error (MSE): 0.2608976641679839
                                 Mean Absolute Error (MAE): 0.43816490068733527

- Stacked Regressor:	Mean Squared Error (MSE): 0.24200777945841367
                        Mean Absolute Error (MAE): 0.3320665817488602

MSE and MAE SVM having low values followed by Stacked Regressor.
