# Fundamentals of Machine Learning Support Vector Machines, Practical Session

## Practical Session

### Results on Random Datasets:

#### Linear SVM Classifier:
- Best Hyperparameters: {'C': 1, 'gamma': 0.1}
- Test Set Accuracy: 0.945

#### RBF SVM Classifier:
- Best Hyperparameters: {'C': 1, 'gamma': 0.01}
- Test Set Accuracy: 0.95

#### Polynomial SVM Classifier:
- Best Hyperparameters: {'C': 1, 'gamma': 0.01}
- Test Set Accuracy: 0.95

### Results on Pulsar Dataset:

#### SVM Classifier:
- Best Hyperparameters: {'C': 10, 'gamma': 0.1, 'kernel': 'rbf'}
- Train Set Accuracy: 0.9808
- F1 Score: 0.8882

### Saving Predictions:
- Predictions made on the test set are saved to 'y_pred_test.csv' using `to_csv()` method with index set to False.
