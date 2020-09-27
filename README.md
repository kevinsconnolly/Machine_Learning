Challenge Summary
credit_risk_resampling.ipynb
the imbalanced-learn library is used to resample the data in order to build and evaluate logistic regression classifiers.

Oversample the data using the RandomOverSampler and SMOTE algorithms.
Undersample the data using the cluster centroids algorithm.
Use a combination approach with the SMOTEENN algorithm.
For each of the above:

Train a logistic regression classifier (from Scikit-learn) using the resampled data.
Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
Generate a confusion_matrix.
Print the classification report (classification_report_imbalanced from imblearn.metrics).
We wrote a brief summary and analysis of the models’ performance. In the analysis, we described the precision and recall scores, as well as the balanced accuracy score. Also included is a final recommendation on the model to use, if any. If we did not recommend any of the models, we justified our reasoning.

Extension
credit_risk_ensemble.ipynb
For the extension, we trained and compared two different ensemble classifiers to predict loan risk and evaluated each model.

Train the model and generate predictions.
Calculate the balanced accuracy score.
Generate a confusion matrix.
Print the classification report (classification_report_imbalanced from imblearn.metrics).
For the BalancedRandomForestClassifier, print the feature importance, sorted in descending order (from most to least important feature), along with the feature score.
Lastly, we wrote a brief summary and analysis of the models’ performance, described the precision and recall scores, as well as the balanced accuracy score. Additionally, a final recommendation on the model to use, if any. If we did not recommend any of the models, we justified our reasoning.
