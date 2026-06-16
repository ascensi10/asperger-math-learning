# Statistics / Probability — Asperger Tutor Reference

## Teaching Order
1. Data = set of numbers (start with a small, concrete list).
2. Measures of center: mean, median, mode (when to use which).
3. Spread: range → variance → standard deviation.
4. Probability = ratio (favorable outcomes / total outcomes).
5. Distributions and reading graphs.

## Critical Concretization Points

**Mean (mechanism):** "share everything equally" — add them up, divide:
$$\bar{x} = \frac{2 + 4 + 9}{3} = \frac{15}{3} = 5$$

**Median vs. Mean (when to use which):** If there are extreme (outlier) values, the mean is misleading. For $\{1, 2, 2, 3, 100\}$:
$$\text{mean} = \frac{108}{5} = 21.6, \qquad \text{median} = 2$$
The median represents the typical value much better because it is not affected by outliers.

**Probability = ratio (concrete):** In a bag with $3$ red and $2$ blue balls, total $5$ balls:
$$P(\text{red}) = \frac{3}{5} = 0.6 = 60\%$$
Always "favorable outcomes / total outcomes".

**Standard Deviation (intuition first):** "How far on average are the values from the mean". Small SD = data is clustered together; large SD = data is spread out. Formula after the intuition:
$$s = \sqrt{\frac{\sum (x_i - \bar{x})^2}{n}}$$

## Common Working-Memory Errors

| Error | Why it happens | Checkpoint |
|---|---|---|
| Mean / median confusion | Two measures at once | "Is there an outlier?" → if yes, use median |
| Wrong denominator in probability | Total outcomes overlooked | Write down "what is the total?" first |
| Percent / ratio / decimal confusion | Seen as three unrelated formats | Apply the $\times 100$ conversion card |
| Skipping steps in the SD formula | Multi-layered operation | Write the $(x_i - \bar{x})$ column separately first |

## Format: Statistics Problem
**DATA:** [list out the data, break it down if small]
**WHICH MEASURE:** [mean / median / probability — reason for choosing this]
**STEP 1-3:** [add / sort / divide — each line is a single operation]
**RESULT:** [value; unit / % if required]
**✔ CHECK:** [is it within range? is it reasonable?]
