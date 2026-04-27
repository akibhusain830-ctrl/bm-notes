# 📝 BM PREDICTED SESSIONAL PAPER — SET 1 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Define a Diagonal Matrix.**
> **Answer:** A square matrix in which all elements outside the main diagonal are zero is called a Diagonal Matrix.
> *Example:* `[2 0; 0 5]`

**2. Find the value of the determinant | 5 2; 3 4 |.**
> **Solution:** 
> Formula: `ad - bc`
> `(5 × 4) - (2 × 3) = 20 - 6 = 14`
> **Answer: 14**

**3. Fill in the blank: The derivative of a constant function is always ______.**
> **Answer: Zero (0)**

**4. In LPP, what do we call the area that satisfies all constraints?**
> **Answer: Feasible Region**

**5. If f(x) = 2x³, find f'(x).**
> **Solution:** 
> Using Power Rule `nxⁿ⁻¹`:
> `f'(x) = 2 × (3x²) = 6x²`
> **Answer: 6x²**

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If A = [1 2; 3 4] and B = [0 1; 2 3], find A + 2B.**
> **Solution:**
> 1. `2B = [0 2; 4 6]`
> 2. `A + 2B = [1+0  2+2; 3+4  4+6] = [1 4; 7 10]`
> **Answer: [1 4; 7 10]**

**7. State the Identity Row/Column Property of determinants.**
> **Answer:** If any two rows (or two columns) of a determinant are identical, the value of the determinant is **zero**.

**8. Define Marginal Cost (MC) and write its mathematical formula.**
> **Answer:** Marginal Cost is the change in total cost that comes from producing one additional unit of output.
> **Formula:** `MC = d(TC) / dx` (where TC is Total Cost and x is output).

**9. Find the derivative of y = e²ˣ + log x.**
> **Solution:**
> 1. Derivative of `e²ˣ` is `2e²ˣ` (Chain rule).
> 2. Derivative of `log x` is `1/x`.
> **Answer: dy/dx = 2e²ˣ + 1/x**

**10. Differentiate between a Square Matrix and a Scalar Matrix.**
> **Answer:**
> - **Square Matrix:** A matrix where the number of rows equals the number of columns (e.g., 2x2, 3x3).
> - **Scalar Matrix:** A diagonal matrix where all the diagonal elements are equal (e.g., `[5 0; 0 5]`).

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Solve using Cramer’s Rule: [x+y+z=6; x-y+z=2; 2x+y-z=1]**
> **Solution:**
> 1. **D** = `|1 1 1; 1 -1 1; 2 1 -1|` = `1(1-1) - 1(-1-2) + 1(1+2) = 0 + 3 + 3 = 6`
> 2. **Dx** = `|6 1 1; 2 -1 1; 1 1 -1|` = `6(1-1) - 1(-2-1) + 1(2+1) = 0 + 3 + 3 = 6`
> 3. **Dy** = `|1 6 1; 1 2 1; 2 1 -1|` = `1(-2-1) - 6(-1-2) + 1(1-4) = -3 + 18 - 3 = 12`
> 4. **Dz** = `|1 1 6; 1 -1 2; 2 1 1|` = `1(-1-2) - 1(1-4) + 6(1+2) = -3 + 3 + 18 = 18`
> **Final values:** `x = Dx/D = 6/6 = 1`, `y = Dy/D = 12/6 = 2`, `z = Dz/D = 18/6 = 3`
> **Answer: x=1, y=2, z=3**

**12. Find the Inverse (A⁻¹) of A = [1 2 3; 0 1 4; 5 6 0].**
> **Solution Steps:**
> 1. **|A|:** `1(0-24) - 2(0-20) + 3(0-5) = -24 + 40 - 15 = 1`
> 2. **Cofactors:** `C₁₁=-24, C₁₂=20, C₁₃=-5, C₂₁=18, C₂₂=-15, C₂₃=4, C₃₁=5, C₃₂=-4, C₃₃=1`
> 3. **Adj A:** Transpose the cofactors → `[-24 18 5; 20 -15 -4; -5 4 1]`
> 4. **A⁻¹ = Adj A / |A| = Adj A / 1**
> **Answer: [-24 18 5; 20 -15 -4; -5 4 1]**

**13. Solve LPP Graphically: Max Z = 3x + 5y; Sub to: 2x + y ≤ 10; x + 3y ≤ 12; x, y ≥ 0.**
> **Solution Steps:**
> 1. **Line 1 (2x+y=10):** Points (0,10) and (5,0).
> 2. **Line 2 (x+3y=12):** Points (0,4) and (12,0).
> 3. **Intersection:** Solve `2x+y=10` and `x+3y=12`. Multiply eq2 by 2: `2x+6y=24`. Subtracting gives `5y=14` → `y=2.8`, `x=3.6`. Point **(3.6, 2.8)**.
> 4. **Corner Points:** `(0,0)=0`, `(5,0)=15`, `(0,4)=20`, `(3.6, 2.8) = 3(3.6) + 5(2.8) = 10.8 + 14 = 24.8` (Max).
> **Answer: Max Z = 24.8 at x=3.6, y=2.8**

**14. TC = 1/3x³ - 5x² + 20x + 10. Find output x where Marginal Cost (MC) is minimum.**
> **Solution Steps:**
> 1. `MC = d(TC)/dx = x² - 10x + 20`
> 2. To find min MC, set `d(MC)/dx = 0`:
>    `2x - 10 = 0` → `x = 5`
> 3. Check 2nd derivative: `d²(MC)/dx² = 2` (Positive, so it's a minimum).
> **Answer: Output x = 5 units**
