# Analysis (Derivative / Integral) — Asperger Tutor Reference

## Teaching Sequence
1. Rate of change (concrete: speed, temperature, cost).
2. Average change → instantaneous change (limit idea — mechanism, not formal definition).
3. Derivative rules (not memorization, with the **why**).
4. Integral = inverse operation + concept of area.
5. Fundamental Theorem.

## Critical Concrete Concepts

**Limit:** show as a sequence of numbers — *approaches* the boundary, does not *reach* the boundary:
$$\tfrac{1}{2}, \;\tfrac{1}{4}, \;\tfrac{1}{8}, \;\dots \;\longrightarrow\; 0 \qquad (\text{but no term is } 0)$$

**Derivative (as a mechanism):** for $f(x) = x^2$ around $x = 2$:
$$\frac{f(2.1) - f(2)}{0.1} = \frac{4.41 - 4}{0.1} = 4.1$$
$$\frac{f(2.01) - f(2)}{0.01} = \frac{4.0401 - 4}{0.01} = 4.01$$
$$h \to 0 \;\Rightarrow\; f'(2) = 4 \qquad (\text{meaning } f'(x) = 2x)$$

**Derivative rules — rule-card format:**

| Function | Derivative | Mnemonic |
|---|---|---|
| $x^n$ | $n\,x^{n-1}$ | Bring exponent to front, reduce exponent by one |
| $e^x$ | $e^x$ | Itself |
| $\sin x$ | $\cos x$ | Move $90^\circ$ ahead |
| $\cos x$ | $-\sin x$ | Move $90^\circ$ ahead + change sign |
| $\ln x$ | $\dfrac{1}{x}$ | — |

**Chain rule:** "derivative of the outside $\times$ derivative of the inside":
$$\big(f(g(x))\big)' = f'(g(x)) \cdot g'(x)$$
Concrete: $\big(\sin(x^2)\big)' = \cos(x^2) \cdot 2x$.

**Integral:** derivative is "doing it" → integral is "undoing it". Show the area connection numerically:
$f(x) = x$ on the interval $[0, 2]$ → triangle area $= \tfrac{1}{2} \cdot 2 \cdot 2 = 2$, and $\int_0^2 x \, dx = 2$. ✓

## Common Working-Memory Errors

| Error | Checkpoint |
|---|---|
| Skipping the chain rule | Ask for every composition: "Is there an inside function?" |
| Forgetting the constant of integration $+C$ | Indefinite integral "When to add $+C$?" rule-card |
| Sign error ($\sin / \cos$) | Rewrite the derivative table every single time |
