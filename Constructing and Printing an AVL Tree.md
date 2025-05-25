# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[10,5,15,7,18,9]
```

## OUTPUT
![Screenshot 2025-05-19 132238](https://github.com/user-attachments/assets/da9ac513-27e3-482a-b9d7-f9e023e591db)
![Screenshot 2025-05-19 132243](https://github.com/user-attachments/assets/e3bb9fa6-eccd-46ff-aa1e-a00fec5953a7)


## RESULT
Thus a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function has been successfully implemented.
