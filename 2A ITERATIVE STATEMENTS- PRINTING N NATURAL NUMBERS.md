# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To create a Python program for printing `n` natural numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```python
#Reg.NO-212223060291
#Name-Thenmozhi N
#Write your Code here
n = int(input("Enter a positive integer: "))
if n <= 0:
    print("Please enter a positive integer.")
else:
    print(f"The first {n} natural numbers are:")
    for i in range(1, n + 1):
        print(i)

```
### OUTPUT
![Screenshot 2025-04-30 154120](https://github.com/user-attachments/assets/c6bfa62a-3233-4101-baf5-d8bfdf8a5ca5)
### RESULT
```
The program successfully prints the first n natural numbers using a for loop.

```

