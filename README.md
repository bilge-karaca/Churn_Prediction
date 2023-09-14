# Churn_Prediction

This project’s goal is to predict churning customers in the 6 upcoming months, using a real-world transactional dataset.

The scope of the project covers:
- an intensive **preprocessing** and **transformation** phase on the raw dataset,
- defining churn event in a **non-contractual e-commerce setting**,
- taking various approaches for prediction: I build models using **3 different datasets** while applying a variety of **supervised classification algorithms** accompanied by **unsupervised techniques** to constitute hybrid approaches.

More precisely, I generate **network (graph) features** and **time-based features** on top of the base dataset to create two enhanced dataset variants. Base dataset itself contains **customer, basket, transaction, product and RFM features**.


The main single predictors I train are **Logistic Regression, SVM, Random Forest, XGBoost and LightGBM**. Then I use **k-means clustering** and **PCA** for hybrid models.


The selected model, XGB-oversampling, achieves f1-score = 61.46% on the test dataset.

--

Keywords: Churn prediction, classification, RFM, segmentation, tree-based models, network science, graphrole, customer analytics, non-contractual setting, hybrid model, e-commerce, imbalanced data.
