# NOTCH1-cardiac-lineage-scRNAseq

This is the repository for the manuscript: [Impaired Human Cardiac Cell Development due to NOTCH1 Deficiency](https://www.ahajournals.org/doi/10.1161/CIRCRESAHA.122.321398).

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

## Download data (working in progress)

- Processed count matrix and metadata for cells
- Count matrices generated from CellRanger
- RNA velocity matrices
- Raw FASTQ reads

## Author

- [Cankun Wang](https://github.com/Wang-Cankun)
