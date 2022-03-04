# Cement_Strength_Prediction
This repository code solves the problem of flawed cement mixture, which result into poor strength of Buildings and Structures using ML.

Dataset link - https://www.kaggle.com/vinayakshanawad/cement-manufacturing-concrete-dataset

Steps followed:
1. Performed EDA on dataset found that.
2. Find the correlation between features.
3. Clustered the dataset using KMeans into 3 cluster.
4. Trained model for each cluster and evaluated their performance.
5. Increased performance of models is found when using clustered data, in comparison to using whole dataset.
6. XGBoost performed the best on clustered and whole dataset with an R2 score of 0.899001 and 0.929995 respectively.

![image](https://user-images.githubusercontent.com/64093713/156764066-dc8d3e37-70e5-44e1-b5c3-3f4be3b34858.png)
![image](https://user-images.githubusercontent.com/64093713/156764173-df3a1339-50ad-475c-bd99-c2038a45fded.png)

Orange curve represent models trained on clustered data. The performance of XGBoost and Linear Regression was better.
