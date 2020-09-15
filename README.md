# Credit-Card-Fraud-Detection

## The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Dataset:  https://www.kaggle.com/mlg-ulb/creditcardfraud 

Observations :

    Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors vs. SVM detecting 8516 errors
    Isolation Forest has a 99.74% more accurate than LOF of 99.65% and SVM of 70.09
    When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%.
    So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%.
    We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases


