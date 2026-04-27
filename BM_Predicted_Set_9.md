# 📝 BM PREDICTED SESSIONAL PAPER — SET 9 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Define Singular Matrix.**
> **Answer:** A square matrix whose determinant is zero is called a singular matrix.

**2. Find d/dx (7x⁴ - 3x + 10).**
> **Solution:** `7(4x³) - 3 = 28x³ - 3`.
> **Answer: 28x³ - 3**

**3. What are Decision Variables in LPP?**
> **Answer:** The variables `x` and `y` (or more) that represent the quantities to be determined to optimize the objective function.

**4. If A = [1 2; 3 4], find Aᵀ.**
> **Answer: [1 3; 2 4]**

**5. Evaluate | 1 2; 2 4 |.**
> **Solution:** `4 - 4 = 0`.
> **Answer: 0**

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If f(x) = x² + 2x + 1, find f(x+h) - f(x).**
> **Solution:** `[(x+h)² + 2(x+h) + 1] - [x² + 2x + 1] = x²+2xh+h² + 2x+2h+1 - x²-2x-1 = 2xh + h² + 2h`.
> **Answer: 2xh + h² + 2h**

**7. State the Identical Row Property of determinants.**
> **Answer:** If any two rows (or columns) of a determinant are identical, the value of the determinant is zero.

**8. Define Average Cost (AC) and Fixed Cost (FC).**
> **Answer:**
> - **Average Cost:** Total cost divided by the number of units produced.
> - **Fixed Cost:** The portion of total cost that does not change with output level (e.g., rent).

**9. Find dy/dx if y = eˣ / x. (Quotient Rule)**
> **Solution:** `u=eˣ, v=x`.
> `dy/dx = (eˣ·x - eˣ·1) / x² = eˣ(x-1) / x²`.
> **Answer: eˣ(x-1) / x²**

**10. Construct a 3x1 column matrix of your choice.**
> **Answer: [1; 2; 3]** (Example)

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Using Cramer’s Rule, solve: [3x - y + z = 5; x + 2y - z = 2; 2x + 3y + z = 13]**
> **Solution Summary:**
> 1. `D = 13`.
> 2. `Dx = 13`.
> 3. `Dy = 26`.
> 4. `Dz = 39`.
> **Values:** `x=1, y=2, z=3`.
> **Answer: x=1, y=2, z=3**

**12. Prove that | 1 1 1; a b c; a³ b³ c³ | = (a-b)(b-c)(c-a)(a+b+c).**
> **Solution Steps:**
> 1. `C2→C2-C1`, `C3→C3-C1`.
> 2. `| 1 0 0; a (b-a) (c-a); a³ (b³-a³) (c³-a³) |`.
> 3. Factor out `(b-a)` and `(c-a)`.
> 4. `(b-a)(c-a) | 1 1; b²+ab+a² c²+ac+a² |`.
> 5. `(b-a)(c-a) [c²+ac+a² - b²-ab-a²] = (b-a)(c-a) [(c-b)(c+b) + a(c-b)]`.
> 6. Factor out `(c-b)`: `(b-a)(c-a)(c-b)(c+b+a)`.
> 7. Rearrange signs: `(a-b)(b-c)(c-a)(a+b+c)`.
> **Hence proved.**

**13. LPP Max Z = 40x + 50y; Sub to: x + 2y ≤ 40; 4x + 3y ≤ 120; x, y ≥ 0.**
> **Solution Steps:**
> 1. Line 1: (0,20), (40,0). Line 2: (0,40), (30,0).
> 2. Intersection: `x+2y=40` and `4x+3y=120` → `x=24, y=8`.
> 3. Corners: (0,0)=0, (30,0)=1200, (0,20)=1000, (24,8)=960+400=1360.
> **Answer: Max Z = 1360 at x=24, y=8**

**14. Price p = 330 - x, Cost C = x² + 10x + 12. Find x for Max Profit.**
> **Solution Steps:**
> 1. `TR = (330-x)x = 330x - x²`.
> 2. `Profit (π) = TR - C = (330x - x²) - (x² + 10x + 12) = -2x² + 320x - 12`.
> 3. `dπ/dx = -4x + 320 = 0` → `4x = 320` → `x = 80`.
> 4. `d²π/dx² = -4` (< 0, Max).
> **Answer: Output x = 80 items**
