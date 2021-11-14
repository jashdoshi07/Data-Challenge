# Data-Challenge
- Classification with imbalanced dataset, without any feature information
- Used SMOTE, under and over sampling techniques to come up with a hybrid sampling approach.
- Classification algorithm experimented with : LogisticRegression, RandomForest, SVC, XGBClassifier.
- Results : (Models and techniques that performed the best)
 
| Model  | Val set Accuracy  | AUC  | Sampling | Outliers
|:-:|:-:|:-:| :-: | :-: |
|  Logistic Regression | 0.86  | 0.82  | Hybrid | dropped
| SVC  |  0.87  |  0.82 | Hybrid | dropped
| XGBoost | 0.86 | 0.83 | Hybrid | dropped

###Key Points:
- Since here the variable are not explainable, I used PCA and then logistic regression as well. But it also did not improve the accuracy.
- If we did have the feature names, we could have used our domain knowledge to decide if the given feature is required or not.
- We could have tried knn imputations. We could also address the skewed distribuition to first transform it normal distribuition using log transforms.

