# Linear Support Vector Machine (SVM) Classification Project

# Project Overview
This project demonstrates a Linear Support Vector Machine (SVM) classifier applied to a synthetic dataset, where we aim to predict customer subscription status (subscribed or not subscribed) based on two key features:

- Age: Age of the customer
- Balance: Account balance of the customer
The project explores the basic principles of SVMs for classification tasks, and includes data preprocessing, model training, evaluation, and visualization of the decision boundary.

# Project Contents
- # Data Generation: A synthetic dataset is generated with realistic patterns, where customers with higher balances and younger ages have a higher likelihood of subscription.

- # Data Preprocessing:
  - The dataset is split into training and test sets.
  - Features are scaled using StandardScaler to optimize SVM model performance.
# Model Training:
  - We train a Linear SVM model using scikit-learn's SVC classifier.
  - The model is trained on the age and balance features to predict subscribed status.
# Evaluation:
  - Model performance is evaluated on the test set using accuracy, confusion matrix, and classification report.
  - Results provide insight into model accuracy and class-wise performance.
# Visualization:
  - The decision boundary for the SVM model is plotted using Matplotlib, illustrating how the classifier distinguishes between subscribed and not subscribed customers.
# Key Files
  - synthetic_data_generation.py: Generates the synthetic dataset with age, balance, and subscribed columns.
  - svm_classification.ipynb: The main notebook containing the data processing, model training, evaluation, and visualization code.

Conclusion
This project is a practical example of using Linear SVM for a classification task. It’s structured to be reusable and modular, so it can be adapted easily to other datasets and feature combinations. Feedback and contributions are welcome!
