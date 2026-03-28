# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

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
A=create_matrix(int(r),int(c))
B=create_matrix(int(r),int(c))
C=[]
for i in range(int(r)):
    R=[]
    for j in range(int(c)):
        item=A[i][j]-B[i][j]
        R.append(item)
    C.append(R)
print(A)
print(B)
print(C)
```

## OUTPUT:
<img width="548" height="585" alt="Screenshot 2026-03-28 084428" src="https://github.com/user-attachments/assets/c47faafa-6925-4507-8a3d-69c8d4ba0988" />


## RESULT:
Thus, the python program that reads two matrices from the user and performs matrix subtraction is executed successfully.

