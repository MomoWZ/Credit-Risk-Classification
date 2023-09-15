# Credit Risk Classification Report

## Description
The purpose of this credit risk analysis is to identify the creditworthiness of borrowers. This analysis use a logistic regression model to identify 2 lables, healthy loans(0) and high-risk loan(1). There are two models have been created. Models are trained using different methods and their performance is compared to determine which model performs better. 

## Model 1
* instantiating a logistic regression model and training with the original training sets (X_train, y_train), fitting it to the training sets, and generating predictions <br>

### Results
Model 1 had been trained on the original data, gives an accuracy of 95.2% in predicting the 2 labels. The model is very good at predicting the healthy loans, the precision score of this model is 1.00. And the recall score is nearly 1.00. On the other hand, the prediction of high-risk loan is only 0.85, which indicates that only 87% of actual high-risk loans were correctly predicted. Compared with healthy loans, the high-risk loan only identified 91% of all high-risk loans in the dataset. Overall, the F1 score is a weighted average of the precision and recall scores. Our model's F1 score is 88%.

## Model 2
*  resampling the original training data using the RandomOverSampler module, instantiating a logistic regression model and fitting the resampled training sets (X_r, y_r) to the model, and generating predictions <br>

### Results
Compared with Model 1, Model 2 has 99.4% accuracy in perdicting the 2 lables. With the health laons, Model 2 has the same results with Model 1. Moreover, the prediction of high-risk loan has decreased one piont, 0.84. But, the high-risk loan only identified 99% of all high-risk loans in the dataset. Overall, the F1 score is a weighted average of the precision and recall scores. Our model's F1 score is 91%.

## Summary
Based on the above two model, I believe that Model 2 has outperformance Model 1 with higher accuracy score. Model 2 has better ability predicting high-risk loans while correctly identifying all high-risk loans in the dataset compared with Model 1. In conculsion, Model 2 will be a better fit in perdicting healthy loans and high-risk loan.
