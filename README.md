# Credit_Risk_Analysis
## Overview of Project
### Overview of the loan prediction risk analysis
Credit risk is an unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes during this project.

###Purpose
1. The purposes of this project includes:
2. Explaining how machine learning algorithms are used in data analytics.
3. Create training and test groups from a provided data set.
4. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
6. Compare the advantages and disadvantages of each supervised learning algorithm.
7. Determine which supervised learning algorithm is best used for a provided data set or scenario.
8. Use ensemble and resampling techniques to improve model performance.

## Results and Analysis
### Results
The results for the six machine learning models and their respective balanced accuracy, precision, and recall scores are:

 1. Naive Random Oversampling
 
![image](https://user-images.githubusercontent.com/109991916/206018597-cbb8e555-79bc-4536-aac8-efc4b77245ed.png)

Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67


2. SMOTE Oversampling

![image](https://user-images.githubusercontent.com/109991916/206018820-3da6e884-5461-4bbb-914c-6c0ad4ab7e61.png)

Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .62/.64
 
3. Undersampling

![image](https://user-images.githubusercontent.com/109991916/206019008-3f15b619-69f3-423b-a3fc-1d675e072ca8.png)

Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .63/.40

4. Combination Under-Over Sampling

![image](https://user-images.githubusercontent.com/109991916/206019153-92c79bff-f4eb-4cc9-a8ed-e0c5545de323.png)

Balanced Accuracy: 0.5173713090878325
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .70/.57

5. Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/109991916/206019382-dd3c130d-ae09-4822-9d0b-bf6704bd87d3.png)

Balanced Accuracy: 0.7877672625306695
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .67/.91

6. Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/109991916/206019543-f996dff8-0d31-4561-9885-376cde9f0fec.png)

Balanced Accuracy: 0.925427358175101
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .91/.94

## Summary
When working with balanced accuracy, the highest accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. 

The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
