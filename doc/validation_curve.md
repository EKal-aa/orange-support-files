# Validation_curve.py

doc-string

```
* Widget input: data and some learners
* Widget output: -

* Computes and shows validation curve for connected learners out of cross validation.
* Uses standard error to indicate variability of the results.
* Scores are CA (classification accuracy) for classification and R_squared (R2) or RMSE for regression.
* Uses names of connected learners as x-labels.

Usage: 
* mainly to compare different learner settings for manual hyper parameter optimization.
* e.g. several learners of the same type, but with different values of a certain hyper parameter
* Use name in learner widget to indicate different learners

```

Settings

```
##########################################################################
# Settings:
k = 5                       # number of folds
problem = "reg"             # "class": classification or "reg": Regression
score = "MSE"               # "R2" or "MSE"; only for regression
save_results = False        # True: save Excelfile with results; False: don't save
file_path = "E:/Downloads/" # file path for save_results
#                             e.g. "E:/Downloads/" - with slash (!) also in Windows (and trailing slash)
replicable = False          # WARNING: if using replicable=True, make sure to use shuffled data!
###########################################################################

```

## Usage in the canvas
It is possible to realise a variation of hyperparameters (as shown here; number of neighbors is varied) to produce a validation curve. It is also possible to just compare some different learners, e.g. linear regression, kNN and AdaBoost,  in the diagram. 

In the diagram, the names of the learners as defined in the learner widget are used.

![](images/validation_curve_02.png)

## score = "R2"

![](images/validation_curve_03.png)

## score = "MSE"

![](images/validation_curve_04.png)

## problem = "class"

For classification problems, classification accuracy (CA) is used as performance criterion in the diagram.



