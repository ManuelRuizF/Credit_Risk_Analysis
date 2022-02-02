# Credit_Risk_Analysis

## Overview of the analysis
So for this work we are going to do an analsys on credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. To make this machine learning model we are going to do the following:  
- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk  
We will evaluate each model and compared them. According to the results we will anañyze if it´s worth using it for this project.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Oversampling (Naive Random Oversampling)  
![lo](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/1.%20naive%20r%20oversampling.PNG)  
- The accurancy balance is 65%.  
- The high risk is about 1%
- There is a low risk of 100%  

### SMOTE Oversampling  
![los](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/2.%20Oversampling%20SMOTE.PNG)  
- The accurancy balance is 63%.  
- The high risk is about 1%
- There is a low risk of 100% 

### Undersampling  
![lod](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/3.%20undersampling.PNG)  
- The accurancy balance is 50%.  
- The high risk is about 1%
- There is a low risk of 100% 

### Combination 
![log](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/4.%20combination%20over%20and%20under.PNG)
- The accurancy balance is 62%.  
- The high risk is about 1%
- There is a low risk of 100% 

### Balanced Random Forest Classifier
![loh](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/5.%20Balanced%20Random%20Forest%20Classifier.PNG)
- The accurancy balance is 78%.  
- The high risk is about 4%
- There is a low risk of 100% 

### Easy Ensemble AdaBoost classifier  
![loj](https://github.com/ManuelRuizF/Credit_Risk_Analysis/blob/main/resources/6.%20easy%20ensemble%20adaboost%20classifier.PNG)
- The accurancy balance is 93%.  
- The high risk is about 7%
- There is a low risk of 100% 



## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
