# AgriShield-AI: Assam Agricultural Flood 2026 Dataset

This repository provides the dataset used in the **AgriShield-AI framework for agricultural flood-impact assessment in Assam, India**, based on multi-temporal Earth observation data.

The dataset is intended to support research on agricultural flood-impact mapping, satellite-based change detection, feature generation, and machine-learning-based assessment of potentially affected agricultural areas.

---

## Dataset Overview

The dataset contains spatial data and pre-flood/post-flood Earth observation products used in the AgriShield-AI study.

The complete dataset is provided as a single compressed archive:

`AssamPaperDataset.zip`

The archive contains four major components:

- `Boundary/` – Administrative boundary datasets for Assam.
- `PreFlood/` – Pre-flood Sentinel-2 data and associated products.
- `PostFlood/` – Post-flood Sentinel-2 data and associated products.
- `Processed/` – Processed Sentinel-2 products and derived spectral/vegetation information.

---

## Study Area

The study focuses on agricultural areas within the state of **Assam, India**, affected by the 2026 flood event investigated in the AgriShield-AI study.

The administrative boundary data included in the dataset provide spatial reference information for the study area.

---

## Flood Event

**Event:** Assam Agricultural Flood 2026

The dataset contains Earth observation information representing conditions before and after the flood event.

### Temporal Coverage

**Pre-flood period:**

`2026-05-01 to 2026-06-30`

**Post-flood period:**

`2026-07-01 to 2026-08-04`

These periods correspond to the temporal datasets included in the repository.

---

## Data Sources

The primary Earth observation data used in the dataset are derived from **Copernicus Sentinel-2 Level-2A imagery**.

The dataset also contains spatial boundary information used for the analysis.

The Sentinel-2 data include spectral bands and derived products used for agricultural and flood-impact analysis.

---

## Dataset Structure

The complete dataset is provided as:

`AssamPaperDataset.zip`

The archive is organized as follows:

```text
AssamPaperDataset.zip
│
├── Boundary/
│   ├── Assam_State.zip
│   ├── Assam_District.zip
│   └── Assam_SubDistrict.zip
│
├── PreFlood/
│   └── PreFloodSentinel2_L2A/
│
├── PostFlood/
│   └── PostFloodSentinel2_L2A/
│
└── Processed/
    ├── Pre_S2/
    └── Post_S2/
