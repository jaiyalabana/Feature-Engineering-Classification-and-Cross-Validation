This project focuses on building and analyzing a machine learning model that classifies emails as spam or ham (non-spam).
Using a dataset of email text and metadata, the model extracts key textual features, trains a logistic regression classifier, and evaluates its performance through metrics such as the ROC curve.
The goal is to explore how different features — such as the presence of HTML, exclamation marks, and numerical characters — influence whether an email is classified as spam.
Feature correlations were visualized using a heatmap, revealing which attributes are most predictive of spam.
A Logistic Regression model was trained using Scikit-learn.
Probabilities were computed using predict_proba, and classification thresholds were adjusted to balance false positives and false negatives.
Performance was assessed using a Receiver Operating Characteristic (ROC) Curve, visualizing the trade-off between true and false positive rates.
