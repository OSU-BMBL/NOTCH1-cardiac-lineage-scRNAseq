# NOTCH1-cardiac-lineage-scRNAseq

This is the repository for the manuscript: Single-cell transcriptomics reveals impaired human cardiac cell lineage determination and cardiomyocyte proliferation due to NOTCH1 deficiency.

If you have any questions or feedback regarding this notebook, please contact Cankun Wang via <cankun.wang@osumc.edu>.

## Directory structure

Note: raw data is not added due to paper revision

- 10x_code: HPC scripts to run CellRanger workflow
- 10x_qc_report: web_summary.html output from 10x CellRanger workflow
- 10x_counts: Gene-cell expression count matrix generated from CellRanger workflow
- velocyto_code: HPC scripts to run velocyto to generate velocity matrix in loom format
- velocity_loom: velocity matrix generated from Velocyto workflow
- rmarkdown: analysis code in R from 10x read counts 
- jupyter: RNA velocity analysis in Python

## Author

- [Cankun Wang](https://github.com/Wang-Cankun)
