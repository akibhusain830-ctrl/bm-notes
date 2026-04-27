# 📐 BUSINESS MATHEMATICS — COMPLETE NOTES
## B.Com 2nd Semester | Gauhati University | 30 Marks
## All 4 Topics: Determinants | Matrices | Linear Programming | Functions & Differentiation

---

# 📌 TOPIC 1: DETERMINANTS

---

## 🔷 What is a Determinant?

Every **square matrix** (same number of rows and columns) has a special number associated with it called its **determinant.**

A determinant is written as **|A|** or **det(A)**.

> Think of a determinant as a **single number that summarises an entire matrix.** It tells us important things about the matrix — like whether it can be inverted, and whether a system of equations has a unique solution.

---

## 🔷 Notation

If A is a matrix:
```
A = | a  b |
    | c  d |
```
Its determinant is written as:
```
|A| = | a  b |
      | c  d |
```

---

## 🔷 DETERMINANT OF A 1×1 MATRIX

If A = [a], then **|A| = a**

> **Example:** A = [5] → |A| = 5

---

## 🔷 DETERMINANT OF A 2×2 MATRIX

### Formula:
```
If A = | a  b |
       | c  d |

|A| = (a × d) - (b × c)
```

### 🧠 Easy Memory Trick:
**"Multiply diagonally — Top-left × Bottom-right MINUS Top-right × Bottom-left"**

```
| a  b |    ↘  ↗
| c  d |   ad - bc
```

---

### ✅ SOLVED EXAMPLES — 2×2 Determinants

**Example 1:**
```
Find the determinant of A = | 3  4 |
                             | 2  5 |

Solution:
|A| = (3 × 5) - (4 × 2)
    = 15 - 8
    = 7  ✓
```

---

**Example 2:**
```
Find |A| if A = | 6   2 |
                | 3   4 |

Solution:
|A| = (6 × 4) - (2 × 3)
    = 24 - 6
    = 18  ✓
```

---

**Example 3:**
```
Find |A| if A = | -2   3 |
                |  4  -1 |

Solution:
|A| = (-2 × -1) - (3 × 4)
    = 2 - 12
    = -10  ✓
```

---

**Example 4 (with zero):**
```
Find |A| if A = | 5  0 |
                | 0  3 |

Solution:
|A| = (5 × 3) - (0 × 0)
    = 15 - 0
    = 15  ✓
```

---

## 🔷 DETERMINANT OF A 3×3 MATRIX

### Matrix Structure:
```
A = | a₁  b₁  c₁ |
    | a₂  b₂  c₂ |
    | a₃  b₃  c₃ |
```

### Method: EXPANSION ALONG FIRST ROW

We expand using the first row elements with **alternating signs (+, -, +)**:

```
|A| = a₁ × M₁₁ - b₁ × M₁₂ + c₁ × M₁₃
```

Where M₁₁, M₁₂, M₁₃ are the **2×2 minor determinants** obtained by deleting the row and column of that element.

---

### 🔷 Step-by-Step Method:

**STEP 1:** Take first element of Row 1 → **a₁** → Sign = **+**
Delete Row 1 and Column 1 → remaining 2×2 matrix → find its determinant (M₁₁)

**STEP 2:** Take second element of Row 1 → **b₁** → Sign = **−**
Delete Row 1 and Column 2 → remaining 2×2 matrix → find its determinant (M₁₂)

**STEP 3:** Take third element of Row 1 → **c₁** → Sign = **+**
Delete Row 1 and Column 3 → remaining 2×2 matrix → find its determinant (M₁₃)

**STEP 4:**
```
|A| = (+a₁)(M₁₁) + (−b₁)(M₁₂) + (+c₁)(M₁₃)
```

---

### 🔷 Sign Pattern for 3×3:
```
+ − +
− + −
+ − +
```

---

### ✅ SOLVED EXAMPLES — 3×3 Determinants

**Example 1:**
```
Find |A| if A = | 1  2  3 |
                | 4  5  6 |
                | 7  8  9 |

Step 1: Expand along Row 1

|A| = +1 × | 5  6 |  - 2 × | 4  6 |  + 3 × | 4  5 |
           | 8  9 |         | 7  9 |         | 7  8 |

Step 2: Calculate each 2×2 determinant

M₁₁ = | 5  6 | = (5×9) - (6×8) = 45 - 48 = -3
       | 8  9 |

M₁₂ = | 4  6 | = (4×9) - (6×7) = 36 - 42 = -6
       | 7  9 |

M₁₃ = | 4  5 | = (4×8) - (5×7) = 32 - 35 = -3
       | 7  8 |

Step 3: Final calculation

|A| = 1×(-3) - 2×(-6) + 3×(-3)
    = -3 + 12 - 9
    = 0  ✓
```
> Note: When determinant = 0, the matrix is called **SINGULAR** (it has no inverse)

---

**Example 2:**
```
Find |A| if A = | 2  1  3 |
                | 0  4  2 |
                | 1  0  5 |

Expand along Row 1:

M₁₁ = | 4  2 | = (4×5) - (2×0) = 20 - 0 = 20
       | 0  5 |

M₁₂ = | 0  2 | = (0×5) - (2×1) = 0 - 2 = -2
       | 1  5 |

M₁₃ = | 0  4 | = (0×0) - (4×1) = 0 - 4 = -4
       | 1  0 |

|A| = +2×(20) - 1×(-2) + 3×(-4)
    = 40 + 2 - 12
    = 30  ✓
```

---

**Example 3:**
```
Find |A| if A = | 1   0   2 |
                | 3  -1   4 |
                | 2   1  -2 |

M₁₁ = | -1   4 | = (-1×-2) - (4×1) = 2 - 4 = -2
       |  1  -2 |

M₁₂ = |  3   4 | = (3×-2) - (4×2) = -6 - 8 = -14
       |  2  -2 |

M₁₃ = |  3  -1 | = (3×1) - (-1×2) = 3 + 2 = 5
       |  2   1 |

|A| = +1×(-2) - 0×(-14) + 2×(5)
    = -2 - 0 + 10
    = 8  ✓
```

---

## 🔷 PROPERTIES OF DETERMINANTS

### Property 1: Reflection Property
**If all rows and columns are interchanged (transpose), the determinant remains the same.**
```
|A| = |Aᵀ|
```

### Property 2: Zero Row/Column Property
**If all elements of any row or column are zero, the determinant = 0.**
```
| 0  0  0 |
| 3  4  5 | = 0
| 1  2  6 |
```

### Property 3: Identical Row/Column Property
**If two rows or two columns are identical, the determinant = 0.**
```
| 1  2  3 |
| 1  2  3 | = 0   (Row 1 = Row 2)
| 4  5  6 |
```

### Property 4: Scalar Multiple Property
**If all elements of a row/column are multiplied by k, the determinant is multiplied by k.**
```
| ka  kb  kc |         | a  b  c |
| d    e   f  | = k ×  | d  e  f |
| g    h   i  |         | g  h  i |
```

### Property 5: Row/Column Swap Property
**If two rows or columns are interchanged, the sign of the determinant changes.**

### Property 6: Determinant of Identity Matrix
**The determinant of any Identity Matrix = 1**

### Property 7: Product Rule
**|AB| = |A| × |B|**

---

## 🔷 APPLICATION: SOLVING EQUATIONS USING CRAMER'S RULE

Cramer's Rule uses determinants to solve a **system of linear equations.**

### For 2 equations with 2 unknowns:
```
a₁x + b₁y = c₁
a₂x + b₂y = c₂
```

**Formula:**
```
        |c₁  b₁|           |a₁  c₁|
        |c₂  b₂|           |a₂  c₂|
x = ─────────────    y = ─────────────
        |a₁  b₁|           |a₁  b₁|
        |a₂  b₂|           |a₂  b₂|

Let D = |a₁  b₁|   Dx = |c₁  b₁|   Dy = |a₁  c₁|
        |a₂  b₂|         |c₂  b₂|         |a₂  c₂|

Then:  x = Dx/D     y = Dy/D
```

---

### ✅ SOLVED EXAMPLE — Cramer's Rule

**Example:**
```
Solve:  3x + 2y = 7
        x  - y  = 1

Step 1: Find D (main determinant)
D = | 3   2 | = (3×-1) - (2×1) = -3 - 2 = -5
    | 1  -1 |

Step 2: Find Dx (replace x-column with constants)
Dx = | 7   2 | = (7×-1) - (2×1) = -7 - 2 = -9
     | 1  -1 |

Step 3: Find Dy (replace y-column with constants)
Dy = | 3   7 | = (3×1) - (7×1) = 3 - 7 = -4
     | 1   1 |

Step 4: Calculate x and y
x = Dx/D = -9/-5 = 9/5 = 1.8
y = Dy/D = -4/-5 = 4/5 = 0.8

Verification:
3(1.8) + 2(0.8) = 5.4 + 1.6 = 7 ✓
(1.8) - (0.8) = 1 ✓
```

---

---

# 📌 TOPIC 2: MATRICES

---

## 🔷 What is a Matrix?

A **matrix** is a **rectangular arrangement of numbers (or elements)** organised into **rows and columns**, enclosed in brackets.

```
A = [ 1   2   3 ]
    [ 4   5   6 ]
```

This is a **2×3 matrix** (2 rows, 3 columns).

The **order** (size) of a matrix = **rows × columns**

Each number in the matrix is called an **element** or **entry.**
The element in Row i, Column j is written as **aᵢⱼ**

---

## 🔷 TYPES OF MATRICES

### 1. 📦 Row Matrix
Has **only 1 row.**
```
A = [1  2  3  4]     Order: 1×4
```

### 2. 📦 Column Matrix
Has **only 1 column.**
```
A = [ 2 ]
    [ 5 ]     Order: 3×1
    [ 8 ]
```

### 3. 📦 Square Matrix
Number of **rows = Number of columns.**
```
A = [ 1  2 ]     Order: 2×2
    [ 3  4 ]
```

### 4. 📦 Zero / Null Matrix
**All elements are 0.**
```
O = [ 0  0 ]
    [ 0  0 ]
```

### 5. 📦 Identity / Unit Matrix (I)
A **square matrix** where all **diagonal elements are 1** and all others are 0.
```
I = [ 1  0  0 ]
    [ 0  1  0 ]
    [ 0  0  1 ]
```
> Property: A × I = I × A = A (Identity matrix is like the number 1 in multiplication)

### 6. 📦 Diagonal Matrix
A square matrix where **all non-diagonal elements are 0.**
```
A = [ 3  0  0 ]
    [ 0  5  0 ]
    [ 0  0  8 ]
```

### 7. 📦 Scalar Matrix
A diagonal matrix where **all diagonal elements are equal.**
```
A = [ 4  0 ]
    [ 0  4 ]
```

### 8. 📦 Symmetric Matrix
**A = Aᵀ** (the matrix equals its own transpose)
```
A = [ 1  2  3 ]
    [ 2  4  5 ]
    [ 3  5  6 ]
```

### 9. 📦 Triangular Matrices
- **Upper Triangular:** All elements BELOW the diagonal are 0
- **Lower Triangular:** All elements ABOVE the diagonal are 0

```
Upper:  [ 1  2  3 ]     Lower:  [ 1  0  0 ]
        [ 0  4  5 ]             [ 2  4  0 ]
        [ 0  0  6 ]             [ 3  5  6 ]
```

### 10. 📦 Transpose of a Matrix (Aᵀ)
**Rows become columns and columns become rows.**
```
If A = [ 1  2  3 ]     then Aᵀ = [ 1  4 ]
       [ 4  5  6 ]               [ 2  5 ]
                                  [ 3  6 ]
```

---

## 🔷 MATRIX OPERATIONS

---

### ➕ ADDITION OF MATRICES

**Rule:** Matrices must have the **SAME ORDER** to be added.
Add the **corresponding elements.**

**Formula:**
```
If A = [aᵢⱼ] and B = [bᵢⱼ], then A+B = [aᵢⱼ + bᵢⱼ]
```

### ✅ SOLVED EXAMPLE — Matrix Addition

**Example 1:**
```
A = [ 1  2 ]     B = [ 5  6 ]
    [ 3  4 ]         [ 7  8 ]

A + B = [ 1+5   2+6 ]  =  [ 6   8 ]
        [ 3+7   4+8 ]     [ 10  12 ]  ✓
```

**Example 2:**
```
A = [ 2   -1   3 ]     B = [ 1   4   -2 ]
    [ 0    5   1 ]         [ 3  -2    6 ]

A + B = [ 2+1   -1+4   3+(-2) ]  =  [ 3   3   1 ]
        [ 0+3    5-2    1+6   ]     [ 3   3   7 ]  ✓
```

---

### ➖ SUBTRACTION OF MATRICES

**Rule:** Same order required. Subtract corresponding elements.

### ✅ SOLVED EXAMPLE — Matrix Subtraction

**Example:**
```
A = [ 8   5 ]     B = [ 3   1 ]
    [ 2   9 ]         [ 4   6 ]

A - B = [ 8-3   5-1 ]  =  [ 5   4 ]
        [ 2-4   9-6 ]     [ -2  3 ]  ✓
```

---

### ✖️ SCALAR MULTIPLICATION

**Rule:** Multiply EVERY element of the matrix by the scalar (number).

### ✅ SOLVED EXAMPLE — Scalar Multiplication

**Example:**
```
k = 3,   A = [ 1   2 ]
             [ -1  4 ]

3A = [ 3×1    3×2  ]  =  [ 3    6 ]
     [ 3×(-1) 3×4  ]     [ -3  12 ]  ✓
```

---

### ✖️ MATRIX MULTIPLICATION

This is the most important operation. **Pay careful attention.**

**Rule for Multiplication:**
> Matrix A (m×n) can be multiplied by Matrix B (n×p) ONLY IF the **number of columns in A = number of rows in B.**
> The result will be a matrix of order **m×p.**

```
A(m×n) × B(n×p) = C(m×p)
    ↑         ↑
  must be equal!
```

**How to multiply:**
Each element Cᵢⱼ = **Sum of products of Row i of A with Column j of B**

---

### ✅ SOLVED EXAMPLES — Matrix Multiplication

**Example 1: (2×2) × (2×2)**
```
A = [ 1  2 ]     B = [ 5  6 ]
    [ 3  4 ]         [ 7  8 ]

C = A × B

C₁₁ = Row1 of A × Col1 of B = (1×5) + (2×7) = 5 + 14 = 19
C₁₂ = Row1 of A × Col2 of B = (1×6) + (2×8) = 6 + 16 = 22
C₂₁ = Row2 of A × Col1 of B = (3×5) + (4×7) = 15 + 28 = 43
C₂₂ = Row2 of A × Col2 of B = (3×6) + (4×8) = 18 + 32 = 50

C = [ 19  22 ]  ✓
    [ 43  50 ]
```

---

**Example 2: (2×3) × (3×2)**
```
A = [ 1  0  2 ]     B = [ 3  1 ]
    [ 4  1  0 ]         [ 2  0 ]
                         [ 1  4 ]

Order check: A is 2×3, B is 3×2 → Result will be 2×2 ✓

C₁₁ = (1×3)+(0×2)+(2×1) = 3+0+2 = 5
C₁₂ = (1×1)+(0×0)+(2×4) = 1+0+8 = 9
C₂₁ = (4×3)+(1×2)+(0×1) = 12+2+0 = 14
C₂₂ = (4×1)+(1×0)+(0×4) = 4+0+0 = 4

C = [  5   9 ]  ✓
    [ 14   4 ]
```

---

**Example 3: (1×3) × (3×1)**
```
A = [1  2  3]     B = [ 4 ]
                       [ 5 ]
                       [ 6 ]

C = (1×4) + (2×5) + (3×6) = 4 + 10 + 18 = [32]  ✓
```

---

## 🔷 INVERSE OF A MATRIX

### What is the Inverse?

The **inverse of matrix A** (written as **A⁻¹**) is a matrix such that:
```
A × A⁻¹ = A⁻¹ × A = I (Identity Matrix)
```

> Think of it like: just as 5 × (1/5) = 1, a matrix times its inverse = Identity.

**A matrix has an inverse ONLY IF its determinant ≠ 0** (non-singular matrix).

---

### 🔷 Finding Inverse of a 2×2 Matrix

**Formula:**
```
If A = | a  b |    and |A| = ad - bc ≠ 0
       | c  d |

A⁻¹ = ──────── ×  |  d  -b |
       (ad - bc)   | -c   a |
```

**Steps:**
1. Find the determinant |A| = ad - bc
2. Swap the diagonal elements (a and d swap positions)
3. Change signs of off-diagonal elements (b and c become -b and -c)
4. Divide everything by |A|

---

### ✅ SOLVED EXAMPLES — Inverse of 2×2 Matrix

**Example 1:**
```
Find A⁻¹ if A = | 3  1 |
                | 5  2 |

Step 1: |A| = (3×2) - (1×5) = 6 - 5 = 1

Step 2: Swap and sign change:
         |  2  -1 |
         | -5   3 |

Step 3: A⁻¹ = (1/1) × |  2  -1 | = |  2  -1 |
                        | -5   3 |   | -5   3 |

Verification: A × A⁻¹ = | 3  1 | × |  2  -1 |
                         | 5  2 |   | -5   3 |

= | (6-5)  (-3+3) | = | 1  0 | = I ✓
  | (10-10) (-5+6)|   | 0  1 |
```

---

**Example 2:**
```
Find A⁻¹ if A = | 4  7 |
                | 2  6 |

Step 1: |A| = (4×6) - (7×2) = 24 - 14 = 10

Step 2: A⁻¹ = (1/10) × |  6  -7 |
                         | -2   4 |

A⁻¹ = | 6/10   -7/10 | = | 0.6   -0.7 |  ✓
      | -2/10   4/10 |   | -0.2   0.4 |
```

---

**Example 3 (No Inverse):**
```
Find A⁻¹ if A = | 2  4 |
                | 1  2 |

|A| = (2×2) - (4×1) = 4 - 4 = 0

Since |A| = 0, A is SINGULAR → A⁻¹ does NOT EXIST  ✓
```

---

## 🔷 SOLVING EQUATIONS USING MATRICES (Matrix Method / Inverse Method)

### System of equations:
```
a₁x + b₁y = c₁
a₂x + b₂y = c₂
```

### Written in Matrix form as:  **AX = B**
```
| a₁  b₁ | × | x | = | c₁ |
| a₂  b₂ |   | y |   | c₂ |
```

### Solution:
```
X = A⁻¹ × B
```

---

### ✅ SOLVED EXAMPLE — Solving Equations using Matrix Method

**Example:**
```
Solve:  2x + y = 5
        x + 3y = 10

Step 1: Write in matrix form AX = B

A = | 2  1 |   X = | x |   B = |  5 |
    | 1  3 |       | y |       | 10 |

Step 2: Find |A|
|A| = (2×3) - (1×1) = 6 - 1 = 5

Step 3: Find A⁻¹
A⁻¹ = (1/5) × |  3  -1 |  =  |  3/5   -1/5 |
               | -1   2 |     | -1/5    2/5 |

Step 4: X = A⁻¹ × B
| x | = |  3/5   -1/5 | × |  5 |
| y |   | -1/5    2/5 |   | 10 |

x = (3/5)(5) + (-1/5)(10) = 3 - 2 = 1
y = (-1/5)(5) + (2/5)(10) = -1 + 4 = 3

Answer: x = 1, y = 3  ✓

Verification:
2(1) + (3) = 5 ✓
(1) + 3(3) = 10 ✓
```

---

---

# 📌 TOPIC 3: LINEAR PROGRAMMING (LP)

---

## 🔷 What is Linear Programming?

**Linear Programming (LP)** is a mathematical technique for finding the **best (optimal) solution** — maximum profit or minimum cost — from a set of limited resources, subject to certain **constraints (limitations).**

> **Real-life example:** A factory makes two products — chairs and tables. They have limited wood, labour, and machine time. LP helps find how many chairs and tables to produce to **maximise profit** without exceeding the available resources.

---

## 🔷 Key Terms in Linear Programming

### 1. 🎯 Objective Function
The **mathematical expression of what we want to maximise or minimise.**
```
Z = 5x + 3y   (Maximise profit Z)
or
Z = 2x + 4y   (Minimise cost Z)
```
Here x and y are called **decision variables.**

### 2. 🚧 Constraints
The **limitations or restrictions** on the decision variables — usually resource limits.
```
2x + y ≤ 100    (Labour hours available)
x + 3y ≤ 150    (Material available)
x ≥ 0, y ≥ 0   (Non-negativity constraint)
```

### 3. 🔓 Non-Negativity Constraint
We can't produce negative quantities, so:
```
x ≥ 0  and  y ≥ 0  (always included)
```

### 4. 📐 Feasible Region
The **region on the graph** that satisfies ALL constraints simultaneously. The optimal solution lies at one of the **corner points (vertices)** of this region.

### 5. 📍 Optimal Solution
The **best value of Z** (maximum or minimum) found at one of the corner points of the feasible region.

---

## 🔷 ASSUMPTIONS OF LINEAR PROGRAMMING

1. **Linearity:** The objective function and all constraints are linear (straight lines)
2. **Certainty:** All coefficients and constraints are known with certainty
3. **Divisibility:** Decision variables can take fractional values
4. **Non-negativity:** All variables are ≥ 0

---

## 🔷 METHODS OF SOLVING LP PROBLEMS

1. **Graphical Method** — Used for 2-variable problems (most common in exams)
2. **Simplex Method** — Used for more than 2 variables

---

## 🔷 GRAPHICAL METHOD — Step by Step

### Steps:

**STEP 1:** Define the decision variables (x and y)

**STEP 2:** Write the Objective Function (Z = ...)

**STEP 3:** Write all the Constraints

**STEP 4:** Convert each constraint inequality to an equation (use = sign) and find 2 points for each line (set x=0, find y; set y=0, find x)

**STEP 5:** Plot all constraint lines on a graph

**STEP 6:** Identify the Feasible Region (area satisfying ALL constraints)

**STEP 7:** Find all Corner Points (vertices) of the feasible region

**STEP 8:** Substitute each corner point into the Objective Function Z

**STEP 9:** The corner point giving the highest Z = Maximum / lowest Z = Minimum

---

### ✅ SOLVED EXAMPLE 1 — Maximisation Problem

**Problem:**
```
A company makes two products P and Q.
Profit from P = ₹5 per unit, Profit from Q = ₹4 per unit.

Constraints:
- Machine time: 6P + 4Q ≤ 24 hours
- Labour time:  P + 2Q ≤ 6 hours
- Non-negativity: P ≥ 0, Q ≥ 0

Maximise: Z = 5P + 4Q
```

**Solution:**

**Step 1:** Decision variables: P and Q (let's call them x and y for simplicity)
```
Maximise Z = 5x + 4y
Subject to:
  6x + 4y ≤ 24   ...(i)
   x + 2y ≤ 6    ...(ii)
  x ≥ 0, y ≥ 0
```

**Step 2:** Find points for each constraint line:

For **6x + 4y = 24:**
```
When x = 0:  4y = 24  →  y = 6  → Point A(0, 6)
When y = 0:  6x = 24  →  x = 4  → Point B(4, 0)
```

For **x + 2y = 6:**
```
When x = 0:  2y = 6   →  y = 3  → Point C(0, 3)
When y = 0:  x = 6    →  x = 6  → Point D(6, 0)
```

**Step 3:** Find intersection of the two constraint lines:
```
6x + 4y = 24  ...(i)
 x + 2y = 6   ...(ii)  → multiply by 2: 2x + 4y = 12  ...(iii)

Subtract (iii) from (i):
(6x + 4y) - (2x + 4y) = 24 - 12
4x = 12
x = 3

Substitute x = 3 in (ii):
3 + 2y = 6  →  2y = 3  →  y = 1.5

Intersection point: E(3, 1.5)
```

**Step 4:** Corner Points of Feasible Region:
```
O(0, 0)       Z = 5(0) + 4(0)   = 0
C(0, 3)       Z = 5(0) + 4(3)   = 12
E(3, 1.5)     Z = 5(3) + 4(1.5) = 15 + 6 = 21  ← MAXIMUM
B(4, 0)       Z = 5(4) + 4(0)   = 20
```

**Answer:**
```
✅ Maximum Profit Z = ₹21
   When x (Product P) = 3 units
   And  y (Product Q) = 1.5 units
```

---

### ✅ SOLVED EXAMPLE 2 — Minimisation Problem

**Problem:**
```
Minimise Z = 3x + 5y
Subject to:
  x + y  ≥ 4     ...(i)
  x + 3y ≥ 6     ...(ii)
  x ≥ 0, y ≥ 0
```

**Step 1:** Find points for constraint lines:

For **x + y = 4:**
```
x = 0 → y = 4   Point A(0, 4)
y = 0 → x = 4   Point B(4, 0)
```

For **x + 3y = 6:**
```
x = 0 → 3y = 6 → y = 2   Point C(0, 2)
y = 0 → x = 6             Point D(6, 0)
```

**Step 2:** Find intersection:
```
x + y  = 4   ...(i)
x + 3y = 6   ...(ii)

Subtract (i) from (ii):
2y = 2  →  y = 1
x = 4 - 1 = 3

Intersection point: E(3, 1)
```

**Step 3:** Corner Points of Feasible Region:
*(For ≥ constraints, feasible region is ABOVE the lines)*
```
A(0, 4)   Z = 3(0) + 5(4) = 20
E(3, 1)   Z = 3(3) + 5(1) = 9 + 5 = 14  ← MINIMUM
B(4, 0)   Z = 3(4) + 5(0) = 12
```

Wait — check if B(4,0) satisfies constraint (ii):
4 + 3(0) = 4 < 6 → Does NOT satisfy (ii) ✗

So feasible corner points are A(0,4) and E(3,1) and D(6,0):
```
D(6, 0): Z = 3(6) + 5(0) = 18
```

**Answer:**
```
✅ Minimum Cost Z = 14
   When x = 3 and y = 1
```

---

### ✅ SOLVED EXAMPLE 3 — Classic Exam Problem

**Problem:**
```
A furniture maker produces chairs (x) and tables (y).
Profit: ₹3 per chair, ₹5 per table.

Constraints:
  2x + 4y ≤ 80  (wood available: 80 sq ft)
   x + 3y ≤ 60  (labour: 60 hours)
  x ≥ 0, y ≥ 0

Maximise Profit Z = 3x + 5y
```

**Solution:**

For **2x + 4y = 80:**
```
x = 0 → y = 20   Point (0, 20)
y = 0 → x = 40   Point (40, 0)
```

For **x + 3y = 60:**
```
x = 0 → y = 20   Point (0, 20)
y = 0 → x = 60   Point (60, 0)
```

**Intersection of the two lines:**
```
2x + 4y = 80   ...(i)
 x + 3y = 60   ...(ii) → multiply by 2: 2x + 6y = 120  ...(iii)

Subtract (i) from (iii):
2y = 40  →  y = 20
x = 60 - 3(20) = 60 - 60 = 0

Intersection: (0, 20)

Try again — multiply (ii) by 2:
2x + 6y = 120
2x + 4y = 80
Subtract: 2y = 40 → y = 20, x = 0

Since both lines pass through (0,20), let's find another interior point.

Check x + 3y = 60 and 2x + 4y = 80 again:
From (ii): x = 60 - 3y
Sub in (i): 2(60-3y) + 4y = 80
            120 - 6y + 4y = 80
            120 - 2y = 80
            2y = 40
            y = 20, x = 0

Corner Points:
O(0, 0)    Z = 0
(0, 20)    Z = 3(0) + 5(20) = 100
(40, 0)    Z = 3(40) + 5(0) = 120  ← MAXIMUM
```

**Answer:**
```
✅ Maximum Profit Z = ₹120
   Produce 40 chairs and 0 tables
```

---

## 🔷 SPECIAL CASES IN LP

### 1. Unbounded Solution
The feasible region extends to infinity — maximum may not exist (but minimum might).

### 2. Infeasible Solution
No feasible region exists — constraints are contradictory.

### 3. Multiple Optimal Solutions
Two corner points give the same maximum Z — any point on the line between them is also optimal.

---

---

# 📌 TOPIC 4: FUNCTIONS AND SIMPLE DIFFERENTIATION

---

## 🔷 PART A: FUNCTIONS

### What is a Function?

A **function** is a rule that assigns **exactly one output (y) to every input (x).**

Written as: **y = f(x)** or **f: x → y**

> Think of a function like a machine: you put in x, it processes it, and gives out exactly ONE answer y.

```
INPUT (x) → [ FUNCTION f ] → OUTPUT f(x)

Example: f(x) = x²
  x = 3 → f(3) = 9
  x = -3 → f(-3) = 9
```

---

### Types of Functions

#### 1. Linear Function
```
f(x) = mx + c    (m = slope, c = y-intercept)
Example: f(x) = 3x + 2
```
Graph: **Straight line**

#### 2. Quadratic Function
```
f(x) = ax² + bx + c   (a ≠ 0)
Example: f(x) = x² - 4x + 3
```
Graph: **Parabola**

#### 3. Polynomial Function
```
f(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀
Example: f(x) = 2x³ + 3x² - x + 5
```

#### 4. Constant Function
```
f(x) = k    (k is any constant)
Example: f(x) = 7
```
Graph: Horizontal straight line

#### 5. Exponential Function
```
f(x) = aˣ    (a > 0, a ≠ 1)
Example: f(x) = 2ˣ
```

---

### Domain and Range

- **Domain:** All possible **input values** (values of x) for which the function is defined
- **Range:** All possible **output values** (values of y/f(x)) that the function can produce

---

### ✅ SOLVED EXAMPLES — Functions

**Example 1:**
```
If f(x) = 2x² + 3x - 1, find f(2), f(0), f(-1)

f(2)  = 2(2²) + 3(2) - 1 = 8 + 6 - 1 = 13
f(0)  = 2(0)  + 3(0) - 1 = -1
f(-1) = 2(1)  + 3(-1) - 1 = 2 - 3 - 1 = -2  ✓
```

**Example 2:**
```
If f(x) = x² - 5x + 6, find f(3)

f(3) = 9 - 15 + 6 = 0  ✓
(This means x = 3 is a root of the equation)
```

**Example 3:**
```
If f(x) = (x + 1)/(x - 2), find the domain.

The function is undefined when x - 2 = 0, i.e., x = 2
Domain: All real numbers EXCEPT x = 2
Domain = ℝ - {2}  ✓
```

---

## 🔷 PART B: DIFFERENTIATION

### What is Differentiation?

**Differentiation** is the process of finding the **derivative** of a function.

The **derivative** of f(x), written as **f'(x)** or **dy/dx**, measures the **rate of change** of y with respect to x — it tells us how fast y is changing as x changes.

> **Real-life meaning:**
> - If y = distance, then dy/dx = speed (rate of change of distance)
> - If y = profit, then dy/dx = marginal profit (rate at which profit changes with output)

---

### 🔷 The Concept of a Limit (Foundation of Differentiation)

The derivative is defined as:
```
f'(x) = lim  [f(x+h) - f(x)] / h
        h→0
```
This means: how does f change as we make a tiny change h in x, and then let h approach zero?

> In practice, we use **standard rules** (below) instead of this formula for most problems.

---

## 🔷 STANDARD RULES OF DIFFERENTIATION

### RULE 1: 📌 Constant Rule
```
d/dx (c) = 0
```
The derivative of any constant is ZERO.

> Example: d/dx (7) = 0

---

### RULE 2: 📌 Power Rule ⭐ (Most Used)
```
d/dx (xⁿ) = n·xⁿ⁻¹
```
Bring the power down as a multiplier, then reduce the power by 1.

> Examples:
> - d/dx (x⁵) = 5x⁴
> - d/dx (x²) = 2x
> - d/dx (x)  = 1
> - d/dx (x⁻²) = -2x⁻³

---

### RULE 3: 📌 Constant Multiple Rule
```
d/dx [c·f(x)] = c · f'(x)
```
Constants come out of the derivative.

> Example: d/dx (5x³) = 5 · 3x² = 15x²

---

### RULE 4: 📌 Sum / Difference Rule
```
d/dx [f(x) ± g(x)] = f'(x) ± g'(x)
```
Differentiate term by term.

> Example: d/dx (x³ + x² - x) = 3x² + 2x - 1

---

### RULE 5: 📌 Product Rule
```
d/dx [f(x) · g(x)] = f'(x)·g(x) + f(x)·g'(x)
```
"Derivative of first × second + first × derivative of second"

> Example: d/dx [(x²)(x³)]
> = 2x · x³ + x² · 3x²
> = 2x⁴ + 3x⁴ = 5x⁴
> *(Or just: d/dx [x⁵] = 5x⁴ — same answer!)*

---

### RULE 6: 📌 Quotient Rule
```
d/dx [f(x)/g(x)] = [f'(x)·g(x) - f(x)·g'(x)] / [g(x)]²
```
"Derivative of top × bottom MINUS top × derivative of bottom, ALL divided by bottom squared"

---

### RULE 7: 📌 Chain Rule
```
d/dx [f(g(x))] = f'(g(x)) · g'(x)
```
"Differentiate the outside, keep the inside, multiply by derivative of inside"

> Example: d/dx [(2x+3)⁵]
> = 5(2x+3)⁴ · 2 = 10(2x+3)⁴

---

### RULE 8: 📌 Exponential Functions
```
d/dx (eˣ) = eˣ
d/dx (aˣ) = aˣ · ln(a)
```

### RULE 9: 📌 Logarithmic Function
```
d/dx [ln(x)] = 1/x
d/dx [log_a(x)] = 1/(x·ln(a))
```

---

## 🔷 STANDARD DERIVATIVES — QUICK REFERENCE TABLE

| f(x) | f'(x) |
|---|---|
| c (constant) | 0 |
| x | 1 |
| x² | 2x |
| x³ | 3x² |
| xⁿ | nxⁿ⁻¹ |
| √x = x^(1/2) | 1/(2√x) |
| 1/x = x⁻¹ | -1/x² |
| eˣ | eˣ |
| ln(x) | 1/x |

---

## ✅ SOLVED EXAMPLES — Differentiation

**Example 1: Simple Power Rule**
```
Find dy/dx if y = x⁴

dy/dx = 4x³  ✓
```

---

**Example 2: Polynomial**
```
Find dy/dx if y = 3x⁵ - 4x³ + 2x - 7

dy/dx = 3(5x⁴) - 4(3x²) + 2(1) - 0
      = 15x⁴ - 12x² + 2  ✓
```

---

**Example 3: Negative and Fractional Powers**
```
Find dy/dx if y = x⁻³ + √x

Write as: y = x⁻³ + x^(1/2)

dy/dx = -3x⁻⁴ + (1/2)x^(-1/2)
      = -3/x⁴ + 1/(2√x)  ✓
```

---

**Example 4: Product Rule**
```
Find d/dx [(x² + 1)(x³ - 2)]

Let f = x² + 1   f' = 2x
Let g = x³ - 2   g' = 3x²

d/dx = f'g + fg'
     = 2x(x³ - 2) + (x² + 1)(3x²)
     = 2x⁴ - 4x + 3x⁴ + 3x²
     = 5x⁴ + 3x² - 4x  ✓
```

---

**Example 5: Quotient Rule**
```
Find d/dx [x²/(x+1)]

Let f = x²      f' = 2x
Let g = x+1     g' = 1

d/dx = (f'g - fg') / g²
     = [2x(x+1) - x²(1)] / (x+1)²
     = [2x² + 2x - x²] / (x+1)²
     = (x² + 2x) / (x+1)²
     = x(x + 2) / (x+1)²  ✓
```

---

**Example 6: Chain Rule**
```
Find dy/dx if y = (3x² + 2)⁴

Let u = 3x² + 2   du/dx = 6x
y = u⁴             dy/du = 4u³

dy/dx = dy/du × du/dx
      = 4u³ × 6x
      = 4(3x² + 2)³ × 6x
      = 24x(3x² + 2)³  ✓
```

---

**Example 7: Exponential**
```
Find dy/dx if y = e³ˣ

Using chain rule:
dy/dx = e³ˣ × 3 = 3e³ˣ  ✓
```

---

**Example 8: Logarithm**
```
Find dy/dx if y = ln(x² + 1)

Using chain rule:
dy/dx = 1/(x² + 1) × 2x = 2x/(x² + 1)  ✓
```

---

## 🔷 APPLICATIONS OF DIFFERENTIATION

### 1. 📈 Finding Maximum and Minimum (Optimization)

A function f(x) has:
- **Maximum** or **Minimum** at a point where **f'(x) = 0** (called **critical points**)
- To determine which type, use the **Second Derivative Test:**
  - If f''(x) < 0 → **Maximum**
  - If f''(x) > 0 → **Minimum**

---

### ✅ SOLVED EXAMPLE — Finding Maximum/Minimum

**Example:**
```
Find the maximum/minimum of f(x) = x³ - 3x² - 9x + 5

Step 1: Find f'(x)
f'(x) = 3x² - 6x - 9

Step 2: Set f'(x) = 0
3x² - 6x - 9 = 0
x² - 2x - 3 = 0
(x - 3)(x + 1) = 0
x = 3  or  x = -1

Step 3: Find f''(x)
f''(x) = 6x - 6

Step 4: Apply Second Derivative Test

At x = 3:  f''(3) = 18 - 6 = 12 > 0  → MINIMUM
At x = -1: f''(-1) = -6 - 6 = -12 < 0 → MAXIMUM

Step 5: Find the values
f(-1) = (-1)³ - 3(-1)² - 9(-1) + 5 = -1 - 3 + 9 + 5 = 10  → Maximum value = 10
f(3)  = (3)³ - 3(3)² - 9(3) + 5 = 27 - 27 - 27 + 5 = -22  → Minimum value = -22  ✓
```

---

### 2. 💰 Marginal Analysis in Business

| Business Concept | Mathematical Form |
|---|---|
| **Total Cost** | TC = f(x) |
| **Marginal Cost** | MC = dTC/dx |
| **Total Revenue** | TR = p × x |
| **Marginal Revenue** | MR = dTR/dx |
| **Profit** | π = TR - TC |
| **Marginal Profit** | dπ/dx = MR - MC |
| **Profit is Maximum when** | MR = MC |

---

### ✅ SOLVED EXAMPLE — Marginal Analysis

**Example:**
```
A company's cost function is TC = x³ - 6x² + 15x + 10
where x = number of units produced.

Find: (a) Marginal Cost when x = 3
      (b) The value of x where cost is minimum

Solution:
MC = dTC/dx = 3x² - 12x + 15

(a) At x = 3:
MC = 3(9) - 12(3) + 15 = 27 - 36 + 15 = 6  ✓

(b) For minimum cost:
d(MC)/dx = 6x - 12 = 0  →  x = 2
d²(TC)/dx² = 6 > 0 → MINIMUM  ✓

Minimum cost occurs at x = 2 units  ✓
```

---

---

# 🎯 BUSINESS MATHEMATICS — MASTER REVISION CARD

```
╔═══════════════════════════════════════════════════════════╗
║          BUSINESS MATHEMATICS — QUICK REVISION           ║
╠═══════════════════════════════════════════════════════════╣
║                                                           ║
║  DETERMINANTS                                             ║
║  • 2×2: |A| = ad - bc                                    ║
║  • 3×3: Expand along Row 1 with signs (+−+)              ║
║  • Cramer's Rule: x = Dx/D, y = Dy/D                    ║
║  • If |A| = 0 → Singular (no inverse)                    ║
║                                                           ║
║  MATRICES                                                 ║
║  • Types: Row | Column | Square | Identity |             ║
║           Zero | Diagonal | Symmetric                    ║
║  • Operations: Add (same order) | Scalar multiply        ║
║  • Multiply: A(m×n) × B(n×p) = C(m×p)                   ║
║  • Inverse 2×2: (1/|A|) × | d  -b |                     ║
║                            |-c   a |                     ║
║  • Matrix equations: X = A⁻¹B                           ║
║                                                           ║
║  LINEAR PROGRAMMING                                       ║
║  • Objective Function: Z = ax + by                       ║
║  • Constraints: inequalities                             ║
║  • Graphical Method: Plot lines → Find feasible          ║
║    region → Test corner points → Best Z = answer         ║
║  • Max: highest Z at corner | Min: lowest Z              ║
║                                                           ║
║  FUNCTIONS                                                ║
║  • f(x): one input → exactly one output                  ║
║  • Types: Linear | Quadratic | Polynomial                ║
║                                                           ║
║  DIFFERENTIATION — KEY RULES                             ║
║  • Constant: d/dx(c) = 0                                 ║
║  • Power: d/dx(xⁿ) = nxⁿ⁻¹           ← MOST IMPORTANT  ║
║  • Sum: differentiate term by term                       ║
║  • Product: f'g + fg'                                    ║
║  • Quotient: (f'g - fg') / g²                           ║
║  • Chain: f'(g(x)) × g'(x)                              ║
║  • eˣ → eˣ | ln(x) → 1/x                                ║
║  • Max/Min: set f'(x) = 0, use f''(x) to confirm        ║
╚═══════════════════════════════════════════════════════════╝
```

---

## 📝 Exam Strategy — Business Mathematics (30 Marks)

| Topic | Likely Marks | What to Focus On |
|---|---|---|
| **Determinants** | 6-8 marks | 2×2 and 3×3 calculation + Cramer's Rule |
| **Matrices** | 8-10 marks | Multiplication + Inverse + Solving equations |
| **Linear Programming** | 8-10 marks | Graphical method — full problem |
| **Functions & Differentiation** | 6-8 marks | Power rule + Product/Quotient/Chain + Max/Min |

---

## 🔑 Golden Rules for Exam:

```
✅ Determinants: Always show FULL working — no skipping steps
✅ Matrices: Check order compatibility BEFORE multiplying
✅ LP: ALWAYS label axes, corner points, and final answer clearly
✅ Differentiation: Simplify every answer fully
✅ SHOW ALL STEPS — partial marks are given for working even if final answer is wrong
```