# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

f = lambda a, b: a + b
print("The sum is:", f(a, b))

```

## Output
![alt text](<Screenshot 2025-10-19 140909.png>)
## Result
The program successfully defines and executes a lambda function that adds two numbers and displays the result.