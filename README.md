# Logistic-Regression
Iris classification  using  Logistic Regression
A machine learning project implementing the Logistic Regression algorithm to classify Iris flowers into three species using the classic Iris dataset.

Dataset Source: Scikit-learn's built-in load_iris() dataset

Features: 4 numerical attributes Sepal Length (cm) Sepal Width (cm) Petal Length (cm) Petal Width (cm)

Libraries:

pandas
numpy
matplotlib
scikit-learn

Key Concepts Data loading with sklearn.datasets Train-test split (80/20)(train-75% / 80%, test-25% / 20% ) 

Expected Output:
confusion_matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

 classification_report:
 precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      1.00      1.00         9
   virginica       1.00      1.00      1.00        11

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30

Accuracy Score: 1.0

New Flower Prediction:
Input: [[0.1,0.5,0.4,0.2]]
Predicted Species: versicolor
