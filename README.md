# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis
This project adapted several machine learning models to solve a real-world challenge: credit card risk.
### The purpose of this analysis 
The purpose is to evaluate the performance of these models to precidt the crdit risk. Being able to predict credit risk with machine learning algorithms can help banks and financial institutions better predict anomalies, reduce risk cases, monitor portfolios, and provide advice on what to do in the event of fraud.
## Machine Learning Models
1.	Naive Random Oversampling
    ![random oversampling](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/RandomOverSampler.png)
    
2.	SMOTE Oversampling
    ![SMOTE Oversampling](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/SMOTE%20Oversampling.png)
    
3.	Cluster Centroid Undersampling
    ![Cluster Centroid Undersampling](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/Undersampling.png)
    
4.	Combination
  ![Combination](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/Combination%20(Over%20and%20Under)%20Sampling.png)
  
5.	Balanced Random Forest Classifying
![Balanced Random Forest Classifying](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/Balanced%20Random%20Forest.png)

6.	Easy Ensemble Classifying
![Easy Ensemble Classifying](https://github.com/summerginger/Credit_Risk_Analysis/blob/main/pics/Easy%20Ensemble%20AdaBoost.png)

## Summary
The results shows that the easy ensemble analysis model has the highest accuracy score, which can be able to detect 93% of high risk credit but the model is only preicse in 8% of those detections. This would negatively affect individuals with good credit trying to take out loans. Credit risk is an inherently unbalanced classification problem, as the number of good loans easily outnumber the number of risky loans. More preprocessing steps need to be considered (imbalanced-learn). Employ different techniques to train and evaluate models with unbalanced classes.
