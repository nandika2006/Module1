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

## 💻 Program :

    real_part = int(input("Enter the real part: "))
    imag_part = int(input("Enter the imaginary part: "))
    z = complex(real_part, imag_part)
    print("The complex number is:", z)
    print("Real part:", z.real)
    print("Imaginary part:", z.imag)

## Output :

<img width="956" height="390" alt="image" src="https://github.com/user-attachments/assets/fc99c310-95e2-4905-a212-1cf65e5d5f4c" />

## Result :
The Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts is executed successfully.
