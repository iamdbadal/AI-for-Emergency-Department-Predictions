# AI-for-Emergency-Department-Predictions
The Emergency Department (ED) in a hospital is an extremely 
important, 
high-pressure 
and often resource-constrained 
environment. Patients are assessed and triaged for further care, with 
conditions varying from mild abrasions to life-threatening cardiac 
complications. With the recent advances in artificial intelligence 
and machine learning, there is an opportunity to apply these in the 
ED environment to gain new insights, make predictions and 
improve the quality of care. 
This work develops and evaluates a set of machine learning models 
to predict whether an ED patient should be admitted to hospital for 
further care or sent home. The MIMIC-IV-ED dataset, which 
contains US patient data for approximately 425,000 ED visits, is 
used throughout. The models developed achieve AUROC scores in 
the 81% - 84% range which are comparable with those from other 
similar studies. The XGBoost and Deep Neural Networks models 
perform slightly better than Logistic Regression, Decision Tree and 
Random Forest models. However, lower Sensitivity scores are a 
source of concern and require further investigation. 
This work also demonstrates how XAI techniques can be used to 
explain the predictions being made, and how Model Compression 
can reduce the model size and compute resources needed without 
having a major impact on accuracy. Ethical and legal compliance 
considerations are explored, along with an assessment of possible 
sources of bias and mitigation approaches. 
