# Prediction_Of_Wine_Variety

This model applies Text classification to predict the Wine variety. The Train dataset contains a column named "Review_description", that consists of Wine reviews given by various Wine Critics. This review data along with the data in the "Variety" column is used to develop a model that can predict the Wine variety.

The review from the critics is also used to draw various actionable insights.

# Required Libraries

1. numpy
2. pandas
3. tensorflow
4. sklearn
5. keras
6. matplotlib
7. seaborn

# Model Used

Various models like SVM, LSTM, Bidirectional LSTM and Simple Pooling were tested, but Simple Pooling model gave the best result. Hence, Simple Pooling model is used in this application.

Train Accuracy: 0.9485 (94.85 %)


# Uploaded Files

1. train.csv - The training set contains 82657 rows and 12 Features (Including 'variety' column)

2. test.csv - The test set contains 20665 rows and 11 columns ('Variety' is missing, This has to be predicted by the model)

3. Wine_Variety_Prediction.ipynb - This file contains the simple Pooling model implementation for prediction of Wine Variety.

4. Actionable_Insights.ipynb - This file contains implementations to draw Actionable Insights from the critics review and their visualization. The Actionable insights are:
   1) Top 10 Wine Producing Countries
   2) Top 10 Wine Critics
   3) Top 10 Wine Producing Wineries
   4) Top 10 Wine Varieties based on Points given
   5) Distribution of Points For Top 10 Wine Varieties
