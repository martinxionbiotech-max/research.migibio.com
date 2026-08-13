---
title: "Precision vs Accuracy: What the Difference Means for Results"
date: 2026-08-13
description: "Precision vs accuracy in diagnostic assays — why both are validated separately, how CV% measures precision, and what correlation (r) measures accuracy."
---

# Precision vs Accuracy: What the Difference Means for Results

"Precise" and "accurate" are often used interchangeably — but in assay validation they mean different things, and an assay can be one without the other. This page explains the distinction.

## The Bullseye Analogy

| Concept | Analogy | Assay metric |
|---------|---------|--------------|
| **Precision** | Arrows grouped tightly (regardless of bullseye) | CV% (coefficient of variation) |
| **Accuracy** | Arrows near the bullseye | Correlation vs reference (r), bias |

- **Precise but inaccurate** = consistently wrong (tight group, wrong target).
- **Accurate but imprecise** = right on average, but scattered.

## Precision (CV%)

Precision measures **repeatability** — how much repeated measurements of the same sample vary.

| CV% | Interpretation |
|-----|----------------|
| < 8% | Excellent |
| 8–15% | Acceptable for quantitative POCT |
| > 15% | Poor — results fluctuate meaningfully |

For a patient monitored over days, low CV% is essential: otherwise you cannot separate a *real* patient change from *measurement noise*.

## Accuracy (Correlation & Bias)

Accuracy measures **correctness** — how close the result is to the true value.

| Metric | What it measures |
|--------|------------------|
| Correlation (r) | Agreement with a reference method (r > 0.95 target) |
| Bias | Systematic difference from the true value (< 10% target) |

## Why Both Are Validated

An assay must be **both** precise and accurate. Precision alone means consistent-but-wrong; accuracy alone means right-on-average-but-unreliable. Migibio validates both for every assay.

## FAQ

**Can an assay be precise but inaccurate?** Yes — a consistent systematic error (e.g., a miscalibrated curve) produces tight but wrong results. This is why accuracy validation against a reference method is essential.

**Which matters more for patient monitoring?** Precision — because monitoring compares values over time, and low precision would obscure real changes.

*For the full validation framework, see [Validation Methodology](/analytical-performance/validation-methodology/).*
