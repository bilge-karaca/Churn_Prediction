# Churn_Prediction

This project’s goal is to predict churning customers in the 6 upcoming months, using a real-world transactional dataset.

The scope of the project covers
- an intensive **preprocessing** and **transformation** phase on the raw dataset,
- defining churn event in a **non-contractual e-commerce setting**,
- taking various approaches for prediction: I build models using **3 different datasets** while applying a variety of **supervised classification algorithms** accompanied by **unsupervised techniques** to constitute hybrid approaches.

More precisely, I generate **network features** and **time-based features** to create two different datasets, and I use **clustering** and **PCA** for hybrid models.

The main single predictors are **Logistic Regression, Random Forest, XGBoost, LightGBM and SVM**. 

The selected model, XGB-oversampling, achieves f1-score = 61.46% on the test dataset.

Keywords: Churn prediction, classification, tree-based models, network science, customer analytics, non-contractual setting, hybrid model, e-commerce, imbalanced data.
