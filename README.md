# Credit_Risk_Analysis
Module 17 Challenge
## Overview
The purpose of this analysis was to use supervised machine learning and Python to build models predicting credit risk. We oversampled the data, undersampled the data, and then used a combination of both. We then compared two different models, BalancedRandomForestClassifier and EasyEnsembleClassifier. We can analyze the models to see which one is the best at predicting credit risk for our purposes.

## Results
We created and analyzed six models total:
* **1) RandomOverSampler model**
  * **Accuracy Score: 64.6%**
  * **Precision: 99%**
  * **Recall: 68%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.30.29%20PM.png)

* **2) SMOTE model**
  * **Accuracy Score: 62.3%**
  * **Precision: 99%**
  * **Recall: 64%**
 ![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.30.46%20PM.png)
 
* **3) ClusterCentroids model**
  * **Accuracy Score: 54.4%**
  * **Precision: 99%**
  * **Recall: 64%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.34.15%20PM.png)

* **4) SMOTEENN model**
  * **Accuracy Score: 61.6%**
  * **Precision: 99%**
  * **Recall: 54%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.38.33%20PM.png)

* **5) BalancedRandomForestClassifier model**
  * **Accuracy Score: 78.8%**
  * **Precision: 99%**
  * **Recall: 91%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.39.44%20PM.png)

* **6) EasyEnsembleClassifier model**
  * **Accuracy Score: 92.5%**
  * **Precision: 99%**
  * **Recall: 94%**
![image](https://github.com/aisligrace/Credit_Risk_Analysis/blob/main/Screen%20Shot%202022-04-29%20at%201.41.05%20PM.png)

## Summary
In conclusion, we laid out the accuracy score, the precision, and recall score of each of the six models above. Of all six, the EasyEnsembleClassifier model had the highest accuracy score, so that model would be the best fit for predicting credit risk. However, this model also had an extremely large number of false high risks (16139), where other models performed better. I would personally recommend that the bank does not use any of these six models, but instead, continues to find a better fit. 

##
