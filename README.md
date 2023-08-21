# breast_cancer_models
Built and trained various machine learning models predicting whether a tumor is malignant or benign 


Used the SkLearn breast cancer dataset imported from the Wisconsin Breast Cancer database. 

key variables included radius, texture, perimiter, area, smoothness, symmetry and concavity amongst other parameters.

trained KNN, Logistic regression, decision tree, linear and kernel SVCs, random forests, gradient boost, XGboost, and Extra trees.

Bagging and pasting were also applied to logistic regression and decision trees as separate classifiers. 

Also trained voting and stacking classifiers. Used a correlation heatmap to choose the most correlated classifiers to include in these ensemble models. 
