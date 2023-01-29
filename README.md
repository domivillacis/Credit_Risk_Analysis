# Credit Risk Analysis

# Overview of the analysis

The purpose of this analysis is to evaluate whether any of the supervised machine learning models would help predict credit risk to determine which applicants are good loan candidates so they can get a lower default rate or simply if none of these models are accurate.

# Results 

After analyzing each model, these are the results we have obtained from our predictions on accuracy, precision and sensitivity

### Naive Random Oversampling

- Balanced accuracy score: 65%
- Precision:
High Risk: 1% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 72%, Low Risk: 59%

<img width="708" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/112814924/215303527-2310d3ab-fc63-4fc5-a62b-359cec8fcd4b.png">

### SMOTE Oversampling

- Balanced accuracy score: 66%
- Precision:
High Risk: 1% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 63%, Low Risk: 69%

<img width="708" alt="Smote Oversampling" src="https://user-images.githubusercontent.com/112814924/215303559-0e84be54-79bf-4c4e-8b35-83f1742e079e.png">

### Undersampling

- Balanced accuracy score: 54%
- Precision:
High Risk: 1% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 69%, Low Risk: 40%

<img width="708" alt="Undersampling" src="https://user-images.githubusercontent.com/112814924/215303573-39d32275-4a5f-47b7-9a22-b6bc999d8dee.png">

### SMOTEENN

- Balanced accuracy score: 64%
- Precision:
High Risk: 1% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 72%, Low Risk: 57%

<img width="709" alt="Smoteenn" src="https://user-images.githubusercontent.com/112814924/215303586-e465e053-d5d1-42e4-aa7d-230ca25e477e.png">

### Balanced Random Forest Classifier

- Balanced accuracy score: 79%
- Precision:
High Risk: 3% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 70%, Low Risk: 87%

<img width="708" alt="Random_forest" src="https://user-images.githubusercontent.com/112814924/215303685-239cbacb-1edd-4538-abad-ed289cadee8c.png">

### Easy Ensemble AdaBoost Classifier

- Balanced accuracy score: 93%
- Precision:
High Risk: 9% Low Risk: 100%
- Recall/Sensitivity:
High Risk: 92%, Low Risk: 94%

<img width="708" alt="Easy_ensemble" src="https://user-images.githubusercontent.com/112814924/215303676-d83374a2-cec2-4ee8-a613-a3c1efcf2f91.png">

# Summary 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
