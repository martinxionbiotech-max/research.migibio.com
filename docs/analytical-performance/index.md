---
title: "Analytical Performance"
date: 2026-08-13
description: "Analytical validation of Migibio FICT assays — limit of detection (LOD), limit of quantitation (LOQ), precision (CV%), linearity, accuracy, and interference. Method framework and representative performance data."
---

# Analytical Performance

This section documents how Migibio validates the analytical performance of its FICT veterinary assays — and what the resulting figures mean for a veterinarian interpreting a result.

Analytical performance is the foundation of everything else on this site. A reference range is only meaningful if the assay measuring it is precise and accurate. This section explains the metrics, the method, and the representative numbers.

## Why Analytical Performance Matters

Before an assay can answer a clinical question, it must answer four **analytical** questions:

| Question | Metric | What it tells you |
|----------|--------|-------------------|
| Can it detect the analyte at low levels? | **LOD** (limit of detection) | The lowest concentration reliably distinguished from zero |
| Can it *quantify* at low levels? | **LOQ** (limit of quantitation) | The lowest concentration measurable with acceptable precision |
| Is it repeatable? | **CV%** (coefficient of variation) | Run-to-run and day-to-day consistency |
| Does it read the right value? | **Accuracy / correlation** | Agreement with a reference method |

## The Validation Framework

Migibio validates each assay against a defined protocol:

1. **LOD/LOQ determination** — serial dilution of a high-concentration sample to establish the detection floor.
2. **Linearity** — dilution series across the claimed measuring range.
3. **Precision** — intra-assay (within-run) and inter-assay (between-run) CV% using control material.
4. **Accuracy** — method comparison against a reference analyzer/laboratory method, reported as correlation coefficient (r).
5. **Interference** — spiking studies for lipemia, hemolysis, icterus, and common interferents.

The full protocol is documented in [Validation Methodology](/analytical-performance/validation-methodology/).

## Representative Performance (FICT Platform)

Typical performance across the Migibio FICT assay portfolio:

| Metric | Typical Value | Notes |
|--------|---------------|-------|
| Limit of Detection (LOD) | 0.1–1.0 ng/ml | Assay-dependent |
| Limit of Quantitation (LOQ) | 0.5–5.0 ng/ml | Assay-dependent |
| Linear range | 2–3 orders of magnitude | Wide dynamic range |
| Intra-assay CV% | < 8% | Within-run repeatability |
| Inter-assay CV% | < 10% | Between-run reproducibility |
| Correlation vs reference (r) | > 0.95 | Method comparison |

> These are representative platform-level figures. Assay-specific values are published on each biomarker data card in the [Data Hub](https://data.migibio.net/biomarkers/).

## Why FICT Achieves This

The instrument-read, fluorescence-based signal chain of FICT is the reason these figures are achievable — it removes the visual-judgment variability inherent in colloidal-gold strips. See the [FICT technical white paper](/fict-technology/fluorescence-immunochromatography/) for the mechanism.

## FAQ

**What is an acceptable CV% for a quantitative POCT assay?** For quantitative immunoassays, intra-assay CV% below 10% and inter-assay CV% below 15% are generally considered acceptable; Migibio's platform targets intra-assay < 8% and inter-assay < 10%.

**Why does LOD differ between assays?** LOD depends on the antibody affinity for the specific analyte and the fluorophore labeling efficiency — both are analyte-specific, so no single LOD applies across the whole portfolio.

**How do I find the LOD for a specific assay?** See the assay's data card in the [Data Hub](https://data.migibio.net/biomarkers/), or the product's COA (Certificate of Analysis).

*For the structured performance data, see the [Data Hub assay performance section](https://data.migibio.net/assay-performance/).*
