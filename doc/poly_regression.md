# Poly_Regression.py

doc-string

```
* Widget input: 
    - (optional) data 
    - (optional) preprocessors on object-input

* Widget output: 
    - learner on learner-output, if no data on input
    - learner and trained model on classifier-output, if data on input

* Creates a learner for polynomial regression, which can be used e.g. in Test and Score-Widget
* Additionally creates a trained model, if training data is connectet to data-input, e.g. for Predictions-Widget

```

Settings
```
########################################################
# Settings:
name="Linear Regression"  # Name of the learner/model in other widgets, e.g. Test and Score
degree = 3                # maximal degree of the polynomial features
fit_intercept = True      # 
type = "0"                # 0: ordinary Least square 
                          # 1: Lasso (L1-Regularization)
                          # 2: Ridge (L2-Regularization)
alpha = 0.0001            # parameter alpha for L1- and L2-Regularization only
########################################################

```

Usage in the canvas

![](images/poly_reg_01.png)
