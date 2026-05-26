# Coupon Acceptance Analysis (Bar & Coffee House) v3

## Author
**Leo Lin**  
Data Reporting & Analytics Consultant

---

## Problem Statement
The goal of this analysis is to determine which drivers are most likely to accept mobile coupons for two specific coupon groups—**Bar** and **Coffee House**—and to identify the behavioral and demographic factors that distinguish acceptance from rejection.

---

## Exploratory Analysis & Visualizations
Exploratory visualizations compare accepted vs. rejected coupons for each coupon group across:

- Venue visit frequency (Bar / Coffee House)
- Age group
- Presence of children as passengers
- Occupation category

Bar charts and grouped acceptance-rate plots highlight differences in response patterns between segments, with **visit frequency emerging as the most informative variable** for both coupon types.

---

## Statistical Interpretation
- Prior venue visit frequency is strongly associated with higher acceptance rates.
- For both coupon groups, acceptance increases with visit frequency.
- Segment-level comparisons (age, children, occupation) show consistent directional effects.
- Interpretations are limited to observed associations and do not imply causality.

---

## Key Findings

### Bar Coupons
- Frequent bar-goers (>3 visits/month) have the highest acceptance rates (~75%+).
- Drivers over age 25 and not traveling with children are more likely to accept.
- Behavioral factors (e.g., visit frequency) are stronger predictors of coupon acceptance than demographics such as income or family status.

**Actionable Insight:**
- Target bar coupons toward frequent bar visitors without children to maximize acceptance.

---

### Coffee House Coupons

- Targeted segments significantly outperform the baseline, with acceptance rates ranging from **59%–76% vs. 46.6%** overall.
- Older drivers (45+) who frequently visit coffee houses are the most responsive group (**~72.8% acceptance**).
- Lower-income (≤50K) drivers within this group show higher acceptance than higher-income drivers without children (**72.8% vs. 59.3%**), suggesting price sensitivity.
- The presence of children materially increases acceptance, with high-income drivers with kids reaching the highest observed rate (**76.5%**), though this segment has a small sample size.
- Frequent restaurant visitors (low-income) form a secondary segment with above-average acceptance (**63.8%**), but lower than core coffee-focused groups.

**Actionable Insights:**
- Prioritize targeting older (45+) frequent coffee visitors, especially lower-income households.
- Consider family status (presence of children) as a key factor for improving targeting effectiveness.
- Use restaurant frequency as a secondary targeting signal where coffee-related data is limited.

---

## Next Steps & Recommendations
- Quantify feature importance—especially visit frequency, with secondary factors like age and presence of children.
- Focus on users who frequently visit coffee shops and whose behavior aligns with the coupon, while limiting offers to users who are less likely to respond.
- Incorporate contextual features (time, location) to enhance personalization.
- Include transaction-level spending data to identify which segments generate the most revenue and prioritize high-value customers.

---

## Notebook
The full analysis, visualizations, and statistical summaries are available here:
[View Jupyter Notebook](https://github.com/leosj168/analytics-toolkit/blob/main/coupon_driver_ll.ipynb)