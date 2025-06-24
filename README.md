Adult Income Classification using Logistic Regression and SVM

This project analyzes the impact of different data preprocessing techniques on the performance of Logistic Regression and Support Vector Machine (SVM) models using the Adult Census Income dataset.

Four preprocessing pipelines were created by combining two imputation methods (Linear Regression and Mean Imputation) with two scaling techniques (Log Scaling and Robust Scaling). Categorical variables were label encoded.

Each pipeline was used to train both Logistic Regression and SVM models, resulting in eight total runs. Models were evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

The results show that preprocessing choices significantly influenced classification performance. Optional hyperparameter tuning with GridSearchCV was also explored.
