# Churn-Predictor
The project builds a Neural Network model to predict whether the customer will continue their subscription or cancel it. 

The main inspiration is from the video https://www.youtube.com/watch?v=MSBY28IJ47U&list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO&index=21&ab_channel=codebasics. Please follow it, if you have any queries.
The dataset is downloaded from https://www.kaggle.com/code/danwheble/churn-prediction-telco-customer-churn.

Data is imported and preprocessed: useless training samples are dropped, data is converted from categorical to numerical, categories are improved, label encoding, normalization and downsampling.

The data us then trained, evaluated and tested. The metrics of the test are displayed using classification report and confusion matrix.
