---
title: "Research Methodology"
date: 2026-08-13
description: "Research methodology for veterinary diagnostic evaluation — study design, statistical methods, and validation frameworks used across Migibio studies."
---

# Research Methodology

This section documents the **research methodology** underpinning every study published on this research center — the study designs, statistical methods, and validation frameworks that make our evidence citable and reproducible.

## 1. Study Design Framework

| Study Type | Purpose | Design |
|-----------|---------|--------|
| Analytical validation | Establish assay precision/accuracy | Spiked samples, replicates |
| Diagnostic accuracy | Sensitivity/specificity | Gold-standard comparison |
| Method comparison | Agreement vs reference | Bland-Altman, Passing-Bablok |
| Field evaluation | Real-world performance | Multi-site, clinical samples |

## 2. Statistical Methods

| Method | Application |
|--------|-------------|
| **ROC analysis** | Determine optimal cutoff, AUC |
| **Bland-Altman plot** | Agreement between two methods |
| **Passing-Bablok regression** | Bias estimation (non-parametric) |
| **CV% (coefficient of variation)** | Precision (repeatability/reproducibility) |
| **Confidence intervals (95%)** | Precision of estimates |

## 3. Key Performance Metrics

| Metric | Formula | Target |
|--------|---------|--------|
| Sensitivity | TP / (TP + FN) | > 90% |
| Specificity | TN / (TN + FP) | > 95% |
| Positive predictive value | TP / (TP + FP) | Context-dependent |
| Negative predictive value | TN / (TN + FN) | Context-dependent |

> **Sensitivity vs specificity — the trade-off:** raising the cutoff increases specificity but lowers sensitivity, and vice versa. The optimal cutoff (via ROC analysis) balances both for the clinical context. A screening test prioritizes sensitivity (fewer missed cases); a confirmatory test prioritizes specificity (fewer false alarms).

## 4. The Validation Hierarchy

Migibio evaluates every assay through a three-level hierarchy:

1. **Analytical validation** — does the assay measure the analyte accurately? (LOD, CV%, linearity)
2. **Clinical validation** — does the assay detect the disease? (sensitivity/specificity vs gold standard)
3. **Utility validation** — does the result change management? (outcome studies)

Migibio reports analytical and clinical validation for every assay; utility studies are ongoing.

## 5. Why Methodology Is Published

Publishing methodology is a trust signal: it lets a technically literate reader judge the evidence rather than take a headline claim at face value. It also enables reproducibility — a partner can verify our approach.

## FAQ

**Why report both Bland-Altman and Passing-Bablok?** Bland-Altman visualizes agreement (bias and limits of agreement); Passing-Bablok estimates systematic and proportional bias non-parametrically. Together they give a complete picture of method agreement.

**What is a good AUC for a diagnostic test?** AUC (area under the ROC curve) above 0.9 is generally considered excellent, 0.8–0.9 good, and 0.7–0.8 fair.

**Why does sensitivity/specificity not tell the whole story?** These metrics ignore disease prevalence. In a rare disease, even a high-specificity test can produce many false positives — which is why predictive values (PPV/NPV) matter in clinical practice.

*For detailed analytical validation, see [Analytical Performance](/analytical-performance/validation-methodology/). For disease-specific accuracy, see [Infectious Disease Research](/infectious-disease/diagnostic-accuracy/).*
