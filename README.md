Challenge Summary

credit_risk_resampling.ipynb

The imbalanced-learn library is used to resample the data in order to build and evaluate logistic regression classifiers.

Oversample the data using the RandomOverSampler and SMOTE algorithms.
Undersample the data using the cluster centroids algorithm.
Use a combination approach with the SMOTEENN algorithm.
For each of the above:

Train a logistic regression classifier (from Scikit-learn) using the resampled data.
Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
Generate a confusion_matrix.
Print the classification report (classification_report_imbalanced from imblearn.metrics).
WI wrote a brief summary in each ipynb and analysis of the models’ performance. I describe the precision and recall scores, as well as the balanced accuracy score. All justifications for model use or no use are given.

Extension
credit_risk_ensemble.ipynb
For the extension, we trained and compared two different ensemble classifiers to predict loan risk and evaluated each model.

Train the model and generate predictions.
Calculate the balanced accuracy score.
Generate a confusion matrix.
Print the classification report (classification_report_imbalanced from imblearn.metrics).
For the BalancedRandomForestClassifier, print the feature importance, sorted in descending order (from most to least important feature), along with the feature score.
Lastly, I wrote a brief summary in each ipynb and analysis of the models’ performance, described the precision and recall scores, as well as the balanced accuracy score. All justifications for model use or no use are given.
