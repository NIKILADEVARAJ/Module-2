# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print("Result of", a, "%", b, "is:", a % b)
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
result(num1, num2)
```

## Output
![image](https://github.com/user-attachments/assets/dd85ab61-f715-4c52-abd3-e84ea92cbb28)

## Result
The program successfully reads two values from the user, computes the modulo using the % operator, and displays the result through a function.
