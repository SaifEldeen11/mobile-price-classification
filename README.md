# Mobile Price Classification

## Overview

This project uses machine learning to predict the price range of mobile phones based on their specifications.

The dataset contains features such as battery power, RAM, internal memory, screen dimensions, camera specifications, connectivity options, and other hardware characteristics. The target variable is `price_range`, which classifies phones into one of four price categories (0–3).

---

## Dataset

### Features

Some of the available features include:

* Battery Power
* Bluetooth Support
* Clock Speed
* Dual SIM Support
* Front Camera Resolution
* 4G Support
* Internal Memory
* Mobile Weight
* Number of CPU Cores
* Pixel Height
* Pixel Width
* RAM
* Screen Height
* Screen Width
* Talk Time
* 3G Support
* Touch Screen Support
* WiFi Support

### Target

`price_range`

| Class | Meaning        |
| ----- | -------------- |
| 0     | Low Cost       |
| 1     | Medium Cost    |
| 2     | High Cost      |
| 3     | Very High Cost |

---

## Project Workflow

1. Data Loading and Exploration
2. Train-Test Split
3. Decision Tree Classification
4. Random Forest Classification
5. Hyperparameter Tuning with GridSearchCV
6. Support Vector Classification (SVC)
7. Model Comparison
8. Final Prediction Generation

---

## Models Evaluated

### Decision Tree

A baseline tree-based classifier.

**Accuracy:** ~85%

### Random Forest

An ensemble of decision trees with hyperparameter tuning.

**Accuracy:** ~90%

### Support Vector Classifier (SVC)

Provided the best overall performance on the validation set.

**Accuracy:** ~96%

---

## Results

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | 85%      |
| Random Forest | 90%      |
| SVC           | 96%      |

The Support Vector Classifier achieved the highest validation accuracy and was selected as the final model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## Repository Structure

```text
MobileClassificationPrice/
│
├── MobileClassification.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
```

---

## Key Learning Outcomes

* Data preprocessing and feature handling
* Train-test splitting with stratification
* Model evaluation using classification reports
* Hyperparameter tuning using GridSearchCV
* Comparing multiple machine learning algorithms
* Generating predictions for unseen test data
* Creating a complete machine learning workflow

---

## Author

Saif Eldeen
