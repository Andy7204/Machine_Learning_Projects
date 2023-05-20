# ML Model Implementation
 
I have implemented three models with sample datasets.
1. Linear Regression - It plots two graphs one for training and one for test dataset.
2. Logistic Regression - It plots a confusion matrix representing its classification.
3. RandomForest Regression - It gives the lowest Mean Absolute Error with the best tree size.

### Linear Regression

It uses train_test_split to split data into test and training data and scatter plot to visualize the data.

### Logistic Regression

It uses feature scaling for data normalization and a confusion matrix to visualize the results.

### RandomForest Regressor

It finds out the lowest MAE by testing against a list of tree sizes and print the final MAE.
