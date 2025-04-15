# SKILL STATION ACADEMY

## Algorithmic Thinking, A Mathematical Approach to Coding & Problem Solving 

**Course Instructor**: Elankovan G., IIT Madras

**Stuent Mentor**: Logesh C. 

| **Stuents On-Roll** | **Name of the Student** | **Performance Score** |
|:-------------------:|:-----------------------:|:---------------------:|
| AT01 | [Varuna R.](https://docs.google.com/document/d/1egePuRC7RQHzS0G6Safl0aegd5JV5308oNpbvUj0OJI/edit?usp=sharing) | 1/2 |
| AT02 | Prathiba P. | 2/2 | 
| AT03 |  | - |

### PROBLEM STATEMENTS

**1. LINEAR ALGEBRA SERIES**

**A. MATRICES**

- [Sum of Two Matrices](assignments/sum-of-two-matrix.md)
- [Multiplication of Two Matrices](assignments/multiplication-of-two-matrices.md)
- [Transpose of a given Matrix](assignments/transpose-of-a-given-matrix.md)
- [Determinant of a given Matrix](assignments/determinant-of-a-given-matrix.md)
- [Inverse of a given Matrix](assignments/inverse-of-a-given-matrix.md)
- [Solutions to Linear Equations using Matrix](assignments/solutions-to-linear-equations.md)

### W1-P1-QUESTION:  
Find the sum of the first \( n \) natural numbers. Given an integer \( n \), calculate the sum of all natural numbers from 1 to \( n \).  

**Example Test Cases:**  

| Input (n) | Output (Sum) |
|-----------|-------------|
| 1         | 1           |
| 5         | 15          |
| 10        | 55          |
| 20        | 210         |
| 100       | 5050        |

----------------------------------

### **W1-P2-Question:**  
Given an integer \( n \) and a critical value \( c \), determine the number of iterations required to repeatedly divide \( n \) by 2 until the result is less than or equal to \( c \).  

Each iteration consists of dividing the current value by 2. The process stops when the value becomes less than or equal to \( c \).  

### **Example Test Cases:**  

| Input (n, c) | Iterations | Explanation |
|--------------|-----------|-------------|
| 10, 1.25    | 3         | 10 → 5 → 2.5 → 1.25 (3 iterations) |
| 16, 2       | 3         | 16 → 8 → 4 → 2 (3 iterations) |
| 100, 5      | 4         | 100 → 50 → 25 → 12.5 → 6.25 (4 iterations) |
| 8, 1        | 3         | 8 → 4 → 2 → 1 (3 iterations) |

----------------------------------

### **W1-P3-Question**
Given an integer \( n \), check if it is even.  

- If \( n \) is even, print **"even"**.  

### **Example Test Cases:**  

| Input (n) | Output  |
|-----------|--------|
| 10        | even   |
| 7         | (no output) |
| 16        | even   |
| 25        | (no output) |

----------------------------------

### **W1-P4-Question** 
Given an integer \( n \), determine whether it is even or odd.  

- If \( n \) is even, print **"even"**.  
- If \( n \) is odd, print **"odd"**.  

### **Example Test Cases:**  

| Input (n) | Output  |
|-----------|--------|
| 10        | even   |
| 7         | odd    |
| 16        | even   |
| 25        | odd    |

---

### **W1-P5-Question** 
Given an integer \( n \), classify it based on its value and print the corresponding message:  

- If \( n \) is less than 10, print **"less than 10"**.  
- If \( n \) is less than 20, print **"less than 20"**.  
- If \( n \) is less than 30, print **"less than 30"**.  
- Continue this pattern up to **"less than 100"**.  

### **Example Test Cases:**  

| Input (n) | Output         |
|-----------|---------------|
| 5         | less than 10  |
| 15        | less than 20  |
| 27        | less than 30  |
| 42        | less than 50  |
| 99        | less than 100 |

---

### **W1-P6-Question** 
Given an integer \( n \) between 0 and 9, print its word representation.  

- If \( n = 0 \), print **"zero"**.  
- If \( n = 1 \), print **"one"**.  
- If \( n = 2 \), print **"two"**.  
- If \( n = 3 \), print **"three"**.  
- If \( n = 4 \), print **"four"**.  
- Continue this pattern up to 9.  

### **Example Test Cases:**  

| Input (n) | Output  |
|-----------|--------|
| 0         | zero   |
| 2         | two    |
| 4         | four   |
| 7         | seven  |
| 9         | nine   |

-----------------------

## WEEK-II

### **Question-01**  
---  
Write a program to compute the coordinates of points on the unit circle in the first quadrant. The x-coordinates should range from 0 to 1 with a step size of 0.1. Provide the output as a table of test cases. You may use any programming language.  
---  

### **Test Cases**  

| **x-coordinate** | **y-coordinate** |
|-----------------|-----------------|
| 0.0             | 1.0000          |
| 0.1             | 0.9949          |
| 0.2             | 0.9798          |
| 0.3             | 0.9539          |
| 0.4             | 0.9165          |
| 0.5             | 0.8660          |
| 0.6             | 0.8000          |
| 0.7             | 0.7141          |
| 0.8             | 0.6000          |
| 0.9             | 0.4359          |
| 1.0             | 0.0000          |

### **Question-02**

### **Problem Statement:**  
Write a program that solves a **system of two linear equations** in two variables using the given coefficients.  

Given two equations of the form:  
\[
a_1x + b_1y = c_1
\]
\[
a_2x + b_2y = c_2
\]
where \(a_1, b_1, c_1, a_2, b_2, c_2\) are provided as inputs, your task is to **compute the values of \(x\) and \(y\)** and display them as output.  

### **Input:**  
- Six numbers: \(a_1, b_1, c_1, a_2, b_2, c_2\)  

### **Output:**  
- The values of \(x\) and \(y\) that satisfy both equations.  

### **Example 1:**  
#### **Input:**  
```
1 1 5  
1 -1 1  
```
#### **Processing:**  
The equations are:  
\[
x + y = 5
\]
\[
x - y = 1
\]
Solving for \(x\) and \(y\):  
- Adding both equations:  
  \[
  (x + y) + (x - y) = 5 + 1 \Rightarrow 2x = 6 \Rightarrow x = 3
  \]
- Substituting \(x = 3\) into the first equation:  
  \[
  3 + y = 5 \Rightarrow y = 2
  \]
#### **Output:**  
```
3 2
```

---

### **Example 2:**  
#### **Input:**  
```
2 3 12  
1 -1 1  
```
#### **Processing:**  
The equations are:  
\[
2x + 3y = 12
\]
\[
x - y = 1
\]
Solving for \(x\) and \(y\):  
- Express \(x\) from the second equation:  
  \[
  x = y + 1
  \]
- Substitute into the first equation:  
  \[
  2(y + 1) + 3y = 12
  \]
  \[
  2y + 2 + 3y = 12
  \]
  \[
  5y + 2 = 12 \Rightarrow 5y = 10 \Rightarrow y = 2
  \]
- Substitute \(y = 2\) into \(x = y + 1\):  
  \[
  x = 2 + 1 = 3
  \]
#### **Output:**  
```
3 2
```

---

### **Example 3 (No Solution Case):**  
#### **Input:**  
```
1 1 2  
2 2 5  
```
#### **Processing:**  
The equations are:  
\[
x + y = 2
\]
\[
2x + 2y = 5
\]
Rewriting the second equation:  
\[
2(x + y) = 5
\]
Since \(x + y = 2\), substituting gives:  
\[
2(2) = 5
\]
which is **false**, meaning there is **no solution**.  

#### **Output:**  
```
No solution
```

---

### **Example 4 (Infinite Solutions Case):**  
#### **Input:**  
```
1 2 3  
2 4 6  
```
#### **Processing:**  
The equations are:  
\[
x + 2y = 3
\]
\[
2x + 4y = 6
\]
The second equation is just **twice** the first equation, meaning they represent the **same equation**. This leads to **infinitely many solutions**.  

#### **Output:**  
```
Infinite solutions
```

![Solve Linear Equations](https://github.com/skillstation/algorithmic-thinking/blob/main/assets/challenge-linear-equations-250401.png)

---


