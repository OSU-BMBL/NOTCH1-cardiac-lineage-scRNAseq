# NOTCH1-cardiac-lineage-scRNAseq

This is the repository for the manuscript: [Impaired Human Cardiac Cell Development due to NOTCH1 Deficiency](https://www.ahajournals.org/doi/10.1161/CIRCRESAHA.122.321398).

If you have any questions or feedback regarding this repository, please contact Cankun Wang via <cankun.wang@osumc.edu>.

## Directory structure

- 10x_code: HPC scripts to run CellRanger workflow
- 10x_qc_report: web_summary.html output from 10x CellRanger workflow
- 10x_counts: Gene-cell expression count matrix generated from CellRanger workflow
- velocyto_code: HPC scripts to run velocyto to generate velocity matrix into loom format
- velocity_loom: velocity matrices generated from Velocyto workflow
- rmarkdown: analyses using R 
- jupyter: RNA velocity analysis in Jypyter Notbooks (Python)

## Download data (working in progress)

- Merged count matrix and metadata for cells: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE196632 (Supplementary file section)
- Count matrices generated from CellRanger 
- RNA velocity matrices
- Raw FASTQ reads: https://www.ncbi.nlm.nih.gov/bioproject/PRJNA806200

## Author

- [Cankun Wang](https://github.com/Wang-Cankun)
