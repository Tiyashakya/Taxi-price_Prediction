# Titanic-Classification-summary
Comparison of Classification Algorithms on the Titanic Dataset

Process Flow
1. Load the Titanic dataset,on which EDA and feature engineering, and scaling has been performed in exploration stage 
2. Perform data preprocessing and feature engineering as required.
3. Split the dataset into training and testing sets using train_test_split() function from sklearn.model_selection.
4. Initialize the decision tree, logistic regression, and KNN classification models.
5. Fit the models on the training data using their respective fit() functions.
6. Predict the labels for both the training and testing data using the predict() function of each model.
7. Calculate and store the accuracy, precision, recall, F1 score, and AUC ROC for each model using appropriate metrics from sklearn.metrics.
8. Plot the AUC curve for each model using the roc_curve() and auc() functions from sklearn.metrics.
9. Create a dataframe to store the performance metrics for each model, including the train accuracy, test accuracy, train precision, test precision, train recall, test recall, train F1 score, test F1 score, train AUC ROC, and test AUC ROC.
10. Print the performance metrics in a tabular format.


This created dataframe stores the performance metrics for each model, allowing for easy comparison and analysis of the classification algorithms on the Titanic dataset.
