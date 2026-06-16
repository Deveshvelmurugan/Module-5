
# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
n="Emma"
class student:
    
    def __init__(self):
        self.n=n
        print("Inside Constructor\nObject initialized")
        print(f"Hello, my name is {self.n}")
    def __del__(self):
        print("Inside destructor\nObject destroyed")
s2=student()
del s2
```

### OUTPUT

<img width="548" height="230" alt="601365171-795ab4e4-b500-46ed-a9e3-2b36441c0b1c" src="https://github.com/user-attachments/assets/6567ad91-31d3-441c-b8f4-f56d49fc7adc" />

### RESULT

Thus the Python class Student with a destructor was implemented and executed successfully.

