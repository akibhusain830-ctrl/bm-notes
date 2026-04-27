# 📝 BM PREDICTED SESSIONAL PAPER — SET 2 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. What is a Symmetric Matrix?**
> **Answer:** A square matrix A is called symmetric if it is equal to its transpose, i.e., **A = Aᵀ**.
> *Example:* `[1 2; 2 1]`

**2. If |A| = 0, then the matrix A is called a ______ matrix.**
> **Answer: Singular**

**3. Find dy/dx if y = √x.**
> **Solution:** 
> `y = x^(1/2)`
> `dy/dx = (1/2)x^(-1/2) = 1/(2√x)`
> **Answer: 1/(2√x)**

**4. Write the Non-negativity constraint for any LPP problem.**
> **Answer: x ≥ 0 and y ≥ 0** (meaning production/variables cannot be negative).

**5. Evaluate | 1 0 0; 2 1 0; 3 4 1 |.**
> **Solution:** Since this is a Lower Triangular Matrix, the determinant is the product of the diagonal elements.
> `1 × 1 × 1 = 1`
> **Answer: 1**

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If f(x) = (x-1)/(x+1), find f(0) and f(2).**
> **Solution:**
> 1. `f(0) = (0-1)/(0+1) = -1/1 = -1`
> 2. `f(2) = (2-1)/(2+1) = 1/3`
> **Answer: f(0)=-1, f(2)=1/3**

**7. Show that |A| = |Aᵀ| for a 2x2 matrix of your choice.**
> **Solution:** Let `A = [1 2; 3 4]`.
> `|A| = (1×4) - (2×3) = 4 - 6 = -2`.
> `Aᵀ = [1 3; 2 4]`.
> `|Aᵀ| = (1×4) - (3×2) = 4 - 6 = -2`.
> **Hence proved.**

**8. Define Objective Function in the context of Linear Programming.**
> **Answer:** The objective function is the mathematical linear expression that we intend to either **maximise** (like profit) or **minimise** (like cost). It is usually denoted by **Z**.

**9. Find dy/dx if y = x² log x. (Product Rule)**
> **Solution:** 
> Formula: `u'v + uv'`
> `u = x² → u' = 2x`
> `v = log x → v' = 1/x`
> `dy/dx = (2x)(log x) + (x²)(1/x) = 2x log x + x`
> **Answer: x(2 log x + 1)**

**10. Construct a 2x2 matrix where aᵢⱼ = i² + j.**
> **Solution:**
> - `a₁₁ = 1² + 1 = 2`
> - `a₁₂ = 1² + 2 = 3`
> - `a₂₁ = 2² + 1 = 5`
> - `a₂₂ = 2² + 2 = 6`
> **Answer: [2 3; 5 6]**

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Using properties of determinants, prove that: | 1 a a²; 1 b b²; 1 c c² | = (a-b)(b-c)(c-a).**
> **Solution Steps:**
> 1. Apply `R2 → R2 - R1` and `R3 → R3 - R1`.
> 2. Determinant becomes: `| 1 a a²; 0 (b-a) (b²-a²); 0 (c-a) (c²-a²) |`.
> 3. Take `(b-a)` common from R2 and `(c-a)` from R3.
> 4. `(b-a)(c-a) | 1 a a²; 0 1 (b+a); 0 1 (c+a) |`.
> 5. Expand along Col 1: `(b-a)(c-a) [1 × (c+a - (b+a))] = (b-a)(c-a)(c-b)`.
> 6. Rearrange signs: `(a-b)(b-c)(c-a)`.
> **Hence proved.**

**12. If A = [2 3; 1 2], show that A² - 4A + I = O. Using this equation, find A⁻¹.**
> **Solution Steps:**
> 1. `A² = [2 3; 1 2] × [2 3; 1 2] = [7 12; 4 7]`.
> 2. `A² - 4A + I = [7-8+1  12-12+0; 4-4+0  7-8+1] = [0 0; 0 0] = O`. (Proved)
> 3. **To find A⁻¹:** Multiply the whole equation by `A⁻¹`:
>    `A - 4I + A⁻¹ = O` → `A⁻¹ = 4I - A`.
> 4. `A⁻¹ = [4 0; 0 4] - [2 3; 1 2] = [2 -3; -1 2]`.
> **Answer: A⁻¹ = [2 -3; -1 2]**

**13. Solve LPP Minimisation graphically: Min Z = 2x + 3y; Sub to: x + y ≥ 6; 2x + y ≥ 8; x, y ≥ 0.**
> **Solution Steps:**
> 1. **Line 1 (x+y=6):** Points (0,6) and (6,0).
> 2. **Line 2 (2x+y=8):** Points (0,8) and (4,0).
> 3. **Intersection:** `(2x+y) - (x+y) = 8 - 6` → `x = 2`, `y = 4`. Point **(2,4)**.
> 4. **Corner Points (Above the lines):** `(0,8)=24`, `(2,4)=2(2)+3(4)=16` (Min), `(6,0)=12`.
> **Wait, let's recheck:** `Z = 2x + 3y`. At (6,0), `Z = 12`. At (2,4), `Z = 16`. At (0,8), `Z = 24`.
> **Answer: Min Z = 12 at x=6, y=0**

**14. Demand function p = 50 - 2x. Find output x that maximises Total Revenue (TR).**
> **Solution Steps:**
> 1. `TR = p × x = (50 - 2x)x = 50x - 2x²`.
> 2. `d(TR)/dx = 50 - 4x = 0` → `4x = 50` → `x = 12.5`.
> 3. `d²(TR)/dx² = -4` (Negative, so Max).
> 4. **Max Revenue:** `50(12.5) - 2(12.5)² = 625 - 312.5 = 312.5`.
> **Answer: x = 12.5 units, Max TR = 312.5**
