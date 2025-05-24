## MODULE-1
# EXP 1: Datatypes-Boolean Expression Evaluation in Python

## Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## Algorithm
1. Set variable `a` to the result of the expression `11 == True`.
2. Set variable `b` to the result of the expression `5 == False`.
3. Set variable `c` to the result of the expression `True + 54`.
4. Set variable `d` to the result of the expression `False + 7`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## Program
```
a =(11==True)
b =(5==False)
c =True + 54
d =False + 7
print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output
![Screenshot 2025-05-21 140629](https://github.com/user-attachments/assets/12b68cfc-86f2-428b-93d3-2d811d935368)


## Result
Thus, the program is verified successfully.

---
# EXP 2: Conditional Statements in Python: Even or Odd Checker

## Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## Program
```
n=input())
a=int(n)
if a%2!=0:
    print("ODD") 
else:
    print("EVEN")

```
## Output
![Screenshot 2025-05-21 130015](https://github.com/user-attachments/assets/748b6c5e-20b9-442c-bc53-630f0a281953)

## Result
Thus, the program is verified successfully.

---

# EXP 3: Datatypes-Character Literal in Python

##  Aim
To write a Python program that prints the characters `'V'` and `'c'` using character literals.

## Algorithm
1. Print the character `'V'`.
2. Print the character `'c'`.

## Program
```
v='V'
w="c"
print(v)
print(w)
```
## Output
![image](https://github.com/user-attachments/assets/cb5698e4-8ec5-48e7-bf96-3c60922adfab)

## Result
Thus, the program is verified successfully.

---

# EXP 4: Datatypes-Complex Number Creation in Python

## Aim
To write a Python program that reads two integers, create a complex number using them, and then prints the complex number along with its real and imaginary parts.

##  Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## Program
```
a=int(input())
b=int(input())
x=complex(a,b)
x.real=float(a)
x.imag=float(b)
print(x)
print(x.real)
print(x.imag)
```
## Output
![image](https://github.com/user-attachments/assets/eac85e13-ac9b-4228-9138-02bf15889348)

## Result
Thus, the program is verified successfully.

---

# EXP 5: Datatypes-Read and Print a String in Python

## Aim
To write a Python program to read a string from the user and then print it.

## Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## Program
```
men_stepped_on_the_moon = input()
print(men_stepped_on_the_moon)
```
## Output
![image](https://github.com/user-attachments/assets/3605704e-4233-4f90-8e6c-32a5dfd7fef9)

## Result
Thus, the program is verified successfully.
