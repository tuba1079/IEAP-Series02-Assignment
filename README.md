# IEAP Series 02 — RStudio Assignment

**Author:** Tuba  
**Date:** 2025-10-04  
**Course:** IEAP — Series 02 (Statistical Tests)  
**Repository:** https://github.com/tuba1079/IEAP-Series02-Assignment  


## Project Overview
This repository contains my submission for the **IEAP Series 02** assignment.  
It focuses on performing statistical analyses in R using `RStudio` — including:
1. Correlation and linear regression between **PANU**, **SANU**, and **EENU** (NonUse.csv)  
2. Comparison of pre- and post-rehabilitation performance (PrePost.csv)  
3. Analysis of snoring-related stereotypes (snore.txt)


## Files Included
| File | Description |
|------|--------------|
| `main.Rmd` | Complete RMarkdown file containing all code, plots, and answers |
| `NonUse.csv` | Dataset for PANU, SANU, EENU correlation analysis |
| `PrePost.csv` | Before/After rehabilitation dataset |
| `snore.txt` | Anthropometric data for snoring analysis |



---

## Methods Summary
- **Correlation & Regression:** Pearson correlation (`cor()`) and linear model (`lm()`).
- **Paired Tests:** Paired t-test and Wilcoxon signed-rank test.
- **Categorical Tests:** Chi-square test (`chisq.test()`).
- **Visualization:** Boxplots, scatterplots, and correlation matrix (`corrplot`).

---

## Key Findings
- PANU and EENU were moderately correlated (**r ≈ 0.47, p < 0.01**).  
- Pre- vs Post-rehabilitation performance improved significantly (**p < 0.05**).  
- Snorers were not significantly heavier (**p > 0.05**), but gender and smoking showed a small association (**p = 0.008**).

---

## Data Sources
Provided as part of the **IEAP Series 02** course material.


## References
- R Documentation: `?t.test`, `?wilcox.test`, `?chisq.test`, `?cor`, `?lm`  
- Modern Applied Statistics with S — Venables & Ripley  
- ChatGpt
- Course slides and instructions


## Time Spent
Total: **≈ 6 hours** (data preparation, code, documentation, Git setup)

---

