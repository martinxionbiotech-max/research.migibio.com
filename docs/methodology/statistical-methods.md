---
title: "Statistical Methods for Diagnostic Evaluation"
date: 2026-08-13
description: "Statistical methods used in veterinary diagnostic evaluation — ROC analysis, Bland-Altman plots, Passing-Bablok regression, and confidence intervals, explained for non-statisticians."
---

# Statistical Methods for Diagnostic Evaluation

This page explains the statistical methods used to evaluate diagnostic tests — in plain language, with the interpretation each method supports.

## ROC Analysis

**What it does:** Plots sensitivity against (1 − specificity) across all possible cutoffs; the **AUC** (area under the curve) summarizes overall accuracy.

| AUC | Interpretation |
|-----|----------------|
| > 0.9 | Excellent |
| 0.8–0.9 | Good |
| 0.7–0.8 | Fair |
| < 0.7 | Poor |

ROC analysis also identifies the **optimal cutoff** — the threshold that best balances sensitivity and specificity for the clinical context.

## Bland-Altman Plot

**What it does:** Plots the *difference* between two methods against their *mean*, visualizing **bias** (systematic difference) and **limits of agreement**.

- A mean difference near zero → no systematic bias.
- Narrow limits of agreement → the methods agree closely.

## Passing-Bablok Regression

**What it does:** A non-parametric regression that estimates **systematic bias** (intercept ≠ 0) and **proportional bias** (slope ≠ 1) between two methods.

| Result | Meaning |
|--------|---------|
| Intercept ≠ 0 | Constant (systematic) bias |
| Slope ≠ 1 | Proportional bias (bias grows with concentration) |

## Confidence Intervals (95%)

**What they do:** Express the precision of an estimate. A sensitivity of "92% (95% CI 85–96%)" means the true sensitivity likely falls in that range — a wide interval signals a small or noisy study.

## FAQ

**Why use both Bland-Altman and Passing-Bablok?** They answer different questions — Bland-Altman visualizes agreement, Passing-Bablok quantifies systematic and proportional bias. Together they give a complete picture.

**What is a good AUC for a veterinary diagnostic test?** Above 0.9 is excellent; 0.8–0.9 is good. For screening tests, prioritize sensitivity; for confirmatory tests, specificity.

*For study designs, see [Study Design](/methodology/study-design/).*
