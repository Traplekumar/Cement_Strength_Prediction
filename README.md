# Cement_Strength_Prediction
This repository code solves the problem of flawed cement mixture, which result into poor strength of Buildings and Structures using ML.

Dataset link - https://www.kaggle.com/vinayakshanawad/cement-manufacturing-concrete-dataset

Steps followed:
1. Performed EDA on dataset.
2. Find the correlation between features.
3. Clustered the dataset using KMeans into 3 cluster.
4. Trained model for each cluster and evaluated their performance.
5. Increased performance of models is found when using clustered data, in comparison to using whole dataset.
6. XGBoost performed the best on clustered and whole dataset with an R2 score of 0.899001 and 0.929995 respectively.

![image](https://user-images.githubusercontent.com/64093713/156765090-18ab6986-8215-4e36-ae82-2b499236b293.png)
![image](https://user-images.githubusercontent.com/64093713/156765100-d68e4c96-df8c-4a44-b38c-931e90af10b0.png)


Orange curve represent models trained on clustered data. The performance of XGBoost and Linear Regression was better.
