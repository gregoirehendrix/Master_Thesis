# Test-TFE Sharing Codes

This repository contains a set of Jupyter notebooks developed to evaluate, optimize, and compare CSP (Concentrated Solar Power) tower layouts and grouping strategies around a power block. The goal is to minimize piping lengths while exploring different grouping constraints.

---

## Repository Content

### 1) towers_layout_groups.ipynb

This notebook computes optimized layouts and grouping of CSP units **without grouping constraints**.

It performs two main tasks:

- **Optimal spatial layout** of CSP units around the power block to minimize the total pipe length.
- **Automatic grouping** of multiple CSP units (clusters) to reduce the installed piping.

> Note: While this version is intended to find globally optimal grouping configurations, it does **not always** provide the best grouping due to the lack of structural constraints.  
> For this reason, a constrained version is provided for comparison.

---

### 2) towers_layout_groups_horizontal.ipynb

This notebook performs the same optimization tasks but includes an additional constraint:

- **Groups of CSP units must be horizontal.**

This structural constraint can sometimes lead to **better final solutions**, even though it is more restrictive.  
The comparison between both notebooks helps evaluate when constrained grouping is beneficial.

It computes:

- **Optimal CSP layout** around the power block (minimizing pipe length).
- **Grouping of CSP units with a horizontal-only constraint**.

---

## Purpose of This Repository

This repository serves as a shared workspace to:

- Compare different optimization strategies for CSP tower layouts.
- Share and review code related to spatial layout, clustering, and piping minimization.
- Support technical work for TFE/Thesis projects involving CSP field optimization.

---

## License

see LICENSE
   
