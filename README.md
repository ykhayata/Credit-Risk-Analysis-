# Credit Risk Analysis

## Overview

The main purpose of my analysis is to develop a machine learning model that could help us accurately predict credit risk. We used 6 different methods to accomplish this feat:

1: Naive Random Oversampling

2: SMOTE Oversampling

3: Cluster Centroid Undersampling

4: SMOTEENN Sampling

5: Random Forest Classifying

6: Ensemble Classifying

Let's dig into the results! 

## Results

### Naive Random Oversampling

-Accuracy Score: 67.1%

-Precision High Risk: 1%

-Precision Low Risk: 100%

-Recall High Risk: 66%

-Recall Low Risk: 68%

<img width="752" alt="oversampling" src="https://user-images.githubusercontent.com/74481469/112792754-e6c1af80-9018-11eb-9a79-72f494f06ecc.png">

### SMOTE Oversampling

-Accuracy Score: 68.4%

-Precision High Risk: 1%

-Precision Low Risk: 100%

-Recall High Risk: 74%

-Recall Low Risk: 62%

<img width="779" alt="SMOTE_analysis" src="https://user-images.githubusercontent.com/74481469/112792872-1b356b80-9019-11eb-8104-c82abfe52bbc.png">

### Cluster Centroid Undersampling

-Accuracy Score: 52.3%

-Precision High Risk: 0%

-Precision Low Risk: 100%

-Recall High Risk: 62%

-Recall Low Risk: 42%

<img width="819" alt="undersampling" src="https://user-images.githubusercontent.com/74481469/112796022-38b90400-901e-11eb-9f1e-60c8ec996999.png">

### SMOTEENN Sample

-Accuracy Score: 68.1%

-Precision High Risk: 1%

-Precision Low Risk: 100%

-Recall High Risk: 76%

-Recall Low Risk: 60%

<img width="824" alt="SMOTEEN_analysis" src="https://user-images.githubusercontent.com/74481469/112796229-8df51580-901e-11eb-94b2-ca374b46dded.png">

### Random Forest Classifying 

-Accuracy Score: 64.8%

-Precision High Risk: 56%

-Precision Low Risk: 100%

-Recall High Risk: 30%

-Recall Low Risk: 100%

<img width="835" alt="random_forest" src="https://user-images.githubusercontent.com/74481469/112796490-e5938100-901e-11eb-934d-8618e9896a22.png">

### Easy Ensemble Classifying 

-Accuracy Score: 92.3%

-Precision High Risk: 6%

-Precision Low Risk: 100%

-Recall High Risk: 91%

-Recall Low Risk: 94%

<img width="762" alt="easy_ensemble" src="https://user-images.githubusercontent.com/74481469/112796601-0f4ca800-901f-11eb-91c7-949b449be2a9.png">

## Summary 

Our mission is to find a model that poses the least risk on loans passing through, or in other words: lets the least amount of high risk loans pass through undetected. We can use the recall rate (high risk and low risk) as a base, and evaluate the models with the highest rates:  Looking through the different models, the ones that scored the highest were: (high risk / low risk)

1: Easy Ensemble Classifying (91% / 94%)

2: SMOTEENN Sampling (76% / 60%)

3: Naive Random Oversampling (66% / 68%)

4: Random Forest Classifying (30% / 100%)

Now let us examine the overall accuracy percentages to give us a better gauge of how the models perform in general:

1: Easy Ensemble Classify (92.3%)

2: SMOTE Oversampling (68.4%)

3: SMOTEENN Sampling (68.1%)

The Easy Ensemble Classifying model is clearly the most consistent in terms of accuracy as demonstrated above. Therefore, I would highly recommend this model for future use.
