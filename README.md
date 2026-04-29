# Aid Intensity and the Commitment-Compliance Gap in Human Rights

This repository provides datasets and replication materials for a research project on foreign aid intensity and human rights compliance.

## Project Overview

The project examines whether higher levels of Net Official Development Assistance (ODA) per capita are associated with a divergence between:

- formal human rights commitments, measured through ICCPR ratification
- observed political repression outcomes, measured through the Political Terror Scale (PTS)

The central construct is the **Commitment-Compliance Gap**, which captures repression conditional on formal treaty commitment.

## Repository Contents

| File | Description |
| --- | --- |
| `Dataset_final_upload.csv` | Final merged panel dataset used for regression analysis. |
| `NetODA_upload.csv` | Net ODA source data. |
| `PTS-2025_upload.xlsx` | Political Terror Scale source data. |
| `OP+PTS+Gap_upload.xlsx` | Intermediate dataset combining ICCPR commitment, PTS, and constructed gap variables. |

## Key Variables

The final merged dataset includes:

| Variable | Description |
| --- | --- |
| `member` | Country name. |
| `year` | Observation year. |
| `Gap_A`, `Gap_B`, `Gap_C` | Alternative measures of the commitment-compliance gap. |
| `ODA` | Aid intensity measure. |
| `GDP`, `INV`, `IMP`, `INF` | Economic covariates. |
| `SDC`, `CUR`, `BNK`, `QOG`, `DUR`, `MIL` | Additional political and institutional covariates. |

## Data Notes

- The files are provided as public research materials for transparency and replication.
- `Dataset_final_upload.csv` is the main analysis-ready panel dataset.
- Raw and intermediate files are retained to document how the final dataset was constructed.

## Citation

If you use this repository, please cite the associated research project and acknowledge the original data sources where appropriate, including the Political Terror Scale and World Bank ODA data.
