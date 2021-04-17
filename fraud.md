## Financial Fraud Detection

*GitHub Repository Link:* <https://github.com/mikonguyen/Fraud-Detection>

### Overview

The goal of this project was to develop a fraud detection system using machine learning models. The two machine learnings models developed in this project were Decision Tree and Random Forest models to detect fraudulent transactions.

### Results

The models were evaluated using the Precision-Recall (PR) and Area under the ROC curve (AUC) metrics for the training and test sets. 

- The Decision Tree Classifier model achieved a PR of 0.993 and AUC of 0.993 on the test set.
- The Random Forest Classifier model achieved a PR of 0.958 and AUC of 0.992 on the test set.

Comparing both the decision tree classifier and random forest classifier, the decision tree classifier has better results for both the Precision-Recall (PR) and Area under the ROC curve (AUC) metrics. 

<img src="images/fraud.png?raw=true"/> <img src="images/fraud2.png?raw=true"/>

Comparing the two confusion matrices, the difference between the two models are that the random forest classifier has more false positives with 16 samples that are predicted as fraud but are not fraud. Overall, the decision tree classifier has slightly better results. In general, both models are effective for fraud detection with high PR and AUC metrics.

### Tools Utilised
- Azure Databricks
- Spark SQL
- PySpark
- MlLib
