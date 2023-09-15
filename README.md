# Credit Risk Classification Report

## Description
The purpose of this credit risk analysis is to identify the creditworthiness of borrowers. This analysis use a logistic regression model to identify healthy loans(0) and high-risk loan(1). There are two models have been created. Models are trained using different methods and their performance is compared to determine which model performs better. 

## Model 1
* instantiating a logistic regression model and training with the original training sets (X_train, y_train), fitting it to the training sets, and using it to generate predictions <br>

### Results
Model 1 had been trained on the original data, gives an accuracy of 95.2% in predicting the 2 labels. The model is very good at predicting the healthy loans, the precision score of this model is 1.00. On the other hand, the prediction of high-risk loan is only 0.85, which indicates that only 87% of actual high-risk loans were correctly predicted.


## Model 2
*  resampling the original training data using the RandomOverSampler module, instantiating a logistic regression model and fitting the resampled training sets (X_r, y_r) to the model, and generating predictions <br>

### Results
