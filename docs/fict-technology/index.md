---
title: "FICT Technology"
date: 2026-08-13
description: "The science of fluorescence immunochromatography (FICT) — detection principle, fluorescence labeling, instrumentation, signal quantification, and why it enables quantitative POCT."
---

# FICT Technology

This section explains the science behind **Fluorescence Immunochromatographic Technology (FICT)** — the detection principle that powers the Migibio FIA680/FIA880 analyzers and their quantitative test reagents.

FICT is the technology answer to a specific problem: traditional lateral-flow (colloidal-gold) strips are qualitative and operator-dependent, while laboratory immunoassays (ELISA) are quantitative but slow and lab-bound. FICT delivers **quantitative, instrument-read results in minutes at the point of care**.

## Core Concepts

| Concept | Explanation |
|---------|-------------|
| Immunochromatography | Analyte migrates along a membrane via capillary action and is captured by immobilized antibodies |
| Fluorescence labeling | The detection antibody carries a fluorophore (e.g., europium chelate) instead of gold nanoparticles |
| Instrument readout | A dedicated fluorometer excites the fluorophore and measures emitted light intensity |
| Quantitation | Emission intensity is converted to concentration via a pre-calibrated standard curve |

## Why Fluorescence Enables Quantitation

The key difference from colloidal gold is the **nature of the signal**:

| Factor | Colloidal Gold | Fluorescence (FICT) |
|--------|---------------|---------------------|
| Signal type | Absorbance (dense color) | Emission (light) |
| Readout | Visual (human eye) | Instrument (photodetector) |
| Detection limit | ~1 ng/ml | **0.01–0.1 ng/ml (pg/ml)** |
| Dynamic range | 1–2 logs | **3–4 logs** |
| Quantitation | No (line presence only) | **Yes (concentration)** |

Because fluorescence intensity is **linearly proportional to analyte concentration over a wide range** and is read by an instrument rather than judged by eye, FICT achieves true quantitation — the property that separates it from qualitative strips.

## Documented Resources

- [FICT Technical White Paper](/fict-technology/fluorescence-immunochromatography/) — the full deep-dive: detection principle, instrumentation, performance, limitations.
- [Comparative Studies](/comparative-studies/) — FICT head-to-head vs ELISA, PCR, and colloidal gold.

## Platform Instrumentation

FICT requires a dedicated fluorometer. The Migibio platform provides two:

| Parameter | FIA680 | FIA880 |
|-----------|--------|--------|
| Channels | Single | Six |
| Throughput | 1 test/run | Up to 6 tests/run |
| Calibration | Pre-loaded standard curve | Cloud standard-curve sync |

See [Analyzer Technology](https://docs.migibio.com/domain-01-analyzer-technology/) in the knowledge base for operation and maintenance.

## FAQ

**How is FICT different from a qualitative strip?** A qualitative strip shows a line that a human reads as present/absent. FICT measures the *intensity* of a fluorescent signal with an instrument and converts it to a numerical concentration — enabling quantitative results.

**Does FICT require special sample preparation?** No. Serum, plasma, or whole blood is applied directly to the cartridge; the analyzer handles excitation, detection, and curve fit.

**Why does FICT need a dedicated instrument?** The fluorophore must be excited at a specific wavelength and its emission measured precisely — a task only a calibrated fluorometer can perform. The analyzer also stores pre-calibrated standard curves, removing inter-operator variability.

*For structured performance data, see the [Data Hub](https://data.migibio.com/assay-performance/).*
