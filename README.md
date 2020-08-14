# Machine-Learning-Challenge
GT-DSBC-HW-W21


Reporting


✓ README compares each of
the models’ performances and
predictions

Before Hyperparameter Tuning, the performance of the Random Forest model was better than the Support Vector Machine model.
The Random Forest model had a Testing Data Score of 0.8970.
The Support Vector Machine model had a Testing Data Score of 0.8421.

After Hyperparameter Tuning, the best score from the Grid Search was 0.8812 for the Random Forest model and 0.85334 for the Support Vector Machine model.
Both are over the 85% threshold.



✓ README summarizes the
findings and makes assumptions
based on the data and their
models.

The Random Forest model was extremely good with predicting False Positives - with precision of 0.99, and a recall and f1-score of 1.00.
The Random Forest model's weakest category was predicting Candidates. For Candidates, it had an f1-score of .78.
Similar to the Random Forest model, the Support Vector Machine model was extremely good with predicting False Positives - with precision of 0.99, a recall of 1.00, and f1-score of 99.
Similar to the Random Forest model, the Support Vector Machine model's weakest category was predicting Candidates. For Candidates, it had an f1-score of .66.
Both models would be valid to use to make predictions.



✓ README discusses the
predictions of the possible
exoplanets with their models

The predictions of the possible explanets with each model is over the 85% accuracy thresholds, and thus both sets of predictions should be worthwhile to use for the intended purpose.