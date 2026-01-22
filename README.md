# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:

/*
Program to implement univariate Linear Regression to fit a straight line using least squares.

Developed by: Shalini.N


RegisterNumber:  212224040305
*/
```
import numpy as np
import matplotlib.pyplot as plt

x= np.array ([ 9,6,25,1.4,12,3,6,8,17,3])
y = np.array ([9.3, 10, 11,18,12,3,5,6,7,9])

ypred =1.53*x+2.88

print("x values:")
print(x)
print("y values: ")
print(y)

plt.scatter(x,y, color='Blue')
plt.plot(x,ypred, color ='pink')
plt.show()
```

## Output:
<img width="840" height="610" alt="Screenshot 2026-01-22 040319" src="https://github.com/user-attachments/assets/0d83f075-eb07-495c-ad6c-4174813e991f" />



## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
