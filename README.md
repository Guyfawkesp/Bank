# Practical Application III: Comparing Classifiers

## Overview

In this practical application, we aim to **compare the performance** of several supervised machine learning classifiers on a real-world dataset. The classifiers used in this analysis are:

- K Nearest Neighbors (KNN)
- Logistic Regression
- Decision Trees
- Support Vector Machines (SVM)

We utilize a dataset related to **marketing bank products over the telephone**, sourced from the UCI Machine Learning Repository.

## Dataset

The data is from a **Portuguese banking institution** and contains information about the results of various direct marketing campaigns. The goal is to predict whether a client will subscribe to a term deposit based on their attributes and past interactions.

-  Source: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
-   More info: [Related research article (Moro et al., 2014)](https://www.sciencedirect.com/science/article/pii/S0957417414001166)

## Results Summary

The table below summarizes the training time, accuracy scores, and best cross-validation accuracy for each classifier:

| Model                   | Train Time (s) | Train Accuracy | Test Accuracy | Best CV Accuracy |
|------------------------|----------------|----------------|----------------|------------------|
| KNeighborsClassifier   | 3.21           | 0.9142         | 0.9016         | 0.8966           |
| LogisticRegression     | 1.90           | 0.9101         | 0.9164         | 0.9099           |
| DecisionTreeClassifier | 0.84           | 0.9160         | 0.9185         | 0.9122           |
| SVC                    | 814.00         | 0.9251         | 0.9125         | 0.9051           |

## Key Takeaways

- **Decision Tree** achieved the best **test accuracy** and **cross-validation score** overall.
- **Logistic Regression** performed well with minimal training time, making it an efficient baseline model.
- **SVM** achieved strong accuracy but at a very high computational cost.
- **KNN** provided competitive performance with moderate training time.


