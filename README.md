# Honest vs. Misleading Visualizations

## Objective
An applied study of how chart design choices, including axis scaling, framing, and
summary statistics, can distort or clarify the economic story a dataset tells, paired
with a structured exploratory data analysis (EDA) workflow for catching those
distortions before they reach an audience.

## Methodology
- **Summary statistics vs. structure:** Recreated Anscombe's Quartet, four datasets with
  identical means, variances, and correlation coefficients but very different
  underlying shapes, to show why summary statistics alone are not enough and plotting
  is required.
- **Quantifying distortion:** Calculated the Lie Factor (the size of the effect shown in
  the graphic divided by the size of the effect in the data) for a revenue chart with a
  truncated y-axis, which produced a Lie Factor of **[YOUR VALUE]**. Then redesigned the
  chart with a zero-based axis so the Lie Factor was close to 1.
- **Framing the same series four ways:** Using FRED's Average Hourly Earnings of
  Production and Nonsupervisory Employees (AHETPI), deflated to constant 2020 dollars,
  produced four visualizations of the same real-wage series. Varying time window, axis
  range, and nominal vs. real framing supported four different narratives.
- **Structured EDA:** Applied a four-step EDA checklist (structure, distributions,
  relationships, anomalies) to World Bank GDP data covering **[YOUR VALUE]** countries
  over **[YOUR VALUE]** years.
- **Interactive tool:** Built an interactive chart toggler that switches between honest
  and misleading design choices and recalculates the Lie Factor live, so viewers can see
  exactly how much each choice distorts the data.

## Key Findings
- Identical summary statistics can hide very different data-generating patterns.
  Anscombe's Quartet shows that visualization is part of the analysis, not decoration.
- Truncating the axis on the revenue chart inflated the apparent change by a factor of
  **[YOUR VALUE]**. The zero-based redesign kept the data the same while bringing the
  visual effect back in line with the actual effect.
- A single real-earnings series supported four competing stories, from wage stagnation
  to strong growth, depending only on framing. Because presentation choices carry
  economic claims, they should be disclosed and justified.
- The EDA checklist surfaced structural and data-quality issues in the World Bank GDP
  panel before modeling. Examples include missing observations, heavily skewed
  distributions that call for log scales, and outlier economies.
- Making the Lie Factor interactive turns an abstract rule for honest charts into a
  measurable, testable property of any graphic.# econ3916-lab03-visualization
