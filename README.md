## Credit_Risk_Analysis
![alt text](https://github.com/MellyCodes808/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/viz/1.jpg)

# Overview of the analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this analysis, I employe different techniques to train and evaluate models with unbalanced classes. I used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

By using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.Lastly, I evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk


# Results:




# Summary:

Based on all models ran, the Easy Ensemble AdaBoost Classifier spreformed the best with a %92.5 accuracy at detecting a low-credit risk loan. The second best model prefoming at only %78. None of the models did a good job of determining if an individual is is high-risk- which is another important metric to consider.  For this dataset the EEAC algorithm preforms best. 

