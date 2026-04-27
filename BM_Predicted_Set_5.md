# 📝 BM PREDICTED SESSIONAL PAPER — SET 5 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Is the matrix [1 2; 2 4] singular?**
> **Solution:** `|A| = (1×4) - (2×2) = 0`.
> Since the determinant is 0, **Yes, it is singular.**

**2. Find d/dx (1/x).**
> **Solution:** `d/dx(x⁻¹) = -1 · x⁻² = -1/x²`.
> **Answer: -1/x²**

**3. Define Linear Programming.**
> **Answer:** It is a mathematical technique used to find the best (optimal) way to use limited resources to achieve a goal like maximizing profit or minimizing cost.

**4. If f(x) = 7, find f'(100).**
> **Answer: 0** (Derivative of a constant is always zero).

**5. What is a Column Matrix?**
> **Answer:** A matrix that has only one column is called a Column Matrix.

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If A = [1 -1; 2 3], find AᵀA.**
> **Solution:**
> `Aᵀ = [1 2; -1 3]`.
> `AᵀA = [1 2; -1 3] × [1 -1; 2 3] = [(1+4) (-1+6); (-1+6) (1+9)] = [5 5; 5 10]`.
> **Answer: [5 5; 5 10]**

**7. Find the limit of (x² - 4)/(x - 2) as x → 2.**
> **Solution:**
> `(x - 2)(x + 2) / (x - 2) = x + 2`.
> As `x → 2`, `2 + 2 = 4`.
> **Answer: 4**

**8. Briefly explain the Cofactor of an element in a determinant.**
> **Answer:** The cofactor of an element `aᵢⱼ` is its minor `Mᵢⱼ` multiplied by `(-1)ᶦ⁺ʲ`. It gives the minor a specific sign based on its position.

**9. State the Product Rule and Quotient Rule of differentiation.**
> **Answer:**
> - **Product Rule:** `d/dx(uv) = u'v + uv'`
> - **Quotient Rule:** `d/dx(u/v) = (u'v - uv') / v²`

**10. In an LPP, if Z = 4x + 2y, and the corner points are (0,5), (3,2), (4,0), find max Z.**
> **Solution:**
> - At (0,5): `Z = 2(5) = 10`
> - At (3,2): `Z = 4(3) + 2(2) = 16` (Max)
> - At (4,0): `Z = 4(4) = 16` (Max)
> **Answer: Max Z = 16 (occurs at both (3,2) and (4,0))**

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Find the Inverse of A = [2 1 3; 3 1 2; 1 2 3].**
> **Solution Summary:**
> 1. `|A| = 2(3-4) - 1(9-2) + 3(6-1) = -2 - 7 + 15 = 6`.
> 2. **Adj A:** `[-1 3 -1; -7 3 5; 5 -3 -1]`.
> 3. `A⁻¹ = Adj A / 6`.
> **Answer: 1/6 × [-1 3 -1; -7 3 5; 5 -3 -1]**

**12. Show that the maximum value of x + 1/x is less than its minimum value.**
> **Solution Steps:**
> 1. `f'(x) = 1 - 1/x² = 0 → x = ±1`.
> 2. `f''(x) = 2/x³`.
> 3. **At x=1:** `f''(1)=2 > 0` (Min). `Value = 1+1=2`.
> 4. **At x=-1:** `f''(-1)=-2 < 0` (Max). `Value = -1-1=-2`.
> **Since -2 < 2, the Maximum is less than the Minimum. Verified.**

**13. Solve LPP: Max Z = 10x + 6y; Sub to: 3x + y ≤ 12; 2x + 5y ≤ 20; x, y ≥ 0.**
> **Solution Steps:**
> 1. Line 1: (0,12), (4,0). Line 2: (0,4), (10,0).
> 2. Intersection: `3x+y=12`, `2x+5y=20`. Solve: `x=40/13 ≈ 3.07, y=30/13 ≈ 2.3`.
> 3. Corner points: (0,0)=0, (4,0)=40, (0,4)=24, (3.07, 2.3) = `10(3.07) + 6(2.3) = 30.7 + 13.8 = 44.5`.
> **Answer: Max Z = 44.5 at x=3.07, y=2.3**

**14. MC = 10 + 2x, FC = 500. Find TC and AC.**
> **Solution Steps:**
> 1. `TC = ∫ MC dx + FC = ∫ (10 + 2x) dx + 500 = 10x + x² + 500`.
> 2. `AC = TC / x = (10x + x² + 500) / x = 10 + x + 500/x`.
> **Answer: TC = x² + 10x + 500, AC = x + 10 + 500/x**
