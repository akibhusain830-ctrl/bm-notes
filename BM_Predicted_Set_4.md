# 📝 BM PREDICTED SESSIONAL PAPER — SET 4 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. What is the transpose of a Row Matrix?**
> **Answer: A Column Matrix.**

**2. Find d/dx (eˣ + x).**
> **Solution:** `d/dx(eˣ) = eˣ` and `d/dx(x) = 1`.
> **Answer: eˣ + 1**

**3. Name any two types of matrices.**
> **Answer:** 1. Square Matrix, 2. Identity Matrix.

**4. If |A| = 5, find |2A| for a 2x2 matrix.**
> **Solution:** For a matrix of order `n`, `|kA| = kⁿ|A|`.
> Here `n=2`, so `|2A| = 2² × |A| = 4 × 5 = 20`.
> **Answer: 20**

**5. What is a Feasible Solution?**
> **Answer:** Any point in the feasible region that satisfies all the given constraints and the non-negativity conditions of an LPP is called a feasible solution.

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. Explain Cramer’s Rule for a system of 2 equations.**
> **Answer:** It solves `a₁x + b₁y = c₁` and `a₂x + b₂y = c₂`.
> Let `D = |a₁ b₁; a₂ b₂|`, `Dx = |c₁ b₁; c₂ b₂|`, `Dy = |a₁ c₁; a₂ c₂|`.
> Then `x = Dx/D` and `y = Dy/D` (provided `D ≠ 0`).

**7. Find the derivative of y = (2x + 3)⁵ using Chain Rule.**
> **Solution:**
> Let `u = 2x + 3 → du/dx = 2`.
> `y = u⁵ → dy/du = 5u⁴`.
> `dy/dx = (5u⁴) × 2 = 10(2x + 3)⁴`.
> **Answer: 10(2x + 3)⁴**

**8. Given A = [1 0; 2 1], find A².**
> **Solution:**
> `[1 0; 2 1] × [1 0; 2 1] = [(1+0) (0+0); (2+2) (0+1)] = [1 0; 4 1]`.
> **Answer: [1 0; 4 1]**

**9. State any two uses of LPP in the Transport Industry.**
> **Answer:**
> 1. Minimising transportation costs between factories and warehouses.
> 2. Optimising fuel usage and route planning.

**10. Find the domain of f(x) = 1 / (x - 5).**
> **Answer:** The function is undefined when `x - 5 = 0`, i.e., `x = 5`.
> **Domain: All Real Numbers except 5 (ℝ - {5})**.

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. If A = [1 2; 3 4], verify that A · (Adj A) = |A| · I.**
> **Solution Steps:**
> 1. `|A| = 4 - 6 = -2`. So `|A|·I = [-2 0; 0 -2]`.
> 2. `Adj A = [4 -2; -3 1]`.
> 3. `A · Adj A = [1 2; 3 4] × [4 -2; -3 1] = [(4-6) (-2+2); (12-12) (-6+4)] = [-2 0; 0 -2]`.
> **LHS = RHS. Verified.**

**12. Solve using Cramer's Rule: [3x + y = 10; 2x - y = 5].**
> **Solution Steps:**
> 1. `D = |3 1; 2 -1| = -3 - 2 = -5`.
> 2. `Dx = |10 1; 5 -1| = -10 - 5 = -15`.
> 3. `Dy = |3 10; 2 5| = 15 - 20 = -5`.
> 4. `x = -15/-5 = 3`, `y = -5/-5 = 1`.
> **Answer: x=3, y=1**

**13. Discuss the Assumptions and Limitations of Linear Programming.**
> **Answer Summary:**
> - **Assumptions:** Linearity, Determinism (all values known), Divisibility (fractions allowed).
> - **Limitations:** Doesn't handle non-linear goals (like market risk), assumes constant prices, variables must be quantifiable.

**14. TC = 100 + 5x, TR = 20x - x². Find output level x that maximises Profit.**
> **Solution Steps:**
> 1. `Profit (π) = TR - TC = (20x - x²) - (100 + 5x) = -x² + 15x - 100`.
> 2. `dπ/dx = -2x + 15 = 0` → `2x = 15` → `x = 7.5`.
> 3. `d²π/dx² = -2` (< 0, Max).
> **Answer: Output x = 7.5 units**
