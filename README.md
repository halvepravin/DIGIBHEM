# README: PREDICT THE PRICES OF STOCKS 

## Creator # Halvepravin

## Aim

The aim of this project is to build a Machine Learning model to predict the prices of stocks.

## Dataset

The model will be trained on a dataset of historical stock prices. once the model is trained, it can be used to predict future stock prices

## Libraries Used

The following important libraries were used for this project:

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.preprocessing.LabelEncoder
- sklearn.model_selection.train_test_split
- Keras model

## Data Exploration and Preprocessing

1. The dataset was loaded using pandas as a DataFrame, and its shape and a glimpse of the first high , low , close volume and then open.
2. Next the dataset were arranged to array where we can known it easily.
3. The tenserflow is used for updating the stock prices from the year of evaluating.
4. The close price is used with the stock prices in the dollars.
5. Then at the last from the date to Close and to predictions have made.
6. For the prediction of the stock here the chart is used.


## Model Training

1. The feature matrix `X` and target vector `Y` were created using relevant columns from the DataFrame.
2. The dataset was split into training and testing sets using `train_test_split` from `sklearn.model_selection`.
3. A Keras model was initialized and trained on the Keras ` from `sklearn.Keras_model`.

## Model Prediction

1. The model was used toto predict the prices of stocks.
2. The predicted results were printed using root mean .
3. The actual target prices in the test set were printed using `Y_test`.
4. A sample prediction was made using the stocks between 2 to 3 years.