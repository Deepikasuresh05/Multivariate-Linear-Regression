# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1


## Program:
```
#devolped by:deepika.s
#register number:23002257


import pandas as pd
from sklearn import linear_model
df = pd.read_csv('cars.csv')
a = df[['Weight','Volume']]
b = df[['CO2']]
regr = linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))


```
## Output:

![image](https://github.com/Deepikasuresh05/Multivariate-Linear-Regression/assets/148514509/e6f36a0a-0534-4898-ad88-d11ec3c0d0ca)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
