# Titanic Survival Prediction Using Logistic Regression

## RCA – CIE 2 Activity 2: Binary Classification

## About the Activity

This project is part of the **Regression and Classification Algorithms (RCA) – CIE 2 Activity 2**. It demonstrates the application of Logistic Regression, a supervised machine learning classification algorithm, to predict the survival of passengers aboard the Titanic.

## Objective

- To understand the working of Logistic Regression.
- To perform data preprocessing and exploratory data analysis.
- To engineer meaningful features from passenger information.
- To train and optimize a classification model.
- To predict passenger survival probabilities and class labels.
- To evaluate the model using classification performance metrics.

## Dataset

The project uses the Titanic dataset, which contains information about passengers aboard the Titanic.

**Dataset Source:** [Titanic Dataset – GitHub](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)

### Selected Features

- `pclass` – Passenger class
- `sex` – Gender of the passenger
- `age` – Age of the passenger
- `sibsp` – Number of siblings or spouses aboard
- `parch` – Number of parents or children aboard
- `fare` – Ticket fare
- `embarked` – Port of embarkation
- `family_size` – Total family members travelling with the passenger
- `is_alone` – Indicates whether the passenger was travelling alone

### Target Variable

- `survived = 0` – Did not survive
- `survived = 1` – Survived

## Algorithm Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems. It estimates the probability of an outcome belonging to a particular class using the sigmoid function.

In this project, it predicts whether a Titanic passenger survived or did not survive.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed

1. Loaded and explored the Titanic dataset.
2. Checked missing values, duplicates and data types.
3. Performed data cleaning and preprocessing.
4. Handled missing numerical and categorical values.
5. Encoded categorical features and scaled numerical features.
6. Performed exploratory data analysis using visualizations.
7. Created additional features such as family size and travelling alone.
8. Split the dataset into training and testing sets using stratified sampling.
9. Trained a Logistic Regression model.
10. Optimized model hyperparameters using cross-validation.
11. Generated predicted probabilities and class labels.
12. Evaluated the model using a confusion matrix and classification metrics.
13. Compared different decision thresholds.
14. Analyzed the ROC curve and ROC-AUC score.
15. Compared training and testing performance.
16. Compared the model with a majority-class baseline.
17. Made a prediction for a new passenger.

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- Specificity
- F1-score
- ROC-AUC
- Confusion Matrix
- Classification Report

A majority-class baseline is also used to compare the performance of Logistic Regression.

## Results

The Logistic Regression model achieved the following performance on the test dataset:

| Metric | Score |
|---|---:|
| Accuracy | 82.12% |
| Precision | 81.36% |
| Recall | 69.57% |
| F1-score | 75.00% |
| ROC-AUC | 84.99% |

The model correctly classified approximately 82% of the passengers in the test dataset. The ROC-AUC score of 84.99% indicates that the model has a reasonable ability to distinguish between passengers who survived and those who did not.

## Conclusion

This activity provided practical understanding of Logistic Regression and its application to binary classification problems. It involved data preprocessing, feature engineering, model training, hyperparameter optimization, probability-based predictions and model evaluation.

The project also demonstrated how evaluation metrics, confusion matrices, ROC curves and decision thresholds help assess the performance of a classification model.

## GitHub Repository

This activity is maintained in an individual public GitHub repository for faculty review.

**Student GitHub ID:** [complexiota](https://github.com/complexiota)

**Repository Name:** RCA-CIE2-Activity2-AD3103

The repository contains the completed notebook/report, README and required project files. It is publicly accessible for review.


