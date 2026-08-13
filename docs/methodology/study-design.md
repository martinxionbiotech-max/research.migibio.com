---
title: "Study Design in Veterinary Diagnostic Evaluation"
date: 2026-08-13
description: "How to design a veterinary diagnostic evaluation study — analytical validation, diagnostic accuracy, method comparison, and field evaluation designs explained."
---

# Study Design in Veterinary Diagnostic Evaluation

The credibility of any diagnostic claim rests on the study design behind it. This page explains the four study designs Migibio uses — and when each is appropriate.

## The Four Designs

| Design | Question it answers | Typical setup |
|--------|---------------------|---------------|
| Analytical validation | Is the assay precise and accurate? | Spiked samples, replicates |
| Diagnostic accuracy | Does it detect the disease? | Gold-standard comparison |
| Method comparison | Does it agree with a reference method? | Split samples, two methods |
| Field evaluation | Does it work in the real world? | Multi-site, clinical samples |

## Analytical Validation Design

**Setup:** Known-concentration samples (spiked or reference material) run in replicates.

| Parameter | How it is measured |
|-----------|-------------------|
| LOD/LOQ | Serial dilution to find the detection/quantitation floor |
| Precision (CV%) | 20 replicates within-run and between-run |
| Linearity | Dilution series across the claimed range |
| Interference | Spiking with hemolysate, lipids, bilirubin |

## Diagnostic Accuracy Design

**Setup:** Clinical samples tested against a **gold standard** (e.g., PCR, necropsy, reference lab).

| Metric | Formula | Meaning |
|--------|---------|---------|
| Sensitivity | TP/(TP+FN) | Ability to detect true positives |
| Specificity | TN/(TN+FP) | Ability to avoid false positives |

The gold standard must be independent of the test under evaluation — a study that uses its own assay as the gold standard proves nothing.

## Method Comparison Design

**Setup:** The same samples run on the new method and a reference method (e.g., FICT vs ELISA), then compared by Bland-Altman and Passing-Bablok.

## Field Evaluation Design

**Setup:** Real clinical samples across multiple sites, evaluating performance under real-world conditions (operator variability, sample quality, time constraints).

## FAQ

**What makes a gold standard valid?** It must be independent of the test under study and recognized as definitive for the condition (e.g., PCR for viral DNA, necropsy for pathology).

**Why run a field evaluation if analytical validation passed?** Analytical validation uses controlled samples; field evaluation confirms the assay still performs with real-world sample quality and operator variability.

*For the statistical methods, see [Statistical Methods](/methodology/statistical-methods/).*
