# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
class Program:
    def __init__(self, first,d,last):
        self.first = first
        self.d = d
        self.last=last
    def display(self):
        L=[i for i in range(self.first,self.last+1,self.d)]
        return L


a=int(input())
b=int(input())
c=int(input())
Series = Program(a,b,c+1)
print(Series.display())
```

## OUTPUT:
<img width="566" height="291" alt="Screenshot 2026-03-28 081308" src="https://github.com/user-attachments/assets/3a0c8ff1-f678-499f-9f90-7b2a70be0150" />


## RESULT:

Thus, the python program that generates all even numbers between 200 and 300 using list comprehension is executed successfully.
