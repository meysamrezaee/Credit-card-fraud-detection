# Credit card fraud detection
Goal: Build a classifier to distinguish between fraudulent/valid transactions

Skills required:
  - Python programming
  - Understanding Numpy, Pandas libraries
  - Understanding machine learning algorithms such as Random Forest, and Logistic regression
  - Using ensembled methods to improve performance
  - Familiarity with anomaly detection 

Challenge:
  - The classes are highly unbalanced.

Method:
  - Anomaly detection algorithms such as One Class SVM, Isolation Forest, and Local Outlier Factor were applied.
  - After balancing the classes, classification algorithms were used.
  - An ensembled method was used to achieve better performance.
  
Results:
  - The anomaly detection algorithms did not perform well.
  - After down-scaling the data, classification algorithms reached higher recall and precision.
  - The best results were achived by using a two layer ensembled method: Precision = 0.77, Recall = 0.81

Data used from:
https://www.kaggle.com/mlg-ulb/creditcardfraud