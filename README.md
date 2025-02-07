# Bank-Churn-Prediction_ML
Developed a predictive model to determine whether bank customers will stay or exit, using an imbalanced dataset. Implemented **K-Nearest Neighbors (KNN) and Stochastic Gradient Descent (SGD) classifiers**, along with techniques like __SMOTE and Random Under sampler__ for handling class imbalance. Evaluated model performance using accuracy, precision, recall, and F1-score to ensure robustness. <br>
1. Loaded _Bank Churn_ dataset which contains imbalanced data. <br>
(_There where 0 - 130113 and 1 - 34920_) <br>
2. Balanced the dataset firstly using Over sampler here I used SMOTE(_Synthetic Minority OverSampling Technique_). <br>
3. Scale and split the dataset <br>
4. Created Stochastic Gradient Descent model and got an accuracy of 80%. <br>
5. Thus I also developed KNN model and got a better accuracy of **84%**. <br>
6. Created Confusion matrix and Classification report. <br>
7. Predicted with new values <br>
8. Balanced the data with _undersampling_ using Random under sampler <br>
9. Trained and predicted with the help of KNN but only got 75% accuracy. <br>
