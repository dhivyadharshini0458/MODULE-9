# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
def create_matrix(n,m):
    M=[]
    for i in range(n):
        row=[]
        for j in range(m):
            x=int(input())
            row.append(x)
        M.append(row)
    return M 
    
r,c=input().split()
r=int(r)
c=int(c)
A=create_matrix(r,c)
print(A)
T = [[r[i] for r in A] for i in range(len(A[0]))]
print(T)
```

## OUTPUT:
<img width="553" height="347" alt="Screenshot 2026-03-28 081447" src="https://github.com/user-attachments/assets/b844e671-4835-4522-9591-1b2b1ccf86a4" />


## RESULT:
Thus, the python program to compute the transpose of a matrix using list comprehension is executed successfully.


