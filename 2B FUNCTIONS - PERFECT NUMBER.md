# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```python
#Reg.No: 212223060291
#Name: Thenmozhi N
#Add your Code Here
def is_perfect(num):
    sum = 0
    for i in range(1, num):
        if num % i == 0:
            sum += i
    return sum == num

# Taking input from the user
n = int(input("Enter a number: "))

# Checking and printing result
if is_perfect(n):
    print(n, "is a Perfect Number.")
else:
    print(n, "is not a Perfect Number.")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/faf41618-0c3a-413f-bca0-09780c75a95d)

### RESULT
```
The program successfully checks whether the given number is a Perfect Number using a function.

```
