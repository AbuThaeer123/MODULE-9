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
class program:
def init (self,a,b,c):
self.a=a self.b=b 
self.c=c
def display(self):
even = [i for i in range(self.a,self.c+1,self.b)] 
print(even)
a = int(input())
b = int(input())
c = int(input())
obj =
program(a,b,c) 
obj.display()
```
## OUTPUT:
<img width="746" height="126" alt="image" src="https://github.com/user-attachments/assets/0071a81c-1511-4abf-b738-3c93c67f8a49" />

## RESULT:
Thus, the given program is implemented and executed successfully.
