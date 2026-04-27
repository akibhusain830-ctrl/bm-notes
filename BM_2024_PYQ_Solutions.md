# 📐 BUSINESS MATHEMATICS — 2024 PYQ SOLUTIONS (COMPLETE)
## Gauhati University | B.Com 2nd Semester | Paper: COM-HC-4026
### Syllabus Focus: Determinants, Matrices, LPP, and Differentiation

---

## 📌 TOPIC 1: DETERMINANTS

### Q1 (c): Evaluate ∫ (from 1 to 2) 1/x dx
**Solution:**
1.  ∫ (1/x) dx = log x
2.  Evaluate [log x] from 1 to 2:
    `log(2) - log(1)`
3.  Since log(1) = 0, the answer is **log 2**.
✅ **Answer: log 2 (or approx 0.693)**

### Q1 (e): Evaluate the determinant [1 0 2; 2 2 4; 3 1 6]
**Solution:**
Expanding along Row 1:
`|A| = 1(2×6 - 4×1) - 0 + 2(2×1 - 2×3)`
`|A| = 1(12 - 4) + 2(2 - 6)`
`|A| = 8 + 2(-4) = 8 - 8 = 0`
✅ **Answer: 0**

### Q1 (f): Find the cofactor of -1 in the determinant [1 -2 3; 2 0 5; 3 2 -1]
**Solution:**
-1 is at position `a₃₃`.
Minor `M₃₃ = |1 -2; 2 0| = (1×0) - (-2×2) = 4`.
Cofactor `C₃₃ = (-1)³⁺³ × M₃₃ = +1 × 4 = 4`.
✅ **Answer: 4**

### Q2 (a): Write two differences between Matrix and Determinant
**Answer:**
1.  **Nature:** A matrix is an *arrangement* of numbers (it has no single value), while a determinant is a *single numerical value* associated with a square matrix.
2.  **Order:** A matrix can be of any order (rectangular), but a determinant exists only for *square matrices*.

### Q3 (a): Show that | -a² ab ac; ab -b² bc; ac bc -c² | = 4a²b²c²
**Solution:**
1.  Take `a` common from R1, `b` from R2, and `c` from R3:
    `LHS = abc | -a b c; a -b c; a b -c |`
2.  Take `a` common from C1, `b` from C2, and `c` from C3:
    `LHS = a²b²c² | -1 1 1; 1 -1 1; 1 1 -1 |`
3.  Evaluate the 3x3 determinant:
    `| -1(1-1) - 1(-1-1) + 1(1-(-1)) |`
    `| -1(0) - 1(-2) + 1(2) | = 2 + 2 = 4`
4.  `Final result = 4a²b²c²`
✅ **Proved.**

### Q4 (a): Solve by Cramer's Rule [2x+y+z=7; 3x-y-z=-2; x+2y-3z=-4]
**Solution Summary:**
- `D = 25`
- `Dx = 25` (replace x-col with 7, -2, -4)
- `Dy = 50` (replace y-col)
- `Dz = 75` (replace z-col)
- `x = 25/25 = 1`, `y = 50/25 = 2`, `z = 75/25 = 3`
✅ **Answer: x=1, y=2, z=3**

### Q4 (b): Evaluate | 1 2; 3 4 | - | -4 -1; 2 3 |
**Solution:**
1.  `|1 2; 3 4| = (1×4) - (2×3) = -2`
2.  `|-4 -1; 2 3| = (-4×3) - (-1×2) = -12 + 2 = -10`
3.  `Result = -2 - (-10) = -2 + 10 = 8`
✅ **Answer: 8**

---

## 📌 TOPIC 2: MATRICES

### Q1 (a): Define a Null Matrix
**Answer:** A matrix where all elements are zero is a Null Matrix. `O = [0 0; 0 0]`.

### Q2 (c): If A = [-5 4; 3 2], B = [1 2; 3 4], find 2A - 3B
**Solution:**
`2A = [-10 8; 6 4]`, `3B = [3 6; 9 12]`
`2A - 3B = [-10-3 8-6; 6-9 4-12] = [-13 2; -3 -8]`
✅ **Answer: [-13 2; -3 -8]**

### Q3 (b): If A = [1 2; 2 1], show that A² - 3I = 2A
**Solution:**
1.  `A² = [1 2; 2 1] × [1 2; 2 1] = [(1+4) (2+2); (2+2) (4+1)] = [5 4; 4 5]`
2.  `3I = [3 0; 0 3]`
3.  `LHS = A² - 3I = [5-3 4-0; 4-0 5-3] = [2 4; 4 2]`
4.  `RHS = 2A = 2 × [1 2; 2 1] = [2 4; 4 2]`
`LHS = RHS`
✅ **Proved.**

### Q4 (c): Construct a 3x2 matrix such that aᵢⱼ = 2i / (i + j)
**Solution:**
- `a₁₁ = 2(1)/(1+1) = 1`
- `a₁₂ = 2(1)/(1+2) = 2/3`
- `a₂₁ = 2(2)/(2+1) = 4/3`
- `a₂₂ = 2(2)/(2+2) = 1`
- `a₃₁ = 2(3)/(3+1) = 6/4 = 1.5`
- `a₃₂ = 2(3)/(3+2) = 6/5 = 1.2`
✅ **Answer: [1 0.66; 1.33 1; 1.5 1.2]**

### Q5 (b): Find inverse of A = [1 0 2; 2 -1 3; 4 1 8]
**Solution Summary:**
- `|A| = 1`
- Cofactors: `C₁₁=-11, C₁₂=-4, C₁₃=6, C₂₁=2, C₂₂=0, C₂₃=-1, C₃₁=2, C₃₂=1, C₃₃=-1`
- `A⁻¹ = Adj A = [-11 2 2; -4 0 1; 6 -1 -1]`
✅ **Answer: [-11 2 2; -4 0 1; 6 -1 -1]**

### Q6 (b): Find x, y, z, t if 3[x y; z x] - [x 6; -1 2t] + [4 x+y; z+t 3]
**Note:** This question appears to have a typo in the paper (3x, y vs x, y). Let's solve the equation `3[x y; z w] = [x 6; -1 2w] + [4 x+y; z+w 3]`.
**Solution:**
1.  `3x = x + 4` → `2x = 4` → `x = 2`
2.  `3y = 6 + (x + y)` → `2y = 6 + 2` → `y = 4`
3.  `3w = 2w + 3` → `w = 3`
4.  `3z = -1 + (z + w)` → `2z = -1 + 3` → `z = 1`
✅ **Answer: x=2, y=4, z=1, w=3**

### Q8 (b): Matrix Multiplication for Profit Maximization
**Problem:** Methods 1, 2, 3 produce goods A, B, C. Matrix A = [4 8 2; 5 7 1; 5 3 9]. Profit matrix P = [10 4 6].
**Solution:**
To find the total profit for each method, multiply Matrix A by the Profit Matrix (Pᵀ):
- **Method 1:** (4×10) + (8×4) + (2×6) = 40 + 32 + 12 = **84**
- **Method 2:** (5×10) + (7×4) + (1×6) = 50 + 28 + 6 = **84**
- **Method 3:** (5×10) + (3×4) + (9×6) = 50 + 12 + 54 = **116**
✅ **Answer: Method 3 maximizes profit with a value of ₹116.**

---

## 📌 TOPIC 3: LINEAR PROGRAMMING (LPP)

### Q1 (i): The variables associated with LPP are called ______
✅ **Answer: Decision Variables**

### Q11 (a): Solve LPP by Graphical Method (Z = 5x + 3y)
**Solution Summary:**
Constraints: `2x+y≤1000`, `x≤400`, `y≤700`.
- Feasible region corner points: `(0,0), (400,0), (400,200), (150,700), (0,700)`
- `Z at (150,700) = 5(150) + 3(700) = 2850` (Maximum)
✅ **Answer: Max Z = 2850 at x=150, y=700**

### Q11 (b): State four uses of LPP in Business
**Answer:**
1.  **Product Mix:** To find the optimal combination of products to maximise profit.
2.  **Resource Allocation:** Best use of limited raw materials and labour.
3.  **Production Scheduling:** Minimising idle time of machines.
4.  **Distribution:** Minimising transportation costs from factory to warehouses.

---

## 📌 TOPIC 4: FUNCTIONS & DIFFERENTIATION

### Q1 (b): d/dx(log x) = ______
✅ **Answer: 1/x**

### Q1 (d): If f(x) = x² - 3x + 5, find f(0)
**Solution:** `f(0) = 0² - 3(0) + 5 = 5`
✅ **Answer: 5**

### Q1 (h): d/dx(TP) = ______ (x = output)
✅ **Answer: Marginal Product (MP)**

### Q2 (b): Evaluate lim (x→0) [√(1+x) - 1] / x
**Solution:**
Rationalize numerator: `[√(1+x) - 1][√(1+x) + 1] / x[√(1+x) + 1]`
`= (1+x - 1) / x[√(1+x) + 1] = x / x[√(1+x) + 1]`
`= 1 / [√(1+x) + 1]`. Substitute x=0: `1 / (1+1) = 1/2`.
✅ **Answer: 0.5**

### Q3 (e)(i): If f(x) = (1-x)/(1+x), prove f((1-x)/(1+x)) = x
**Solution:**
`f(f(x)) = [1 - (1-x)/(1+x)] / [1 + (1-x)/(1+x)]`
`= [(1+x) - (1-x)] / [(1+x) + (1-x)]`
`= 2x / 2 = x`
✅ **Proved.**

### Q3 (e)(ii): dy/dx if y = x · log x
✅ **Answer: 1 + log x** (using Product Rule)

### Q9 (a): Find differential coefficient of √x using First Principle
**Solution:**
`f'(x) = lim(h→0) [√(x+h) - √x] / h`
Rationalize: `[(x+h) - x] / h[√(x+h) + √x] = h / h[√(x+h) + √x]`
`= 1 / [√(x+0) + √x] = 1 / 2√x`
✅ **Answer: 1 / 2√x**

### Q10 (a): Find Average and Marginal profit for P = Q² - 12Q + 50 at Q=5
**Solution:**
1.  **Average Profit (AP)** = P/Q = `(Q² - 12Q + 50) / Q = Q - 12 + 50/Q`
    At Q=5: `5 - 12 + 10 = 3`
2.  **Marginal Profit (MP)** = dP/dQ = `2Q - 12`
    At Q=5: `2(5) - 12 = -2`
✅ **Answer: AP = 3, MP = -2**

### Q10 (b): Given MC = 3x + 4, Fixed Cost = 10. Find Total Cost.
**Solution:**
Total Cost (TC) = `∫ MC dx + FC`
`TC = ∫ (3x + 4) dx + 10 = (3/2)x² + 4x + 10`
✅ **Answer: TC = 1.5x² + 4x + 10**
