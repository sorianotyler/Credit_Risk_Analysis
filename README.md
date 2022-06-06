# Credit_Risk_Analysis


## Overview of Project
 The objective of this project is to practice using supervised machine learning to predict credit card risk. With this unbalanced classification problem we want to see the effect of using the different techniques to evaluate models with unbalanced classes.
### Purpose
The purpose of this is to demostrate knowledge of the different models and to find the best model to predict risk.  

 
## Results 
Naive Random Oversampling:
- accuracy: 0.6375472246439988 or 63%
- Precision for high_risk: 0.01 or 1%
- recall for high_risk: 0.68 or 68%  
Reference fig1

SMOTE Oversampling
- accuracy: 0.6816623074687591 or 68%
- Precision for high_risk: 0.01 or 1%
- recall for high_risk: 0.61 or 61%  
Reference fig2

Undersampling
- accuracy: 0.45033420517291484 or 45%
- Precision for high_risk: 0.01 or 1%
- recall for high_risk: 0.61 or 61%  
Reference fig3

Combination (Over and Under)
- accuracy: 0.45033420517291484 or 45%
- Precision for high_risk: 0.01 or 1%
- recall for high_risk: 0.61 or 61%  
Reference fig4

Balanced Random Forest Classifier 
- accuracy: 0.7899981707712398 or 78%
- Precision for high_risk: 0.03 or 3%
- recall for high_risk: 0.69 or 69%  
Reference fig5

Easy Ensemble AdaBoost Classifier
- accuracy: 0.9316600714093861 or 93%
- Precision for high_risk: 0.09 or 9%
- recall for high_risk: 0.92 or 92%  
Reference fig6



## Summary 
In conclusion, the best model to use would be the Easy Ensemble AdaBoost Classifier. This model has the highest accuracy (93%) with the second highest only being 78%. It would also have the highest precision with 9% with the second highest precision being only 3% and a majority being only 1%. Finally it has the highest recall with 92% with the second highest being 69%.
