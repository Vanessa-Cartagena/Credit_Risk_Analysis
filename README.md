# Credit_Risk_Analysis
In this task, we used machine learning to address the problem of credit risk. To create and assess models utilizing resampling, we used the imbalanced-learn and scikit-learn libraries. We oversampled the data using the RandomOverSampler and SMOTE algorithms and undersampled the data using the ClusterCentroids algorithm using the credit card credit dataset from LendingClub, a peer-to-peer lending services provider. The SMOTEENN algorithm was then utilized in a combinatorial approach of over- and undersampling. In order to predict credit risk, we also compared BalancedRandomForestClassifier and EasyEnsembleClassifier, two novel machine learning models that reduce bias.

## Results
### Oversampling 
Naive RandomOverSampler 
<img width="670" alt="Screen Shot 2022-10-16 at 2 48 03 AM" src="https://user-images.githubusercontent.com/105958160/196022497-b32c6583-83af-479e-8018-c5a54f03ea6b.png">
SMOTE OverSampler 
<img width="653" alt="Screen Shot 2022-10-16 at 2 48 14 AM" src="https://user-images.githubusercontent.com/105958160/196022510-0474481b-2fe0-4eda-9975-3a1529478ab7.png">

### Undersample
ClusterCentroids
<img width="655" alt="Screen Shot 2022-10-16 at 2 48 31 AM" src="https://user-images.githubusercontent.com/105958160/196022513-a3ff9de4-eb39-4e77-b313-3c82271bde04.png">

### Combination Sampling 
<img width="657" alt="Screen Shot 2022-10-16 at 2 48 41 AM" src="https://user-images.githubusercontent.com/105958160/196022515-303657b2-ee8e-4f49-9cb2-d2cd10ddf019.png">

### Ensemble Learners 

<img width="657" alt="Screen Shot 2022-10-16 at 2 50 00 AM" src="https://user-images.githubusercontent.com/105958160/196022529-47043672-8de4-4708-bbe3-08b45ebba392.png">

<img width="786" alt="Screen Shot 2022-10-17 at 2 43 11 PM" src="https://user-images.githubusercontent.com/105958160/196257500-101da2a0-b09b-4fee-9697-e455905e5d45.png">

Based on the models we examined for this challenge, the Easy Ensemble Adaboost Classifer model predicted "High Risk candidates" with an accuracy rate of 93.17%, a precision rate of 9%, and a recall rate of 94%. This model received the highest results. The least number of high-risk loans would be able to get through undetected using this approach. So, I recommend utilizing this module.

