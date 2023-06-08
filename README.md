## Usage

This repository contains code used in multiple manuscripts. If you use or are inspired by this code, please cite appropriate DOIs (updates coming) or contact [brandonlind](https://github.com/brandonlind) for citation.

manuscripts
```
Lind, B. M., R. Candido-Ribeiro, P. Singh, M. Lu, D. O. Vidakovic, T. R. Booker, M. Whitlock, N. Isabel, S. Yeaman,
and S. N. Aitken. 2023. How useful is genomic data for predicting  maladaptation to future climate? bioRxiv DOI: https://doi.org/10.1101/2023.02.10.528022
```

or code
```
Lind BM. 2023. GitHub.com/brandonlind/douglas_fir_natural_populations: Revision Release (Version 1.1). DOI TBD

Lind BM. 2023. GitHub.com/brandonlind/offset_validation: Preprint release (Version 1.0.0). Zendodo (2023):  DOI: https://doi.org/10.5281/zenodo.7641225
```
 

---

## Outline

[02_baypass](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/tree/main/02_baypass/)
- [01_01_DF_pooled_GEA_coastal_kickoff.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/01_01_DF_pooled_GEA_coastal_kickoff.ipynb) - create covariance matrix for structure correction and submit GEA jobs to slurm
- [01_02_DF_pooled_GEA_interior_kickoff.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/01_02_DF_pooled_GEA_interior_kickoff.ipynb) - create covariance matrix for structure correction and submit GEA jobs to slurm
- [02_01_DF_pooled_GEA_coastal_gather.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/02_01_DF_pooled_GEA_coastal_gather.ipynb) - retrieve GEA jobs from slurm and combine results from replicates into one dataframe
- [02_02_DF_pooled_GEA_interior_gather.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/02_02_DF_pooled_GEA_interior_gather.ipynb) - retrieve GEA jobs from slurm and combine results from replicates into one dataframe

---

pythonimports module seen in notebooks is here: https://github.com/brandonlind/pythonimports
