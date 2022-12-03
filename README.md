# online_payment_fraud_detection-model-building

Descriptive analysis and pre processing: https://github.com/ThasneemShehani/online_payment_fraud_detection

Payment fraud detection is critical to prevent losses and ensure operations are smooth and secure. Therefore, here my objective is to analyze whether an online transaction is fraud or non-fraud (which is the target variable) with the use of several variables such as hour of transaction, type, amount etc. from the given dataset. To detect whether an online transaction is fraud or non-fraud, Logistic regression, Decision Tree classifier, Random Forest classifier and XGBoost models were fitted. According to the given dataset and after feature selection, each model was fitted for 10 and 23 variables separately. Finally, the XGBoost model fitted using the under sampled dataset (due to high imbalance) had an accuracy of 0.99 with a single falsely predicted negative record (a fraud transaction predicted as non-fraud). 

Google colab

pandas, seaborn, matplotlib, numpy, LabelEncoder, OneHotEncoder, ExtraTreesClassifier, LogisticRegression, classification_report, confusion_matrix, GridSearchCV, RandomizedSearchCV, imblearn.under_sampling, RandomOverSampler, SMOTETomek, DecisionTreeClassifier, RandomForestClassifier, roc_auc_score, roc_curve, XGBClassifier, plot_partial_dependence
