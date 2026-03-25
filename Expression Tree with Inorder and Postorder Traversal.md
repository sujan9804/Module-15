# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```python
#Reg.no:212222060262
#Name: SUJAN S B

from binarytree import build,Node
x=['*',4,'-',5,'+',2,7]
t=build(x)
print(t.inorder)
print(t.postorder)


```

## OUTPUT
<img width="810" height="109" alt="image" src="https://github.com/user-attachments/assets/ab12b666-eeff-42f5-8864-463b56057f2e" />


## RESULT
Thus the Python program to build the given expression tree and print the inorder and postorder traversals has been implemented and executed successfully.
