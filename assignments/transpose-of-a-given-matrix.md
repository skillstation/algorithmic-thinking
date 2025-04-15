
# 🧮 Matrix Operations – Programming Questions

## 1. Addition of Two Matrices

**Question:**

Write a program in any programming language of your choice to add two matrices of the same size. The program should:

1. Take two matrices as input.
2. Add the corresponding elements.
3. Output the resulting matrix.
4. Include at least two test cases.

**Example:**

If the input matrices are:

```
Matrix A = [[1, 2], 
            [3, 4]]

Matrix B = [[5, 6], 
            [7, 8]]
```

The output should be:

```
Result = [[6, 8],
          [10, 12]]
```

**Hint:**  
Use nested loops to iterate through each row and column. Ensure both matrices have the same dimensions before performing addition.

---

## 2. Multiplication of Two Matrices

**Question:**

Write a program in any programming language of your choice to multiply two matrices. The program should:

1. Take two matrices as input.
2. Perform matrix multiplication (not element-wise).
3. Output the resulting matrix.
4. Include at least two test cases.

**Example:**

If the input matrices are:

```
Matrix A = [[1, 2], 
            [3, 4]]

Matrix B = [[5, 6], 
            [7, 8]]
```

The output should be:

```
Result = [[19, 22],
          [43, 50]]
```

**Hint:**  
Matrix multiplication is valid only if the number of columns in the first matrix equals the number of rows in the second matrix. Use three nested loops to calculate the result.

---

## 3. Transpose of a Matrix

**Question:**

Write a program in any programming language of your choice to find the **transpose** of a given matrix. The program should:

1. Take a matrix as input.
2. Compute its transpose.
3. Output the transposed matrix.
4. Include at least two test cases.

**Example:**

If the input matrix is:

```
Matrix A = [[1, 2, 3], 
            [4, 5, 6]]
```

The output should be:

```
Transpose = [[1, 4],
             [2, 5],
             [3, 6]]
```

**Hint:**  
In a transpose, the rows become columns and the columns become rows. So the element at position `(i, j)` becomes `(j, i)`.

---
