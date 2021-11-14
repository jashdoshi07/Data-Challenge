# Data-Challenge
- Classification with imbalanced dataset, without any feature information
- Used SMOTE, under and over sampling techniques to come up with a hybrid sampling approach.
- Classification algorithm experimented with : LogisticRegression, RandomForest, SVC, XGBClassifier.
- Results : (Models and techniques that performed the best)
- 
| Model  | Val set Accuracy  | AUC  | Sampling | Outliers
|:-:|:-:|:-:| :-: | :-: |
|  Logistic Regression | 0.86  | 0.82  | Hybrid | dropped
| SVC  |  0.87  |  0.82 | Hybrid | dropped
| XGBoost | 0.86 | 0.83 | Hybrid | dropped

