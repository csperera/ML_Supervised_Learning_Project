# machine_learning_project-supervised-learning

## Project Overview
In this Project, we are going to perform a full supervised learning machine learning project on a "Diabetes" dataset. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes, based on certain diagnostic measurements included in the dataset.

## Part 1 - Exploratory Data Analysis
We performed exploratory data analysis and found no missing values in the data set. Although there were no missing values, many values did have an erroneous zero-value which were obviously bad data and would have to be corrected. The predictor variables were linearly related to the outcome variable. There were outliers in the predictor variables which would have to be addressed.

## Part 2 – Preprocessing & Feature Engineering

As mentioned earlier although there are no missing values, there were many zero-values in columns such as blood pressure, skin thickness, insulin and BMI which are obviously erroneous and had to be dealt with utilizing future engineering.  Additionally, outliers in the dataset were located and Windsorization of these outliers at the 95th percentile was accomplished.

## Part 3 - Training The ML Model
The binary classification models chosen were the Random Forest model and the XG boost classification model. After splitting the data into a training and test set, and then fitting them to each model we ran each model and derived metrics for each model. Ultimately the Random Forest Classifier seemed to provide higher accuracy then the XG Boost classifier likely because the Random Forest Classifier is a generally simpler model. It should be noted that we did not optimize either model as we were time constrained to do so however this should be the next step going forward.
