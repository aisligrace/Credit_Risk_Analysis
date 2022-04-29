# Credit_Risk_Analysis
Module 17 Challenge
## Overview
The purpose of this analysis was to use supervised machine learning and Python to build models predicting credit risk. We oversampled the data, undersampled the data, and then used a combination of both. We then compared two different models, BalancedRandomForestClassifier and EasyEnsembleClassifier. We can analyze the models to see which one is the best at predicting credit risk for our purposes.

## Results
We created and analyzed six models total:
* **RandomOverSampler model**
  * **Accuracy Score: 64.6%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.30.29%20PM.png)

* **SMOTE model**
  * **Accuracy Score: 62.3%
 ![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.30.46%20PM.png)
 
* **ClusterCentroids model**
  * **Accuracy Score: 54.4%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.34.15%20PM.png)

* **SMOTEENN model**
* **Accuracy Score: 61.6%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.38.33%20PM.png)

* **BalancedRandomForestClassifier model**
* **Accuracy Score: 78.8%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.39.44%20PM.png)

* **EasyEnsembleClassifier model**
* **Accuracy Score: 92.5%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.41.05%20PM.png)

## Summary
