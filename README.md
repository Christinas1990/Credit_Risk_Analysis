# Credit_Risk_Analysis

## Overview 

The purpose of the anaylsis is to evaulate if the machine learning models are accurate to determine credit risk which is unbalanced classification problem by using imbalanced-learn and scikit-learn libraries.


## Results

### Naive Random Oversampling

<img width="730" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/100255000/177044812-5848ae67-5fbc-4d39-b4bc-4ebcd7414177.png">

* Balanced Accuracy Score is 65%
* High Risk Loan Precision score is 1% with Recall score of 61%
* Precision Low Risk Loan score is 100% with Recall score of 68%
* Overall precision score of 99% and Recall score of 68%

### SMOTE Oversampling

<img width="745" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/100255000/177045230-b1cb2ce2-72e2-4c33-9b37-3a10f6d67433.png">

* Balanced Accuracy Score is 62%
* High Risk Loan Precision score is 1% with Recall score of 61%
* Precision Low Risk Loan score is 100% with Recall score of 64%
* Overall precision score of 99% and Recall score of 64%

### Undersampling

<img width="741" alt="Undersampling" src="https://user-images.githubusercontent.com/100255000/177045356-57bf94a0-121f-4174-bfaf-45cebd27c2d2.png">

* Balanced Accuracy Score is 52%
* High Risk Loan Precision score is 1% with Recall score of 57%
* Precision Low Risk Loan score is 100% with Recall score of 46%
* Overall precision score of 99% and Recall score of 46%

### Combination Under-Over Sampling

<img width="749" alt="Combination Under-Over Sampling" src="https://user-images.githubusercontent.com/100255000/177045420-fe185ca3-a757-44ac-bca0-048c5526901b.png">

* Balanced Accuracy Score is 62%
* High Risk Loan Precision score is 1% with Recall score of 69%
* Precision Low Risk Loan score is 100% with Recall score of 54%
* Overall precision score of 99% and Recall score of 54%

### Balanced Random Forest Classifier

<img width="730" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/100255000/177045509-439e524e-3a88-4c71-95bc-d88db67690c9.png">

* Balanced Accuracy Score is 79%
* High Risk Loan Precision score is 4% with Recall score of 67%
* Precision Low Risk Loan score is 100% with Recall score of 91%
* Overall precision score of 99% and Recall score of 91%

### Easy Ensemble AdaBoost Classifier

<img width="736" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/100255000/177045554-117d9f4a-276c-44df-85fb-908d140ab164.png">

* Balanced Accuracy Score is 93%
* High Risk Loan Precision score is 7% with Recall score of 91%
* Precision Low Risk Loan score is 100% with Recall score of 94%
* Overall precision score of 99% and Recall score of 94%

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)`
