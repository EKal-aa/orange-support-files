# PolyFeatures.py

docstring

```
* Widget input: data (only numerical features are used; categorical features are filtered out)
* Widget output: data with additinal features, generated as polynomial combinations of the features

Usage:
* Create additional features to use linear regression for modeling nonlinear functions
* Use to show the effect of model complexity on overfitting the data

```

Usage in the canvas

![](images/polyfeatures_01.png)

## Data befor transformation with PolyFeatures

![](images/polyfeatures_02.png)

## Data after transformation with PolyFeatures
with the following settings
```
###########################################################
# Settings:
degree = 2     # maximal degree of the polynomial features
###########################################################
```

![](images/polyfeatures_03.png)

Tree additional features, generated as polynomial combinations of the two original features.





