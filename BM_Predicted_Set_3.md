# 📝 BM PREDICTED SESSIONAL PAPER — SET 3 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Define a Unit Matrix.**
> **Answer:** A square matrix in which all the main diagonal elements are 1 and all other elements are 0 is called a Unit Matrix (or Identity Matrix), denoted by **I**.

**2. If y = log(x² + 1), find dy/dx at x=1.**
> **Solution:** 
> Using Chain Rule: `dy/dx = [1 / (x² + 1)] × 2x = 2x / (x² + 1)`
> At x=1: `2(1) / (1² + 1) = 2/2 = 1`
> **Answer: 1**

**3. State one assumption of Linear Programming.**
> **Answer: Linearity** (The objective function and all constraints must be linear).

**4. Find the cofactor of a₁₂ in | 1 2; 3 4 |.**
> **Solution:** 
> Element `a₁₂` is 2. Its minor is 3. 
> Cofactor `C₁₂ = (-1)¹⁺² × 3 = -3`.
> **Answer: -3**

**5. What is Marginal Revenue (MR)?**
> **Answer:** Marginal Revenue is the additional income received from selling one more unit of a good or service. `MR = d(TR) / dx`.

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. Find the product AB if A = [1 2 3] and B = [4; 5; 6].**
> **Solution:** 
> Matrix A is 1x3, B is 3x1. Result is 1x1.
> `AB = [ (1×4) + (2×5) + (3×6) ] = [ 4 + 10 + 18 ] = [ 32 ]`.
> **Answer: 32**

**7. Prove that d/dx (xⁿ) = nxⁿ⁻¹ is 1 for x=1 and n=1.**
> **Solution:** 
> For `n=1`: `d/dx (x¹) = 1 · x¹⁻¹ = 1 · x⁰ = 1 · 1 = 1`.
> At `x=1`: the value remains 1.
> **Hence proved.**

**8. Briefly explain the Graphical Method steps in LPP.**
> **Answer:** 
> 1. Convert inequalities to equations.
> 2. Plot lines on a graph.
> 3. Identify the common shaded area (Feasible Region).
> 4. Find the coordinates of the corner points.
> 5. Substitute corner points into the objective function (Z).

**9. Find |A| if A = [2 -1; 3 4]. Is it singular?**
> **Solution:** 
> `|A| = (2×4) - (-1×3) = 8 + 3 = 11`.
> Since `|A| ≠ 0`, it is **non-singular**.
> **Answer: 11, Non-singular**

**10. If f(x) = x² - 5x + 6, find the roots of f(x) = 0.**
> **Solution:** 
> `x² - 5x + 6 = 0`
> `(x - 2)(x - 3) = 0`
> `x = 2` or `x = 3`.
> **Answer: x = 2, 3**

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Solve using Matrix Inverse Method: [2x+3y=8; x+2y=5]**
> **Solution Steps:**
> 1. `A = [2 3; 1 2], X = [x; y], B = [8; 5]`.
> 2. `|A| = 4 - 3 = 1`.
> 3. `Adj A = [2 -3; -1 2]`.
> 4. `X = A⁻¹B = [2 -3; -1 2] × [8; 5]`.
> 5. `x = (2×8) + (-3×5) = 16 - 15 = 1`.
> 6. `y = (-1×8) + (2×5) = -8 + 10 = 2`.
> **Answer: x=1, y=2**

**12. Find the determinant of [2 3 4; 1 2 3; 4 5 6] and its Cofactor Matrix.**
> **Solution Steps:**
> 1. `|A| = 2(12-15) - 3(6-12) + 4(5-8) = 2(-3) - 3(-6) + 4(-3) = -6 + 18 - 12 = 0`.
> 2. **Cofactors:**
>    `C₁₁=-3, C₁₂=6, C₁₃=-3`
>    `C₂₁=2, C₂₂=-4, C₂₃=2`
>    `C₃₁=1, C₃₂=-2, C₃₃=1`
> **Answer: |A|=0, Matrix = [-3 6 -3; 2 -4 2; 1 -2 1]**

**13. LPP Maximisation: Z = 40x + 30y; Sub to: 2x + y ≤ 40; x, y ≥ 0.** (Note: simplified for demo)
> **Solution Steps:**
> 1. Line: `2x + y = 40`. Points: (0,40) and (20,0).
> 2. Region is bounded by axes and this line.
> 3. Corner points: (0,0), (20,0), (0,40).
> 4. `Z(20,0) = 40(20) = 800`.
> 5. `Z(0,40) = 30(40) = 1200`.
> **Answer: Max Z = 1200 at x=0, y=40**

**14. Examine f(x) = 2x³ - 15x² + 36x + 10 for Max/Min.**
> **Solution Steps:**
> 1. `f'(x) = 6x² - 30x + 36 = 0`.
> 2. `x² - 5x + 6 = 0` → `(x-2)(x-3)=0`. Critical points: `x=2, 3`.
> 3. `f''(x) = 12x - 30`.
> 4. **At x=2:** `f''(2) = 24-30 = -6` (< 0, **Maximum**). `f(2) = 16 - 60 + 72 + 10 = 38`.
> 5. **At x=3:** `f''(3) = 36-30 = 6` (> 0, **Minimum**). `f(3) = 54 - 135 + 108 + 10 = 37`.
> **Answer: Max value 38 at x=2, Min value 37 at x=3**
