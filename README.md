# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon = input("Enter the name of men who stepped on the moon: ")
print(men_stepped_on_the_moon)
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 124236" src="https://github.com/user-attachments/assets/039db4eb-6cd1-4092-863e-00960c22a3be" />

## Result
Thus the program To write a Python program to read a string from the user and then print it has been executed sucessfully


# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input("Enter the real part: "))
b = int(input("Enter the imaginary part: "))
x = complex(a, b)
print("The complex number is:", x)
print("Real part:", x.real)
print("Imaginary part:", x.imag)

```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 124832" src="https://github.com/user-attachments/assets/b4228e17-3b85-4520-9b09-928fc4cae42e" />

## Result
Thus the program To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts has been executed sucessfully.


# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')

```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 125131" src="https://github.com/user-attachments/assets/328557c9-5ad4-47f8-97f8-da7a7785847e" />

## Result

Thus the program To write a Python program that prints the characters `'T'` and `'a'` using character literal has been executed sucessfully

# Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)

```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 125445" src="https://github.com/user-attachments/assets/47950c10-7803-4386-b4c0-aeff69e11588" />

## Result
Thus the program To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`  has been executed sucessfully.

# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```

a = int(input("Enter a number: "))

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```
## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-19 125649" src="https://github.com/user-attachments/assets/9496dbea-a391-48c0-aca9-df53914138d6" />
<img width="1920" height="1080" alt="Screenshot 2025-10-19 125709" src="https://github.com/user-attachments/assets/3eceea07-8dc1-4566-8af9-88c5248ddb70" />


## Result
Thus the program To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements is executed sucessfily.
