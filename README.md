# Obesity Classification Project
This project aims to classify obesity levels based on various attributes using machine learning techniques. The dataset contains 17 attributes, and the records are labeled with the class variable NObesity (Obesity Level), which includes categories such as Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III. The goal is to build a classifier that can accurately predict the obesity level of individuals based on their attributes.

The dataset used for this project can be found [here](https://www.kaggle.com/competitions/playground-series-s4e2/data).

## Techniques Used
The following machine learning techniques were employed for classification:

- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost
  
The main machine learning technique employed for classification is XGBoost due to the good performance.

## Results
The XGBoost model achieved an accuracy of 91.2% on the test dataset. The confusion matrix and classification report are provided to evaluate the model's performance metrics such as precision, recall, and F1-score for each class.

## Usage
- Prepare the dataset.

- Data preprocessing: encode categorical variables, and scale numerical features as necessary.

- Model training: Train the XGBoost model using the prepared dataset and evaluate its performance using cross-validation or train-test split.

- Model evaluation: Evaluate the performance of the XGBoost model using metrics such as accuracy, precision, recall, and F1-score. Compare the results to assess the model's effectiveness in classifying obesity levels.

- Predictions: Utilize the trained XGBoost model to make predictions on new or unseen data, and assess its performance based on the achieved accuracy.
