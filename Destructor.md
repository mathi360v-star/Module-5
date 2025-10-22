# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object no longer exists.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object no longer exists.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Demo:
    def __init__(self):
        print("Alive")
    def __del__(self):
        print("The object no longer exists")
obj=Demo()
del obj
```
## 🧪 Output
<img width="702" height="186" alt="image" src="https://github.com/user-attachments/assets/d73d2263-c86a-483b-bf0f-e753c2cfbb25" />


## Result
This project demonstrates how to implement a **destructor** in Python using a simple class is executed sucessfully.

