---
title: "Membrane Coating & Lot-to-Lot Reproducibility"
date: 2026-08-14
description: "The physics of T-line/C-line membrane coating in FICT strips — dispense uniformity, drying kinetics, and how process control delivers tight lot-to-lot CV% reproducibility."
---

# Membrane Coating & Lot-to-Lot Reproducibility

The T-line and C-line are where the quantitative signal is captured. Their physical uniformity — line width, reagent volume, and edge definition — is the single largest manufacturing determinant of assay precision (CV%). This page explains the coating physics and how reproducibility is achieved.

## The Coating Problem

A capture reagent is dispensed as a continuous line onto the nitrocellulose membrane. For the assay to be quantitative and reproducible, the amount of capture reagent *per unit length* must be constant across the entire membrane and identical between lots.

## Factors That Affect Coating Uniformity

| Factor | Effect on the line |
|--------|--------------------|
| Dispense rate (µL/cm) | Total reagent loading — drives signal intensity |
| Line width | Reagent density per unit area |
| Reagent viscosity | Flow consistency through the dispenser |
| Membrane surface energy | Line spreading / wicking |
| Temperature & humidity | Evaporation rate, line sharpness |

## The Drying Step

After dispensing, the membrane is dried under controlled temperature and humidity. Drying is not a passive step:

- **Too fast** → uneven reagent distribution, "coffee-ring" effect, degraded activity.
- **Too slow** → reagent diffusion, blurred lines, high background.
- **Incomplete** → residual moisture degrades stability over shelf life.

## How Lot-to-Lot Reproducibility Is Controlled

| Control | Method | Target |
|---------|--------|--------|
| Dispense calibration | Gravimetric verification of dispense rate | Fixed µL/cm |
| Line-width monitoring | Optical measurement of line width | Within tolerance |
| Signal uniformity check | Fluorescence scan along the line | Low variance (→ low CV%) |
| Environment lock | Temperature/humidity control | Stable drying kinetics |
| Reference-lot comparison | New lot vs. reference curve | Within acceptance range |

## Why This Produces Tight CV%

Precision (CV%) is the variance of signal across strips and lots. By holding dispense rate, line geometry, and drying constant, the dominant sources of variance are removed — leaving CV% below 10% as a *process property* rather than a fortunate outcome.

## The Link to Analytical Validation

The analytical performance documented in [Validation Methodology](/analytical-performance/validation-methodology/) — LOD, CV%, linearity — is achievable in routine production only because the membrane coating process is this reproducible. See also the [Lot-to-Lot Consistency Report](/technical-reports/lot-consistency-report/).

## FAQ

**How is line uniformity verified?** By optical line-width measurement and fluorescence-intensity scanning along the dispensed line, before the membrane is cut into strips.

**What is the most common cause of high CV%?** Non-uniform membrane coating — which is why it is the most tightly controlled step.

*For the equipment used in coating, see the [Knowledge Base](https://docs.migibio.net/domain-11-manufacturing-production/).*
