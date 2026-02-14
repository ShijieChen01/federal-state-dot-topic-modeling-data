# TRID / State DOT Topic Modeling Datasets

This repository contains curated datasets used for topic modeling and program/funding alignment analyses based on TRID project records, UTC/TRID records, and supplemental state DOT-provided records.

## Contents

The repository includes the following files:

- **1_Original_Data_from_RH.csv**  
  Raw records exported from RH (original source dataset).

- **2_Cleaned_RH_Data_for_Topic_Modeling.csv**  
  Cleaned and filtered RH dataset used as a modeling-ready input.

- **3_Original_Data_from_TRID.csv**  
  Raw TRID-exported project records before filtering and normalization.

- **4_Supplemental_Data_from_Certain_State_DOTs.csv**  
  Supplemental project records obtained directly from selected state DOTs (e.g., via email survey / requests).  
  *Note:* Any personally identifiable contact details should be masked or removed.

- **5_Final_StateDOT_Data_for_Topic_Modeling.xlsx**  
  Consolidated, modeling-ready dataset combining TRID and supplemental state DOT records, with additional flags/metadata used in analysis.

- **6_Original_UTC_Data_from_TRID.csv**  
  Raw UTC-related records exported from TRID.

## Data processing overview (high level)

The datasets were produced through a multi-step process:
1. Export raw datasets from source systems (TRID, RH, UTC/TRID).
2. Clean and normalize metadata fields (e.g., sponsor/source agency variations).
3. Filter to the intended study time window and eligibility criteria.
4. Merge TRID records with supplemental state DOT records.
5. Produce final modeling-ready tables for topic modeling and downstream analysis.

## Recommended citation

If you use these data in academic work, please cite the associated manuscript/project:

> Chen, S., et al. (2026). *[Manuscript title]*. Under review.

(Replace with your final citation when available.)



## Contact

For questions or collaboration, open an issue in this repository.
