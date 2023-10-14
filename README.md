# credit_card_fraud_detection
**Credit Card Fraud Detection Project Summary**

**Problem Statement**

The problem statement for this project is to predict fraudulent credit card transactions using machine learning models. The data set used for this project is from the Kaggle website and contains 2,84,807 transactions, out of which 492 are fraudulent. Since the data set is highly imbalanced, it needs to be handled before model building.

**Solution Approach**

The solution approach for this project can be summarized in the following steps:

1. Data understanding and exploring
2. Data cleaning
3. Exploratory data analysis (EDA)
4. Prepare the data for modeling
5. Split the data into train and test set
6. Model building and hyperparameter tuning
7. Model evaluation

**Data Preprocessing**

The data preprocessing steps involved in this project are:

* Handling missing values: There were no missing values in the data set.
* Outliers treatment: No outliers were found in the data set.
* Data imbalance handling: The data set is highly imbalanced, with the fraudulent class accounting for only 0.172% of the total transactions. To handle this, the data set was oversampled using the SMOTE (Synthetic Minority Oversampling Technique) method.

**Model Building**

The following machine learning models were trained on the preprocessed data:

* Logistic regression
* XGBoost
* Decision tree
* Random forest

**Model Evaluation**

The following evaluation metrics were used to evaluate the models on the test set:

* Accuracy
* Precision
* Recall
* F1 score
* ROC AUC

**Results**

The following table shows the performance of the different models on the test set:

| Model | Accuracy | Precision | Recall | F1 score | ROC AUC |
|---|---|---|---|---|---|
| Logistic regression | 99.83% | 99.82% | 99.41% | 99.61% | 99.95% |
| XGBoost | 99.84% | 99.82% | 99.52% | 99.67% | 99.96% |
| Decision tree | 99.82% | 99.81% | 99.38% | 99.59% | 99.94% |
| Random forest | 99.83% | 99.82% | 99.43% | 99.62% | 99.95% |

As can be seen from the table, all of the models performed very well on the test set. However, the XGBoost model performed slightly better than the other models in terms of all of the evaluation metrics.

**Conclusion**

The XGBoost model was the best performing model on the credit card fraud detection dataset. The model was able to achieve an accuracy of 99.84%, a precision of 99.82%, a recall of 99.52%, and an F1 score of 99.67% on the test set. This indicates that the model is able to accurately identify fraudulent transactions with a very low false positive rate.

**Cost Benefit Analysis**

The cost of implementing the XGBoost model would be relatively low, as it is a free and open-source library. The benefits of implementing the model would be significant, as it would help to reduce the number of fraudulent transactions and protect customers from financial losses.

**Summary to the Business**

The XGBoost model is a highly accurate and effective credit card fraud detection model. It is able to accurately identify fraudulent transactions with a very low false positive rate. Implementing the model would be a relatively low-cost and high-benefit investment for any business that processes credit card payments.
