# Imbalanced Classification Example

This repository contains part of the code I used for a project focused on building a model with a dataset containing an imbalanced class. Despite the class imbalance, I employed an iterative approach to model development, starting with a simple decision tree model and progressively testing and refining the model's parameters to enhance its performance. The best-performing model was selected, and its weights were saved in a .pkl file.

It is important to note that I limited the parameter testing options due to the large size of the dataset. Due to the very small number of positive cases, it was impractical to create a smaller subset of the dataset.

## Credit Card Fraud Dataset (from Kaggle)

Due to GDPR and data governance protocols, I am unable to share the original dataset used in this project. However, to ensure that the code is runnable, I’ve imported a widely used synthetic dataset containing fake credit card fraud data (with an imbalanced class) from Kaggle.
