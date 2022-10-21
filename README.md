# Credit Risk Analysis - Supervised Learning

## Overview of the Analysis
In this project, credit risk is an unbalanced classification problem because good loans outnumber risky loans. In order our analysis would be more accurate, we are implementing different techniques to train and evaluate models with unbalanced classes. 
A dataset from LendingClub, a peer-to-peer lending services company will be utilize and employ the following:

> *  Oversampling the data using '''RandomOverSampler''' and '''SMOTE''' algorithms. 

> * Undersample the data using '''ClusterCentoroids''' algorithm.

> * Use a combinatorial approach of over- and undersampling using the '''SMOTEENN''' algorithm.


> * Compare two machine learning models that reduce bias, '''BalancedRandomForestClassifier''' and '''EasyEnsembleClassifier'''.



## Resources:
> * Data Source: LoanStats_2019Q1.csv

> * Software: Jupyter Notebook, Pythondata, Anaconda Navigator 


## Results:
### Naive Random Oversampling

#### Balance Accuracy

![Delivery 1 Balanced Accuracy](Resources/Delivery%201%20Balance%20Accuracy%20Score.png)

####  Confusion Matrix

![Confusion Matrix](Resources/Naive%20Random%20Over%20Sampling%20Confusion%20Matrix.png)

#### Classification Report 

![Classification Report](Resources/Naive%20Random%20Over%20Sampling%20Classification%20Report.png)


### SMOTE Oversampling

## Summary:
