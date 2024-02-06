# credit-risk-classification

# Purpose of the Analysis:

The objective was to develop a credit risk model for lending, crucial for companies aiming to minimize risks and make informed financial decisions.

# Financial Information:

The dataset encompassed various financial details of loans, with the target variable being "loan_status," indicating healthy (0) or high-risk (1) loans.

# Variables to Predict:

The primary focus was on predicting "loan_status," differentiating between healthy (0) and high-risk (1) loans.

# Stages of the Machine Learning Process:

1. Data Preprocessing:
Segregated features (X) and labels (y).
2. Model Training:
Employed logistic regression and oversampling for improved model training.
3. Model Evaluation:
Assessed model performance with metrics like accuracy, precision, and recall.

# Methods Used:

Logistic Regression: Trained the model on the original data.
Oversampling: Applied oversampling to address class imbalance and retrained the logistic regression model.

# Machine Learning Model 1: Logistic Regression (Original Data)

The logistic regression model performs exceptionally well in predicting both '0' (healthy loan) and '1' (high-risk loan) labels, boasting high precision and recall scores for both classes.

For '0' (healthy loan):

Precision: Close to 100%, indicating highly accurate predictions for healthy loans.
Recall: About 99%, suggesting effective identification of the majority of healthy loans.
For '1' (high-risk loan):

Precision: Approximately 86%, reflecting a relatively high level of accuracy in predicting high-risk loans.
Recall: About 91%, showcasing effective identification of a significant portion of high-risk loans.
The logistic regression model demonstrates robust performance, achieving exceptionally high precision and recall for healthy loans while maintaining a balance between precision and recall for high-risk loans.

# Machine Learning Model 2: Logistic Regression with Oversampled Data

The logistic regression model, trained with oversampled data, exhibits outstanding predictive capabilities for both '0' (healthy) and '1' (high-risk) loans. The model shows high precision, recall, and F1-scores for both classes, highlighting enhanced performance in identifying creditworthiness.

Notably, the oversampling technique significantly improves the model's ability to pinpoint high-risk loans in the imbalanced dataset.

While the precision for high-risk loans experiences a slight drop compared to the original data, the recall for both healthy and high-risk loans substantially improves. The high-risk loan achieves an impressive 0.99 recall, surpassing the original data's 0.91.

Overall, the logistic regression model, trained with oversampled data, excels in effectively predicting both healthy and high-risk loan labels.

# Conclusion
In conclusion, the analysis reveals that the logistic regression model, particularly when trained with oversampled data, showcases remarkable predictive capabilities for both healthy and high-risk loans. The models demonstrate high precision and recall, emphasizing their effectiveness in identifying creditworthiness. The oversampling technique significantly enhances the model's ability to detect high-risk loans in imbalanced datasets. Careful consideration of precision and recall trade-offs provides valuable insights for potential credit risks. The decision on model preference may depend on the specific priorities of the lending company, such as minimizing false negatives for high-risk loans. Overall, the analysis offers valuable insights into the performance of the logistic regression models in the context of credit risk classification.
