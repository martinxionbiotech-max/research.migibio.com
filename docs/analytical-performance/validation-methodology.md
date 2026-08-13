---
title: "Analytical Performance Validation: LOD, LOQ, CV%, and Linearity"
description: "A methodology guide to analytical validation of veterinary POCT immunoassays — limit of detection (LOD), limit of quantitation (LOQ), precision (CV%), linearity, accuracy, and interference testing."
---

# Analytical Performance Validation: LOD, LOQ, CV%, and Linearity

## 1. Why Analytical Validation Matters

Analytical validation establishes that an assay **measures what it claims, reliably, across its reportable range**. For veterinary POCT, this is the foundation of every clinical claim — before a test can detect disease, it must first be shown to detect its analyte precisely and accurately.

This document defines the standard analytical parameters Migibio reports for every assay, and the methodology behind them.

## 2. Core Parameters

| Parameter | Definition | What it proves |
|-----------|-----------|----------------|
| **LOD** | Limit of Detection — lowest analyte concentration distinguishable from blank | Analytical sensitivity |
| **LOQ** | Limit of Quantitation — lowest concentration measurable with acceptable precision | Lower reporting limit |
| **Precision (CV%)** | Coefficient of variation — repeatability of measurement | Reliability |
| **Linearity** | Range over which signal is proportional to concentration | Reportable range |
| **Accuracy** | Closeness to a reference method (bias) | Trueness |
| **Interference** | Effect of matrix components (hemolysis, lipemia) | Robustness |

## 3. Limit of Detection (LOD)

**Method:** measure a blank (zero-analyte) sample 20 times; LOD = mean blank + 3 SD.

```
LOD = mean(blank) + 3 × SD(blank)
```

| Parameter | FICT Typical |
|-----------|-------------|
| Blank replicates | 20 |
| LOD | 0.1–1.0 ng/ml (assay-dependent) |
| Confidence | 95% (3 SD) |

## 4. Limit of Quantitation (LOQ)

**Method:** LOQ is the lowest concentration measurable with CV% ≤ 20% (or the concentration at mean blank + 10 SD).

```
LOQ = mean(blank) + 10 × SD(blank)   (≈ where CV% = 20%)
```

| Parameter | FICT Typical |
|-----------|-------------|
| CV% at LOQ | ≤ 20% |
| LOQ | 0.5–5.0 ng/ml |

## 5. Precision (CV%)

Two components, both reported:

| Type | Method | Migibio Target |
|------|--------|----------------|
| **Intra-assay (repeatability)** | Same run, same sample, 20 replicates | < 8% |
| **Inter-assay (reproducibility)** | Different runs/days/operators, 20 runs | < 10% |

```
CV% = (SD / mean) × 100
```

## 6. Linearity & Reportable Range

**Method:** serially dilute a high-concentration sample; plot measured vs expected; linearity is the range where correlation r² ≥ 0.99.

| Parameter | FICT Typical |
|-----------|-------------|
| Linear range | 3–4 orders of magnitude |
| r² (linear regression) | ≥ 0.99 |

## 7. Accuracy (Bias vs Reference)

**Method:** compare against a reference method (e.g., ELISA) using a Bland-Altman plot and Passing-Bablok regression.

| Metric | FICT Typical |
|--------|-------------|
| Correlation (r) vs ELISA | > 0.95 |
| Mean bias | < 10% |
| Slope (Passing-Bablok) | 0.9–1.1 |

## 8. Interference & Matrix Effects

| Interferent | Tested Concentration | Acceptance |
|-------------|---------------------|------------|
| Hemoglobin (hemolysis) | up to 5 g/L | Bias < 10% |
| Triglycerides (lipemia) | up to 10 g/L | Bias < 10% |
| Bilirubin (icterus) | up to 0.2 g/L | Bias < 10% |
| Rheumatoid factor | clinical range | No false positive |

## 9. Summary — Migibio Standard Validation Panel

Every Migibio assay ships with a validation report covering:

1. LOD & LOQ
2. Intra- & inter-assay precision (CV%)
3. Linearity & reportable range
4. Accuracy vs reference method (correlation + bias)
5. Interference & cross-reactivity
6. Lot-to-lot consistency
7. Sample stability (serum/plasma/whole blood)

*For per-assay performance numbers, see the [Data Hub](https://data.migibio.com/assay-performance/). For assay-specific validation reports, see [Technical Reports](/technical-reports/).*
