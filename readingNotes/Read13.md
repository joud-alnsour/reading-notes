# Linear Regression
Regression analysis explores the relationship between a quantitative response variable and one or more explanotory variables.

**How to implement Linear Regression**<br>
1-Import packages and classes
```
import numpy as np
from sklearn.linear_model import LinearRegression
```
2- Provide Data
```
x = np.array([5, 15, 25, 35, 45, 55]).reshape((-1, 1))
y = np.array([5, 20, 14, 32, 22, 38])
```
3-Create a model and fit it
```
model = LinearRegression()
```
4-Get Results
```
r_sq = model.score(x, y)
```
5-Predict Response
```
y_pred = model.predict(x)
```
## Scikit-learn
```
%matplotlib inline

import numpy as np
import pandas as pd
import scipy.stats as stats
import matplotlib.pyplot as plt
import sklearn
```

## linear regression object
```
from sklearn.linear_model import LinearRegression
lm = LinearRegression()
```
## Fit Linear Model
```
lm.fig(DF, dataColumn)

import numpy as np
from sklearn.linear_model import LinearRegression

# Create Model
model = LinearRegression()
model = LinearRegression().fit(x, y) # one line fit

# Coefficient
r_sq = model.score(x, y)

# Predict Response
y_pred = model.predict(x)
```
**Model Methods**
- model.fit()
- model.intercept_
- model.coef_
- model.predict(x)

## Scatter Plot
```
plt.scatter(x, y)
plt.xlabel('string')
plt.ylabel('string')
ptl.title('string')
plt.show()
```

## test_train_split
- from sklearn.model_selection import train_test_split
x_train, x_test, y_train, y_test = sklearn.cross_validation.train_test_split(x, y, test_size=0.33, random_state=5)

## Polynomial Regression
```
from sklearn.preprocessing import PolynomialFeatures
transformer = PolynomialFeatures(degree=2, include_bias=False)

# Modify X array
x_ = transformer.transform(x)
```