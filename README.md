# BIO196 Homework6: RNA-seq Sample Metadata QC

**Author:** Olga Usalka

## Purpose
This repository demonstrates a small RNA-seq sample metadata quality-control workflow.

## Project structure

```
bio196-week6-git-OlgaUsalka/
|-- README.md
|-- .gitignore
|-- data/
|   `-- sample_metadata.csv
`-- scripts/
    `-- qc_check.R
```

- `data/` contains the sample metadata table (`sample_metadata.csv`).
- `scripts/` contains the R script (`qc_check.R`) that performs the quality-control checks on the metadata.

## How to run
From the repository root, run:

```
Rscript scripts/qc_check.R
```

## Expected result
The script checks sample identifiers and prints the number of samples in each condition.

## Data policy
Raw sequencing data, private data, credentials, and large generated files must not be committed

## Commit 4
README.md was fully submitted initially, and this line indicates changes in the file for Q7.