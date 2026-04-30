# Implementation-of-Logistic-Regression-Using-Gradient-Descent

## AIM:
To write a program to implement the the Logistic Regression Using Gradient Descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
```
1. Start
2.Read two numbers (A, B)
3.Add A and B → Result
4.Display Result
5.Stop
 ```

## Program:
```
/*
Program to implement the the Logistic Regression Using Gradient Descent.
Developed by: 
RegisterNumber:
import numpy as np

X = np.array([1, 2, 3, 4, 5])
Y = np.array([0, 0, 0, 1, 1])

w = 0
b = 0

learning_rate = 0.1
iterations = 1000

def sigmoid(z):
    return 1 / (1 + np.exp(-z))

for i in range(iterations):
    z = w * X + b
    Y_pred = sigmoid(z)
    
    dw = np.mean((Y_pred - Y) * X)
    db = np.mean(Y_pred - Y)
    
    w = w - learning_rate * dw
    b = b - learning_rate * db

print("Weight (w):", w)
print("Bias (b):", b)

predictions = sigmoid(w * X + b)
print("Predicted Probabilities:", predictions)
print("Predicted Classes:", [1 if i > 0.5 else 0 for i in predictions])
*/
```

## Output:
<img width="702" height="99" alt="Screenshot 2026-04-30 143140" src="https://github.com/user-attachments/assets/7d12503c-a915-4f58-88d6-243fba2d912c" />



## Result:
Thus the program to implement the the Logistic Regression Using Gradient Descent is written and verified using python programming.

