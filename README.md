# **Breast Cancer Prediction using Support Vector Machine (SVM)**

This repository contains the implementation of a Support Vector Machine (SVM) model to classify breast cancer using the `scikit-learn` library. The dataset used is the popular Breast Cancer dataset from `sklearn.datasets`.

## **Overview**

This project demonstrates how to:
- Load and explore the Breast Cancer dataset.
- Split the data into training and testing sets.
- Train an SVM model on the training data.
- Evaluate the model using accuracy and a confusion matrix.

## **Dataset**

The Breast Cancer dataset is a well-known dataset for binary classification tasks. It contains features computed from digitized images of a fine needle aspirate (FNA) of a breast mass. The dataset includes 569 instances with 30 feature variables and a target variable indicating the presence of malignant or benign cancer.

## **Code Explanation**

1. **Loading the Dataset:**
   - We start by importing the Breast Cancer dataset from `sklearn.datasets` and converting it into a pandas DataFrame for easier manipulation.

2. **Data Splitting:**
   - The data is split into training and testing sets using `train_test_split` from `sklearn.model_selection`, with 75% of the data used for training and 25% for testing.

3. **Model Training:**
   - A Support Vector Classifier (SVC) model is created and trained on the training data.

4. **Predictions and Evaluation:**
   - The model makes predictions on the test data, and the accuracy of the model is computed.
   - A confusion matrix is also generated to give more insight into the classification performance.

## **Results**

- The accuracy score of the model is printed, showing the effectiveness of the SVM in classifying the test data.
- The confusion matrix provides details on the true positives, true negatives, false positives, and false negatives.
