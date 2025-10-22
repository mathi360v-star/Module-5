## Constructors in Python: show Student Name and id using constructors
## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor**,which will take the name and userid of the person as parameters print the userid  of the person.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `display` show the name and userid of the person as parameters print the userid  of the person
5. **Execute the Program**: Instantiate the `Student` class and call the `display` method.

## 🧾 Program
```
class Student:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
        self.display()
    def display(self):
        print(self.userid)
name=input()
userid=input()
obj = Student(name,userid)
obj.display()      
```


## Output

## Result
The Python program that creates a **Student** class with a **default constructor**,which will take the name and userid of the person as parameters print the userid  of the person.


