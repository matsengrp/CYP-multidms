# CYP multidms analysis

Comparing DMS datasets for CYP2C19 and CYP2C19
using [multidms](https://github.com/matsengrp/multidms).

## Key files:

* [notebooks/09-20-23-Analysis.ipynb](notebooks/09-20-23-Analysis.ipynb) provides the code and description for model fitting as described in the manuscript.
* [data/](data/) holds two csv files containing the barcode-level variant abundance scores for CYP2C19and CYP2C9. These comprise the input to the analysis notebook.
* [results/replicate_shift_lasso_sweep.csv](results/replicate_shift_lasso_sweep.csv) contains the fit parameters for all 14 models tested (2 replicate training sets, 7 lasso coefficient strengths).
