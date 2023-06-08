[![DOI](https://zenodo.org/badge/651143319.svg)](https://zenodo.org/badge/latestdoi/651143319)

## Usage

This repository contains code used in multiple manuscripts. If you use or are inspired by this code, please cite appropriate DOIs (updates coming) or contact [brandonlind](https://github.com/brandonlind) for citation.

manuscripts
```
Lind, B. M., R. Candido-Ribeiro, P. Singh, M. Lu, D. O. Vidakovic, T. R. Booker, M. Whitlock, N. Isabel, S. Yeaman,
and S. N. Aitken. 2023. How useful is genomic data for predicting  maladaptation to future climate? bioRxiv DOI: https://doi.org/10.1101/2023.02.10.528022
```

or code
```
Lind BM. 2023. GitHub.com/brandonlind/douglas_fir_natural_populations: Offset Revision 1 (v1.0.0). Zenodo. https://doi.org/10.5281/zenodo.8018894

Lind BM. 2023. GitHub.com/brandonlind/offset_validation: Preprint release (Version 1.0.0). Zendodo (2023):  DOI: https://doi.org/10.5281/zenodo.7641225
```
 

---

## Outline

Notebooks are hyperlinked to be viewed on nbviewer.org, but are best viewed in a jupyter session so that cells can be collapsed or scrolled (html and nbviewer versions, links below do not allow scrolling).

[02_baypass](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/tree/main/02_baypass/)
- [01_01_DF_pooled_GEA_coastal_kickoff.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/01_01_DF_pooled_GEA_coastal_kickoff.ipynb) - create covariance matrix for coastal variety structure correction and submit GEA jobs to slurm
- [01_02_DF_pooled_GEA_interior_kickoff.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/01_02_DF_pooled_GEA_interior_kickoff.ipynb) - create covariance matrix for interior variety structure correction and submit GEA jobs to slurm
- [02_01_DF_pooled_GEA_coastal_gather.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/02_01_DF_pooled_GEA_coastal_gather.ipynb) - retrieve coastal variety GEA jobs from slurm and combine results from replicates into one dataframe
- [02_02_DF_pooled_GEA_interior_gather.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/02_baypass/02_02_DF_pooled_GEA_interior_gather.ipynb) - retrieve interior variety GEA jobs from slurm and combine results from replicates into one dataframe

[12_kmeans_pca](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/tree/main/12_kmeans_pca/) - use a combination of k-means clustering of PCA and geography to determine population colors for visualization purposes
- [01_pca_coastal.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/12_kmeans_pca/01_pca_coastal.ipynb) - run kmeans clustering to identify PCA groups for coastal Douglas-fir
- [02_pca_both_varieties.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/12_kmeans_pca/02_pca_both_varieties.ipynb) - create PCA figs across varieties
- [03_pca_interior.ipynb](https://nbviewer.org/github/brandonlind/douglas_fir_natural_populations/blob/main/12_kmeans_pca/03_pca_interior.ipynb) - run kmeans clustering to identify PCA groups for interior Douglas-fir

---

pythonimports module seen in notebooks is here: https://github.com/brandonlind/pythonimports
