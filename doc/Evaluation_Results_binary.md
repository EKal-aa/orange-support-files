# Evaluation_Results_binary.py
Computes a confusion matrix and the performance criteria 
- CA
- Precision
- Recall
- Specificity
- F1_score and
- MCC (Matthews correlation coefficient; https://en.wikipedia.org/wiki/Phi_coefficient)

for a binary classification.

When a learner is used to make binary classification, and when a custom decision threshold (other than 0.5) is calculated with 
feature construction widget, this script can be used to display the performance.
A custom decision theshold is sometimes desireable, when one type of wrong classification (either false positives or false negatives) 
is prefered over the other. 

doc-string:

```
* Widget input: data
    - predicted values as metas (and only this column in metas!)
    - target
    (use Select Columns Widget to shape the data accordingly)

    Classes in target and predicted must be 1 for positiv and 0 for negative class!
    Data may or may not contain features.

* Widget output: 
    - no output, results are printed in this Widget.

* Computes Confusion matrix and some more Evaluation results
  out of data with predicted values and target.
* Mainly, if predicted values are generated with Feature
  Constructor Widget with a special Threshold.
* Only for binary classification.

```

The script has no setting.
