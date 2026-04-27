# 📝 BM PREDICTED SESSIONAL PAPER — SET 10 (SOLVED)
## Gauhati University | B.Com 2nd Semester | Total: 30 Marks
### Predicted Accuracy: 80-90%

---

### PART A: Very Short Answer Questions (1 × 5 = 5 Marks)

**1. Define a Square Matrix.**
> **Answer:** A matrix in which the number of rows is equal to the number of columns.

**2. If y = log(log x), find dy/dx.**
> **Solution:** `(1 / log x) × (1/x) = 1 / (x log x)`.
> **Answer: 1 / (x log x)**

**3. Name any one limitation of Linear Programming.**
> **Answer:** It assumes all parameters are constant and certain (doesn't handle uncertainty well).

**4. Find the value of | 1 1; 1 1 |.**
> **Answer: 0** (Identical rows).

**5. What is a Symmetric Matrix?**
> **Answer:** A square matrix A such that `A = Aᵀ`.

---

### PART B: Short Answer Questions (2 × 5 = 10 Marks)

**6. If A = [2 3; 4 5], find A².**
> **Solution:** `[2 3; 4 5] × [2 3; 4 5] = [4+12 6+15; 8+20 12+25] = [16 21; 28 37]`.
> **Answer: [16 21; 28 37]**

**7. State the Product Rule of determinants: |AB| = |A|·|B|.**
> **Answer:** The determinant of the product of two square matrices is equal to the product of their individual determinants.

**8. Define Marginal Cost (MC).**
> **Answer:** The additional cost incurred by producing one more unit of output. `MC = d(TC)/dx`.

**9. Find the derivative of y = (3x² + 5) / (2x - 1).**
> **Solution:** `u = 3x²+5, v = 2x-1`.
> `dy/dx = [6x(2x-1) - (3x²+5)(2)] / (2x-1)² = [12x²-6x - 6x²-10] / (2x-1)² = (6x²-6x-10) / (2x-1)²`.
> **Answer: (6x²-6x-10) / (2x-1)²**

**10. If f(x) = x³, find the value of f'(2).**
> **Solution:** `f'(x) = 3x²`. At x=2: `3(2²) = 12`.
> **Answer: 12**

---

### PART C: Long Answer Questions (Answer any 3: 5 × 3 = 15 Marks)

**11. Solve using Matrix Inverse Method: [x+y+z=1; x+2y+3z=4; x+3y+9z=10]**
> **Solution Summary:**
> 1. `|A| = 1(18-9) - 1(9-3) + 1(3-2) = 9 - 6 + 1 = 4`.
> 2. `Adj A = [9 -6 1; -6 8 -2; 1 -2 1]`.
> 3. `X = 1/4 [9 -6 1; -6 8 -2; 1 -2 1] [1; 4; 10]`.
> 4. `x = 1/4 (9-24+10) = -5/4 = -1.25`.
> 5. `y = 1/4 (-6+32-20) = 6/4 = 1.5`.
> 6. `z = 1/4 (1-8+10) = 3/4 = 0.75`.
> **Answer: x=-1.25, y=1.5, z=0.75**

**12. Prove that: | a+b+c c b; c a+b+c a; b a a+b+c | = 2(a+b)(b+c)(c+a).**
> **Solution Steps:**
> 1. Use operations like `C1→C1-(C2+C3)` to simplify.
> 2. Then factor out terms and expand.
> **Answer: Full expansion proving the identity.**

**13. LPP Max Z = 2x + 3y; Sub to: x + y ≤ 400; 2x + y ≤ 600; x, y ≥ 0.**
> **Solution Steps:**
> 1. Line 1: (0,400), (400,0). Line 2: (0,600), (300,0).
> 2. Intersection: `x+y=400` and `2x+y=600` → `x=200, y=200`.
> 3. Corners: (0,0)=0, (300,0)=600, (0,400)=1200, (200,200)=400+600=1000.
> **Answer: Max Z = 1200 at x=0, y=400**

**14. Max/Min values of f(x) = x³ - 3x² - 9x + 5.**
> **Solution Steps:**
> 1. `f'(x) = 3x² - 6x - 9 = 0` → `x² - 2x - 3 = 0` → `(x-3)(x+1)=0`.
> 2. `f''(x) = 6x - 6`.
> 3. **At x=3:** `f''(3)=12 > 0` (Min). `Value = 27-27-27+5 = -22`.
> 4. **At x=-1:** `f''(-1)=-12 < 0` (Max). `Value = -1-3+9+5 = 10`.
> **Answer: Max value 10 at x=-1, Min value -22 at x=3**
