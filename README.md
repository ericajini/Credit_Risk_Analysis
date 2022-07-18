# Credit Risk Analysis 

## Overview 

The overall goal was to create & train 6 different machine learning models using an unbalanced data set, to evaluate the performance of these models, and then make a written recommendation on whether they should be used to predict credit risk. The 6 Machine Learning models create include Random Over Sampler, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classified, and Easy Ensmble Classifier.  

## Results 

![ValueCounts](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/ValueCounts.png)

### Random Over Sampler
The overall accuracy for the ROS model was 65.2%. 

The precision score for high risk was only at 1% and the preicision score for low risk was 100%. The recall score for high risk was 61% while the recall score for low risk was 69%. The f1 score for high risk was 2% and 82% for low risk. 

![ROS](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/ROS.png)

### SMOTE 
The overall accuracy for the ROS model was 64.6%. 

The precision score for high risk was only at 1% and the preicision score for low risk was 100%. The recall score for high risk was 63% while the recall score for low risk was 66%. The f1 score for high risk was 2% and 79% for low risk. 

![SMOTE](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/SMOTE.png)

### Cluster Centroids
The overall accuracy for the ROS model was 64.6%. 

The precision score for high risk was only at 1% and the preicision score for low risk was 100%. The recall score for high risk was 60% while the recall score for low risk was 43%. The f1 score for high risk was 1% and 60% for low risk. 

![CC](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/CC.png)

### SMOTEENN
The overall accuracy for the ROS model was 51.6%. 

The precision score for high risk was only at 1% and the preicision score for low risk was 100%. The recall score for high risk was 69% while the recall score for low risk was 58%. The f1 score for high risk was 2% and 74% for low risk. 

![SMOTEENN](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/SMOTEENN.png)

### Balanced Random Forest Classifier
The overall accuracy score for the ROS model was 78.8%. 

The precision score for high risk was only at 4% and the preicision score for low risk was 100%. The recall score for high risk was 67% while the recall score for low risk was 91%. The f1 score for high risk was 7% and 95% for low risk. 

![BRFC](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/BFC.png)

### Easy Ensemble Classifier 
The overall accuracy score for the ROS model was 92.5%. 

The precision score for high risk was only at 4% and the preicision score for low risk was 100%. The recall score for high risk was 67% while the recall score for low risk was 91%. The f1 score for high risk was 7% and 95% for low risk. 

![EEC](https://github.com/ericajini/Credit_Risk_Analysis/blob/main/EEC.png)

## Summary 

Overall the Easy Ensemble Classifier had the best results out of all 6 machine learning models. Going back to the goal of this analysis, which was to determine if I would recommend using any of these models to assist with assessing credit risk; I don't feel that any of these models do a good enough job to recommend using and feel like using any of these models would be risky. All of these models do not do enough to detect high risk clients. I think this could potentially be helped by increasing the amount of data because high risk is such a low part of this population, so having more of these loans that are high risk, combined with maybe some other factors that are not currently taken into account, could improve these results. 
