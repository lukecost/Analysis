## 5.2.3 Goodness of Fit

Packages: seaborn, numpy, matplotlib, statsmodels, and sklearn

- statsmodels has nicer tables and is easier to specify the regression model
- sklearn is easier to use with prediction/ML

#### Suggestions:
- R2=1−SSE/TSS = The fraction of variation in y that a model can explain, and always between 0 and 1.
- Adjusted R2 adjusts R2 by penalizing based on the number of variables in X. It can actually be negative.
- ```sm_ols(<model and data>).fit().summary()``` automatically reports R2 and Adjusted R2
- when you have multiple regressors, R2 should be used instead of R because it's better with more variables.
- R2 is easier to interprit because the effect of a negative R is removed

## 5.2.4 Interpreting regression coefficients

Normal interpretation of a regression equation: “A 1 unit increase in Xi… …is associated with a bi change in y,  holding all other X constant.”

- Log transformations help show porportional relationships (percentage instead of absolute)
- Binary variables: one is 0 and the other is 1. This should make reading easy.
- continuous variables are linear equations
- catagorical variables are great for counting if something meets a condition (similar to binary, but numerous and counts a jump from group to group)
- Independent variables (x) often move together. So the marginal effect of X (i.e. β) is not the same as the total effect of X.
- keep everything a controlled expirement
- scale continuous ariables by their standard deviaiton (and only scale continuous variables, not dummy or catagorical)
- The meaning of the coefficient's magnitude depends on the corresponding variable's variation,so change in variables so that a 1 unit increase implies te same amount of mvement 


```python

```


```python

```


```python

```
