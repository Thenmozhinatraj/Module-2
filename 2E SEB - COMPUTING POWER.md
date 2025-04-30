# Exp.No:2e  
## SEB - COMPUTING POWER

---

### AIM  
To write a Python program to compute the power of a given number using an appropriate built-in function.

---

### ALGORITHM

1. Begin the program.  
2. Input the base number (`base`) from the user.  
3. Input the exponent number (`exp`) from the user.  
4. Use the built-in `pow()` function to compute the base raised to the power of the exponent.  
5. Print the result using the `print()` function, displaying the power in a formatted output.  
6. Terminate the program.

---

### PROGRAM

```python
base = float(input("Enter the base number: "))
exponent = float(input("Enter the exponent: "))
result = pow(base, exponent)
print(f"{base} raised to the power of {exponent} is {result}")
```
### OUTPUT
![Screenshot 2025-04-30 155631](https://github.com/user-attachments/assets/f0703822-c105-4dde-a1b8-eb4f5efff1bd)

### RESULT
The program successfully computes the power of a given number using the pow() function.
