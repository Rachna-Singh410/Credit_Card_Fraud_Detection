# Credit_Card_Fraud_Detection
In Present senario fraud rates are increasing, so that to avoid from all these we started using different machine learning algorithm to detect and analyse fraud cases. We can use many algorithm like Random forest, Naive Bayes and Isolation Forest etc. Here I used Isolation Forest algorithm and local outlier factor for predicting the classification details.
First of all I read the dataset and after tha I made histogram for all attributes or variables present in the dataset. Then we predicted or calculated the Fraud and Valid cases for credit card. After this using the isolation forest and local outlier, I predicted the classification details.

### Prerequisites
Some python Libraries
```
Numpy
Matplotlib.pyplot
seaborn etc.
```

### Installing
```
pip install library_name
```
#### Dataset
I took the dataset from Kaggle. Link for dataset is https://www.kaggle.com/mlg-ulb/creditcardfraud. The dataset had 31 columns. Some columns are time,v1-v28 these are result of a PCA Dimensionality reduction to protect user identities and sensitive features, amount and class.
