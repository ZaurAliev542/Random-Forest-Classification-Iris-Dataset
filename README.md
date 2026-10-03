# Random-Forest-Classification-Iris-Dataset
Random Forest Classification using the Iris dataset. This notebook covers data preparation, train-test splitting, model training, prediction, evaluation, feature importance, tree visualization, and hyperparameter analysis with `n_estimators` and `max_depth`.
# Random Forest Classification — Iris Dataset

## Objective

This notebook demonstrates a complete Random Forest classification workflow using the Iris dataset.

## Topics Covered

* Dataset loading and exploration
* Train/Test Split
* Random Forest Classifier
* Model Training
* Prediction
* Accuracy
* Confusion Matrix
* Precision, Recall, and F1-score
* Prediction Probabilities
* Feature Importance
* Visualization of Individual Decision Trees
* `n_estimators` experiment
* `max_depth` experiment
* Decision Tree vs Random Forest comparison

## Model

A `RandomForestClassifier` is trained using multiple Decision Trees. For classification, the final prediction is determined through aggregation of the individual tree predictions.


## Dataset

The Iris dataset contains:

* 150 observations
* 4 numerical features
* 3 target classes

## Conclusion

The experiment demonstrates how Random Forest combines multiple Decision Trees to perform classification and how model complexity and the number of trees can affect training and test performance.
