# OPS_16S

Code repository for the study:
Lucas-Ruiz F, Vidal-Correoso D*, Mateo S.V. et al.
“Intrahepatic donor microbiota-based metataxonomic signature detected in organ preservation solution enables prediction of short-term liver transplant outcomes.”
Gut (BMJ, 2025). DOI: 10.1136/gutjnl-2025-335986


## Overview

This repository contains the analytical scripts used to process, model, and visualize data from 16S rRNA metataxonomic profiling of organ preservation solution (OPS) samples from liver transplant donors.
The study demonstrates that the intrahepatic microbiota DNA signature present in OPS predicts post-transplant outcomes (acute rejection, survival, vascular and biliary complications).

The workflows integrate:

- Metataxonomic data preprocessing (QIIME2 / phyloseq)

- Batch correction 

- Differential abundance testing (MaAsLin2)

- Gene–microbiome association mining (PubTator3 + NCBI Entrez)

- Functional enrichment (GO/KEGG)

- Predictive modeling (Random Forest, XGBoost, SVM)

## Citation

Lucas-Ruiz F, Vidal-Correoso D, Mateo SV, et al Intrahepatic donor microbiota-based metataxonomic signature detected in organ preservation solution enables prediction of short-term liver transplant outcomesGut 2025;74:2058-2069.
