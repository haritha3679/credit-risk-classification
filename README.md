# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credity worthiness of potential borrowers from peer-to-peer lending services
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.


* Class 0 Performance:

   - Precision and Recall: Both are extremely high (close to 1.00), indicating that the model is almost perfect in predicting class 0.
   - F1-Score: The F1-score is also 1.00, confirming the model's excellent performance for class 0.
     
* Class 1 Performance:

   - Precision (0.85): The model's ability to correctly identify positive instances of class 1 is good but not perfect.
   - Recall (0.91): The model correctly identifies 91% of the actual class 1 instances, which is quite strong.
   - F1-Score (0.88): This value suggests a good balance between precision and recall, though there's room for improvement.
   - Imbalance in Class Distribution:The support values indicate a significant class imbalance (18,765 for class 0 vs. 619 for class 1). The high performance metrics for class 0 may partially result from this
     imbalance, as the model has more examples of class 0 to learn from.
   - Overall Model Performance:
      - Accuracy (0.99): The model performs exceptionally well overall, correctly classifying 99% of the instances.
      - Macro Average vs. Weighted Average: The macro averages are slightly lower than the weighted averages due to the imbalance. The weighted average gives more importance to the majority class, hence the    higher values.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Based on these metrics, class 0 is performing better than class 1. However, this does not necessarily mean that class 0 is "better" in the context of your application. It simply indicates that your model is more effective at correctly identifying and predicting instances of class 0 compared to class 1. we might have to resolve the imbalance and resample the methods 
