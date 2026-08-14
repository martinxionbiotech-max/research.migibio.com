---
title: "Fluorescence Immunochromatography (FICT): Technical White Paper"
date: 2026-08-13
description: "A technical deep-dive into fluorescence immunochromatography (FICT) — detection principle, fluorescence labeling, instrumentation, and how it achieves quantitative pg/ml-level sensitivity in veterinary POCT diagnostics."
---

# Fluorescence Immunochromatography (FICT): Technical White Paper

## 1. Executive Summary

Fluorescence immunochromatography (FICT) is a quantitative lateral-flow immunoassay technology that replaces the traditional colloidal-gold visual readout with a **fluorescence-labeled conjugate read by a dedicated fluorometer**. The result is a point-of-care test (POCT) that delivers **instrument-read, quantitative results** — comparable in sensitivity to laboratory ELISA, but in minutes at the point of care.

Migibio's FICT platform (FIA680/FIA880 analyzers) applies this principle to veterinary diagnostics, enabling veterinarians to obtain quantitative biomarker concentrations (CRP, SDMA, NT-proBNP, hormones, and infectious-disease markers) with laboratory-grade analytical performance.

| Attribute | Colloidal Gold (LFIA) | FICT (Migibio) | ELISA (Lab) |
|-----------|----------------------|----------------|-------------|
| Readout | Visual (qualitative) | Fluorescence (quantitative) | Absorbance (quantitative) |
| Sensitivity | ng/ml | **pg/ml** | pg/ml |
| Throughput | 1 test, manual | 1 test, 3–15 min | Batch, 1–4 h |
| Quantitation | No (line presence) | **Yes (concentration)** | Yes |
| Operator | Any | Minimal training | Trained tech |
| CV% | Not applicable | **< 10%** | 5–10% |

---

## 2. Detection Principle

FICT is an **immunoassay**, not a chemistry assay. Its signal chain is:

1. **Capture antibody** is immobilized on a nitrocellulose membrane at the test (T) line.
2. **Detection antibody**, conjugated to a **fluorophore** (e.g., europium chelate, fluorescein derivative), is dried on the conjugate pad.
3. **Sample (serum/plasma/whole blood)** is applied; capillary action carries the analyte forward.
4. **Sandwich complex** forms: capture antibody — analyte — fluorophore-labeled detection antibody.
5. **Excitation light** (e.g., 365 nm UV or 470 nm blue) excites the fluorophore at the T line.
6. **Emission** (e.g., 615 nm) is collected by a photodetector and converted to concentration via a pre-calibrated standard curve.

The key difference from colloidal gold: **fluorescence intensity is linearly proportional to analyte concentration over a wide dynamic range**, and is measured by an instrument rather than judged by eye — enabling true quantitation.

### 2.1 Why Fluorescence Beats Colloidal Gold for Quantitation

| Factor | Colloidal Gold | Fluorescence |
|--------|---------------|--------------|
| Signal type | Absorbance (dense color) | Emission (light) |
| Detection limit | ~1 ng/ml | **0.01–0.1 ng/ml (pg/ml)** |
| Dynamic range | 1–2 logs | **3–4 logs** |
| Matrix interference | Higher (visual haze) | Lower (spectral separation) |
| Batch CV | High (visual judgment) | Low (instrument) |

---

## 3. Instrumentation

FICT requires a **dedicated fluorometer** — the analyzer provides excitation, detection, and calibration-curve management. Migibio's platform:

| Parameter | FIA680 | FIA880 |
|-----------|--------|--------|
| Channels | Single-channel | **Six-channel** |
| Throughput | 1 test / run | Up to 6 tests / run |
| Sample types | Serum, plasma, whole blood | Serum, plasma, whole blood |
| Excitation | LED (stable) | LED (stable) |
| Detection | Photodiode / PMT | Photodiode / PMT |
| Calibration | Pre-loaded standard curve | Cloud standard-curve sync |
| Data output | Concentration + qualitative flag | Concentration + qualitative flag |

The analyzer embeds **pre-calibrated standard curves** for each assay (via QR code or cloud sync), so the operator never manually constructs a curve — reducing inter-operator variability.

---

## 4. Analytical Performance (Representative)

FICT assays typically achieve:

| Metric | Typical FICT Value |
|--------|-------------------|
| Limit of Detection (LOD) | 0.1–1.0 ng/ml (assay-dependent) |
| Limit of Quantitation (LOQ) | 0.5–5.0 ng/ml |
| Linear range | 2–3 orders of magnitude |
| Intra-assay CV% | < 8% |
| Inter-assay CV% | < 10% |
| Correlation vs ELISA (r) | > 0.95 |

---

## 5. Clinical Applications

FICT is the enabling technology behind quantitative POCT for:

- **Inflammation**: CRP (canine), SAA (feline) — mg/L scale
- **Renal**: SDMA, cystatin C — early kidney-disease detection
- **Cardiac**: NT-proBNP — heart-failure staging
- **Endocrine**: T4, TSH, cortisol, progesterone, relaxin
- **Infectious disease**: CPV, CDV, FPV, FeLV, FIV antigen/antibody

---

## 6. Limitations & Mitigations

| Limitation | Mitigation |
|-----------|------------|
| Hook effect at very high analyte | Sample dilution; assay designed with extended range |
| Matrix effects (lipemia, hemolysis) | Instrument spectral correction; sample QC prompts |
| Temperature sensitivity of reaction | Built-in temperature control in analyzer |
| Requires dedicated instrument | Bundled analyzer + assay system (economical at scale) |

---

## 7. Conclusion

FICT bridges the gap between qualitative lateral-flow strips and laboratory immunoassays: it delivers **ELISA-grade quantitative sensitivity with POCT convenience**. For veterinary clinics, this means same-visit, actionable results — a material improvement over both send-out lab testing and visual-only strips.

*For structured performance data per assay, see the [Data Hub](https://data.migibio.net/assay-performance/). For method comparison studies, see [Comparative Studies](/comparative-studies/).*
