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
def create_matrix(n,m): 
M = []
for i in range(n): 
row = []
for j in range(m): 
   x = int(input()) 
   row.append(x)
   M.append(row) 
   return M
r,c = input().split()
A = create_matrix(int(r),int(c))
B = create_matrix(int(r),int(c))
C = []
for i in range(int(r)): 
   R = []
for j in range(int(c)): 
   item = A[i][j]-B[i][j] 
R.append(item)
C.append(R) 
print(A) 
print(B) 
print(C)

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/ef8272fe-4ad3-42fa-b78a-2ce5d43ce9d2)

## RESULT:
Thus, the given program is implemented and executed successfully.
