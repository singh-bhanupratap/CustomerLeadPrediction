# CustomerLeadPrediction

This project was developed as part of a consultancy pitch for World Plus Bank, aiming to design and evaluate a lead prediction system for their new term deposit product. The objective was to help the bank identify prospective customers most likely to convert, thereby optimizing marketing costs and increasing sales efficiency.


The solution involved:

* Cleaning and preparing a dataset of 220,000 historic customer records.

* Handling missing and erroneous values with hot-deck imputation and data filtering.

* Applying SMOTE to balance class distributions.

* Performing feature selection using information gain.

* Training and evaluating multiple classification models: Logistic Regression, Decision Trees (C5.0, Ctree), Random Forest, and SVM.

* Comparing models based on precision, recall, F1-score, accuracy, and AUC.


Key Findings:

* Models performed significantly better on the imputed dataset compared to the dataset with removed NAs.

* Random Forest emerged as the best-performing model, striking a strong balance between precision and recall, with lower risk of overfitting.

* Logistic Regression and Decision Trees showed fair performance but struggled with recall (higher false negatives).

* SVM achieved comparable metrics but was computationally expensive, making it less practical for deployment.
