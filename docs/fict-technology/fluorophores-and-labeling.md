---
title: "Fluorophores & Labeling in FICT: The Chemistry Behind the Signal"
date: 2026-08-13
description: "The fluorophore chemistry behind FICT — europium chelates and time-resolved fluorescence, excitation/emission wavelengths, and why fluorophore choice determines sensitivity."
---

# Fluorophores & Labeling in FICT: The Chemistry Behind the Signal

The sensitivity of FICT ultimately comes down to the **fluorophore** — the molecule that emits light when excited. This page explains the fluorophore chemistry and why it determines assay performance.

## What a Fluorophore Does

A fluorophore absorbs light at one wavelength (excitation) and re-emits it at a longer wavelength (emission). In FICT:

```
Excitation light (e.g., 365 nm) → fluorophore absorbs → emits (e.g., 615 nm) → photodetector measures
```

## The Fluorophore Choice Matters

| Property | Impact on assay |
|----------|-----------------|
| Brightness (quantum yield) | Higher → better sensitivity |
| Stokes shift (excitation−emission gap) | Larger → less background interference |
| Photostability | Higher → more reproducible signal |
| Matrix resistance | Better → less interference from sample |

## Time-Resolved Fluorescence: The Key Advantage

Many FICT systems use **lanthanide chelates** (e.g., europium) with **time-resolved fluorescence**:

- Lanthanides emit over a long lifetime (microseconds vs nanoseconds).
- The detector waits out the short-lived background fluorescence, then measures the lanthanide signal.
- Result: near-zero background, dramatically improving the signal-to-noise ratio — the basis of pg/ml sensitivity.

## Why This Beats Colloidal Gold

| Factor | Colloidal gold | Lanthanide fluorescence |
|--------|---------------|------------------------|
| Signal | Color (absorbance) | Long-lived emission |
| Background | Sample haze | Time-resolved elimination |
| Detection limit | ~1 ng/ml | pg/ml |

## FAQ

**What is the Stokes shift, and why does it matter?** It is the gap between excitation and emission wavelengths. A larger gap lets the detector separate the signal from scattered excitation light, reducing background.

**Why use time-resolved fluorescence?** It eliminates short-lived background fluorescence (from sample components) by measuring only the long-lived lanthanide signal — the core reason FICT reaches pg/ml sensitivity.

*For the full detection principle, see the [FICT technical white paper](/fict-technology/fluorescence-immunochromatography/).*
