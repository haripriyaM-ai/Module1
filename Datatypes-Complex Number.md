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
