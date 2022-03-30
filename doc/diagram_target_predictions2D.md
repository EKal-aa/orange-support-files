# Diagram_target_predictions2D.py

doc-string:
```
* Widget input: 
- data with one feature, one target and (mandatory) one prediction (or several predictions) in Metas, only numeric values
  e.g. from test and score widget or from predictions widget)
- trained model (or several trained models) on classifier input

* Widget output: -

Usage:
* to visually show prediction performance and over-/underfitting

```

Usage in the canvas

![](images/dia_target_pred2D_01.png)

This script works only with 2D-data (with one feature, one target and (mandatory) one prediction (or several predictions) in Metas.

![](images/dia_target_pred2D_02.png)

## prediction_model = 1

```
######################################################
# Settings:
prediction_model = 1         # Standard 1 for 1 connected model or the first connected model; 
#                              otherwise number of model, whose predictions should be shown
#####################################################
```

![](images/dia_target_pred2D_03.png)

## prediction_model = 2

```
######################################################
# Settings:
prediction_model = 2         # Standard 1 for 1 connected model or the first connected model; 
#                              otherwise number of model, whose predictions should be shown
#####################################################
```

![](images/dia_target_pred2D_04.png)







