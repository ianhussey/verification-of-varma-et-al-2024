# Verification of Varma et al. (2024) "A systematic review and meta-analysis of experimental methods for modulating intrusive memories following lab-analogue trauma exposure in non-clinical populations"



## License

NB original materials do not contain a license, putting them in a bit of a limbo. No license attached here either.



## Original publication

[Here](https://doi.org/10.1038/s41562-024-01956-y).



## PROSPERO registration

[f original study [here](https://www.crd.york.ac.uk/PROSPERO/view/CRD42021224835).



## Data and code source

On OSF [here](https://osf.io/phu7w/).



## Instructions for computational verification

To reproduce the results, re-run (using RStudio) the .Rmd files in code/, running the files in named numerical order. Results are produced as .csv files in data/processed/.

```
code/                 # processing and analysis scripts. Supplied by authors as .R with absolute paths, rewritten as .Rmd files with relative paths to place nicely with github.
data/
  raw/                # rawest form of data provided by the original authors on the OSF project. All other data files are produced from this one by the code. 
  processed/          # data files produced from the raw data file by the code
  statistical results, correlation tables
registration/         # copy of PROSPERO registration
SupplementaryResults   # folder of results supplied by the original authors, not directly produced by code here.

README.md             # this file
```

## 

