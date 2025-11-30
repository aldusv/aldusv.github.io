+++
title = "Math Test"
date = "2025-11-30"
description = "Yeah"
tags = [
    "development",
]
math = true
+++

# 1. Inline math

Inline math with `$`:

Einstein wrote $E = mc^2$ and $a^2 + b^2 = c^2$.

Inline math with `\(` `\)`:

Einstein wrote \( E = mc^2 \) and \( \alpha + \beta + \gamma = \pi \).

Multiple inline pieces: $x_1, x_2, \dots, x_n$ and \( \sum_{i=1}^n x_i \).

---

# 2. Simple display math (block)

$$
\int_0^1 x^2 \, dx = \frac{1}{3}
$$

$$
e^{i\pi} + 1 = 0
$$

---

# 3. Fractions, superscripts, roots

$$
\sigma_r(E) =
\frac{2J+1}{(2s_1+1)(2s_2+1)}
\cdot \frac{\pi}{k^2(E)}
\cdot \frac{\Gamma_i \Gamma_o}{
(E - E_r)^2 + \tfrac{1}{4}(\Gamma_i + \Gamma_o)^2
}
$$

$$
\sqrt{a^2 + b^2}
\qquad
\sqrt[3]{x^3 + 1}
$$

---

# 4. Sums, products, limits

$$
\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}
$$

$$
\prod_{k=1}^{n} (1 + x_k)
$$

$$
\lim_{x \to 0} \frac{\sin x}{x} = 1
$$

---

# 5. Matrices and vectors

$$
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{pmatrix}
$$

$$
\begin{bmatrix}
v_1 \\ v_2 \\ v_3
\end{bmatrix}
$$

---

# 6. Aligned equations

$$
\begin{aligned}
f(x) &= x^2 + 2x + 1 \\
     &= (x + 1)^2
\end{aligned}
$$

---

# 7. Cases

$$
\begin{cases}
x^2, & x \ge 0 \\
-x,  & x < 0
\end{cases}
$$

---

# 8. Text in math mode and blackboard bold

$$
\text{Var}(X) = \mathbb{E}\!\left[(X - \mathbb{E}[X])^2\right]
$$

Inline examples: $\text{Pr}(A \mid B)$, \( \mathbb{R}^n \), $ \mathbb{Z} $.

---

# 9. Math inside lists

- $x^2 + y^2$
- \( x^2 - y^2 \)
- $ (x + y)^2 $

---

# 10. Code vs math sanity check

This should NOT be rendered as math:

```bash
echo "$HOME"
