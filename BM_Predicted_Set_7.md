# 📝 BM PREDICTED SESSIONAL PAPER — SET 7 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Define a Row Matrix.**
> **Answer:** A matrix that has only one row is called a Row Matrix.

**2. If y = ln(x), find dy/dx.**
> **Answer: 1/x**

**3. What is a Feasible Region?**
> **Answer:** The common region determined by all the constraints including non-negative constraints of a linear programming problem is called the feasible region.

**4. Find the value of | 7 0; 0 7 |.**
> **Solution:** `(7×7) - (0×0) = 49`.
> **Answer: 49**

**5. State the Power Rule of differentiation.**
> **Answer:** `d/dx (xⁿ) = n·xⁿ⁻¹`.

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If A = [1 2; 3 4] and B = [5 6; 7 8], is AB = BA?**
> **Solution:**
> `AB = [(1×5+2×7) (1×6+2×8); (3×5+4×7) (3×6+4×8)] = [19 22; 43 50]`.
> `BA = [(5×1+6×3) (5×2+6×4); (7×1+8×3) (7×2+8×4)] = [23 34; 31 46]`.
> **No, AB ≠ BA.**

**7. Find the cofactor of a₂₁ in | 1 2 3; 4 5 6; 7 8 9 |.**
> **Solution:**
> Element `a₂₁` is 4. Minor `M₂₁ = |2 3; 8 9| = 18 - 24 = -6`.
> Cofactor `C₂₁ = (-1)²⁺¹ × (-6) = +6`.
> **Answer: 6**

**8. Define Marginal Profit mathematically.**
> **Answer:** `Marginal Profit = d(Profit) / dx` or `Marginal Revenue - Marginal Cost`.

**9. Find the derivative of y = x / (x + 1). (Quotient Rule)**
> **Solution:**
> `u = x, v = x+1`.
> `dy/dx = [1(x+1) - x(1)] / (x+1)² = 1 / (x+1)²`.
> **Answer: 1 / (x + 1)²**

**10. Write any two assumptions of Linear Programming.**
> **Answer:** 1. Continuity of variables. 2. Proportionality (constant per-unit impact).

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Solve using Matrix Inverse Method: [3x - 2y = 5; x + y = 5]**
> **Solution Steps:**
> 1. `|A| = 3 - (-2) = 5`.
> 2. `Adj A = [1 2; -1 3]`.
> 3. `X = A⁻¹B = 1/5 [1 2; -1 3] [5; 5]`.
> 4. `x = 1/5 (5 + 10) = 3`, `y = 1/5 (-5 + 15) = 2`.
> **Answer: x=3, y=2**

**12. Find determinant and Adj A for [1 0 2; 2 -1 3; 4 1 8].**
> **Solution Steps:**
> 1. `|A| = 1(-8-3) - 0 + 2(2-(-4)) = -11 + 12 = 1`.
> 2. **Cofactors:** `C₁₁=-11, C₁₂=-4, C₁₃=6, C₂₁=2, C₂₂=0, C₂₃=-1, C₃₁=2, C₃₂=1, C₃₃=-1`.
> 3. `Adj A = Transpose = [-11 2 2; -4 0 1; 6 -1 -1]`.
> **Answer: |A|=1, Adj A = [-11 2 2; -4 0 1; 6 -1 -1]**

**13. Furniture LPP: Max Z = 250x + 75y; Sub to: 2500x + 500y ≤ 50000; x + y ≤ 60.**
> **Solution Steps:**
> 1. Constraint 1 (Investment): `5x + y ≤ 100`. Points: (0,100), (20,0).
> 2. Constraint 2 (Storage): `x + y ≤ 60`. Points: (0,60), (60,0).
> 3. Intersection: `5x+y=100` and `x+y=60` → `4x = 40` → `x=10, y=50`.
> 4. Corners: (0,0)=0, (20,0)=5000, (0,60)=4500, (10,50)=2500+3750=6250.
> **Answer: Max profit ₹6250 at 10 tables and 50 chairs.**

**14. f(x) = x³ - 6x² + 9x + 15. Show max at x=1, min at x=3.**
> **Solution Steps:**
> 1. `f'(x) = 3x² - 12x + 9 = 0` → `x² - 4x + 3 = 0` → `(x-1)(x-3)=0`.
> 2. `f''(x) = 6x - 12`.
> 3. At x=1: `f''(1) = -6` (Max). At x=3: `f''(3) = 6` (Min).
> **Hence proved.**
