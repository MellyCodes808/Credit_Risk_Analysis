## Credit_Risk_Analysis
![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/1.jpg)

# Overview of the analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this analysis, I employe different techniques to train and evaluate models with unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

By using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.Lastly, I evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk


# Results:
Naive Random Oversampling

![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/Naive%20Random%20Oversampling.png)

Balanced Accuracy: 64% 

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .62/.66

SMOTE Oversampling

![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/SMOTE%20Oversampling.png)

Balanced Accuracy: 63%

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .59/.67

Undersampling
![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/Undersampling.png)

Balanced Accuracy: 52%

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .57/.47

Combination Under-Over Sampling

![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/Combination%20Under-Over%20Sampling.png)

Balanced Accuracy: 60%

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .67/.55

Balanced Random Forest Classifier

![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/Balanced%20Random%20Forest%20Classifier.png)

Balanced Accuracy: 78%

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .67/.91

Easy Ensemble AdaBoost Classifier

![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/Easy%20Ensemble%20AdaBoost%20Classifier.png)

Balanced Accuracy: 93%

Low for High-risk loans, high for Low-risk loans

Recall Score: High-Low risk = .91/.94



# Summary:

Based on all models ran, the Easy Ensemble AdaBoost Classifier spreformed the best with a 93% accuracy at detecting a low-credit risk loan. The second best model prefoming at only %78. None of the models did a good job of determining if an individual is is high-risk- which is another important metric to consider.  For this dataset the EEAC algorithm preforms best. 

