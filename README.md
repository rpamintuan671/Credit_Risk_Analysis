# Credit Risk Analysis - Supervised Learning
![](Resources/Credit%20Decision.jpg)

# Overview of the Analysis
In this project, credit risk is an unbalanced classification problem because good loans outnumber risky loans. In order our analysis would be more accurate, we are implementing different techniques to train and evaluate models with unbalanced classes. 
A dataset from LendingClub, a peer-to-peer lending services company will be utilize and employ the following:

> *  Oversampling the data using **Naive RandomOverSampler** and **SMOTE** algorithms. 

> * Undersample the data using **ClusterCentoroids** algorithm.

> * Use a combinatorial approach of over- and undersampling using the **SMOTEENN** algorithm.


> * Compare two machine learning models that reduce bias, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**.



## Resources:
> * Data Source: LoanStats_2019Q1.csv

> * Software: Jupyter Notebook, Pythondata, Anaconda Navigator 


# Results:
### Naive Random Oversampling

#### Balanced Accuracy Score

![Delivery 1 Balanced Accuracy](Resources/Delivery%201%20Balance%20Accuracy%20Score.png)

####  Confusion Matrix

![Confusion Matrix](Resources/Naive%20Random%20Over%20Sampling%20Confusion%20Matrix.png)

#### Classification Report 

![Classification Report](Resources/Naive%20Random%20Over%20Sampling%20Classification%20Report.png)


### SMOTE Oversampling
#### Balanced Accuracy Score
![](Resources/SMOTE%20Oversampling%20Balanced%20Acccuracy.png)

####  Confusion Matrix
![](Resources/SMOTE%20Oversampling%20Confusion%20Matrix.png)

#### Imbalanced Classification Report
![](Resources/SMOTE%20Oversampling%20Imbalance%20Classification%20Report.png)


### Undersampling
#### Balanced Accuracy Score
![](Resources/Undersampling%20Balanced%20Accuracy%20Score.png)

####  Confusion Matrix
![](Resources/Undersampling%20Confusion%20Matrix.png)

#### Imbalanced Classification Report
![](Resources/Undersampling%20Imbalanced%20Classification%20Report.png)

### Combination (Over and Under) Sampling
Testing over-and under-sampling algorithm. Below is a result of resampling data using SMOTEENN algorithm. 


#### Balanced Accuracy Score
![](Resources/Combination%20Over%20and%20Under%20Sampling%20Balanced%20Accuracy%20Score.png)

####  Confusion Matrix
![](Resources/Combination%20Over%20and%20Under%20Sampling%20Confusion%20Matrix.png)

#### Imbalanced Classification Report
![](Resources/Combination%20Over%20and%20Under%20Sampling%20Classification%20Report.png)

## Esemble Learners
### Balance Random Forest Classifier

#### Balanced Accuracy Score
![](Resources/Balanced%20Random%20Forest%20Classifier%20Accuracy%20Score.png)

####  Confusion Matrix
![](Resources/Balanced%20Random%20Forest%20Classifier%20Confusion%20Matrix.png)


#### Imbalanced Classification Report
![](Resources/Balanced%20Random%20Forest%20Classifier%20Imbalanced%20Classification%20Report.png)

### Easy Ensemble AdaBoost Classfier

#### Balanced Accuracy Score
![](Resources/Easy%20Ensemble%20Adaboost%20Classifier%20Balanced%20Accuracy%20Score.png)

####  Confusion Matrix
![](Resources/Easy%20Ensemble%20Adaboost%20Classifier%20Confusion%20Matrix.png)


#### Imbalanced Classification Report
![](Resources/Easy%20Ensemble%20Adaboost%20Classifier%20Imbalanced%20Classification%20Report.png)


# Summary:
