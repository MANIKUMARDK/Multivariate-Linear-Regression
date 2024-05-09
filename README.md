# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1
Import pandas as pd and from sklearn import linear_model

## Step2
Read the csv file from the drive

## Step3
Drive the required list from the file

## Step4
Print the list of the program

## Step5
End the program

## Program:
```
#Python program to implement multivariate linear regression and predict the output.
#Developed by: MANIKUMAR DK
#Register Number: 212223230121

import pandas as pd
from sklearn import linear_model

df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))






```
## Output:

### Insert your output
![image](https://github.com/MANIKUMARDK/Multivariate-Linear-Regression/assets/147215581/56742497-9649-4fbc-b66a-9fa46671051f)
![Screenshot 2024-05-09 134803](https://github.com/MANIKUMARDK/Multivariate-Linear-Regression/assets/147215581/27370eb3-c323-4287-8bb6-0fd26b8cc549)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
