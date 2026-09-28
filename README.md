# InternSpark Task 1 - Supervised Classification

## Project Overview

This project was completed as part of the InternSpark internship.

The objective of this task was to build and evaluate supervised machine learning classification models using the **Breast Cancer Wisconsin dataset**.

Two classification algorithms were implemented and compared:

* Logistic Regression
* Random Forest

The models were evaluated using multiple classification metrics and visualizations.

## Dataset

The **Breast Cancer Wisconsin (Diagnostic) Dataset** contains:

* 569 samples
* 30 input features
* 1 target variable
* 2 target classes

The dataset is used to classify breast cancer cases based on the provided diagnostic features.

## Machine Learning Workflow

The following steps were performed:

1. Loaded the dataset.
2. Checked the dataset structure and target classes.
3. Preprocessed the data.
4. Split the data into training and testing sets.
5. Applied feature scaling where required.
6. Trained a Logistic Regression model.
7. Trained a Random Forest model.
8. Performed 5-fold cross-validation.
9. Generated predictions on the test dataset.
10. Evaluated both models using classification metrics.
11. Created confusion matrices.
12. Created an ROC curve for model evaluation.

## Algorithms Used

### 1. Logistic Regression

Logistic Regression was used as a linear classification algorithm for predicting the target class.

### 2. Random Forest

Random Forest was used as an ensemble classification algorithm consisting of multiple decision trees.

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

Confusion matrices and an ROC curve were also used to visualize model performance.

## Cross-Validation

Five-fold cross-validation was performed to evaluate the models across multiple training and validation splits.

## Project Files

* `customer_churn_classification.ipynb` - Jupyter Notebook containing the complete implementation, code, evaluation metrics and visualizations.
* `README.md` - Project documentation.

## Requirements

The project uses Python and the following libraries:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* Jupyter Notebook

## Installation

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Running the Notebook

1. Clone or download this repository.
2. Open the project folder.
3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open:

```text
customer_churn_classification.ipynb
```

5. Run the notebook cells from beginning to end.

## Results

Both Logistic Regression and Random Forest were trained and evaluated on the Breast Cancer Wisconsin dataset.

The notebook contains the complete evaluation results, including:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion matrices
* ROC curve
* Cross-validation results

## Conclusion

This project demonstrates the complete workflow of a supervised classification problem, including data preprocessing, train/test splitting, cross-validation, model training, evaluation and visualization.

The comparison of Logistic Regression and Random Forest provides an understanding of how different classification algorithms perform on the same dataset.

## Repository

GitHub Repository:

https://github.com/aishwaryadh674/InternSpark-Task---1-Classification.git
