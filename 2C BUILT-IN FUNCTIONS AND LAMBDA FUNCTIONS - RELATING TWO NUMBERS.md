# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```python
compare = lambda a, b: "a is greater than b" if a > b else ("a is equal to b" if a == b else "a is smaller than b")
a = int(input("Enter first number (a): "))
b = int(input("Enter second number (b): "))
print(compare(a, b))
```

### OUTPUT

![image](https://github.com/user-attachments/assets/391e3b8f-f676-476a-9163-d88000c4bac7)

### RESULT

```
The program successfully compares two numbers using a lambda function and displays their relationship.
```
