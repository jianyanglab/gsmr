# GSMR
 
GSMR (Generalised Summary-data-based Mendelian Randomisation) is a statistical method that uses GWAS summary statistics to test for a putative causal association between two phenotypes (e.g., a modifiable risk factor and a disease) based on a multi-SNP model

## Installation

### Packages required to be pre-installed

Please install the following packages first. 

```{r}
# survey
install.packages('survey')
```

### Installation of gsmr

Please run the following to install the `gsmr` package:
```
devtools::install_github("jianyanglab/gsmr")
```

or download the package [here](https://yanglab.westlake.edu.cn/software/gsmr/static/gsmr_1.0.6.tar.gz) and install it using the following command
```
install.packages("~/Downloads/gsmr_1.0.6.tar.gz", type = "source", repo = NULL)
```

## Example analysis pipeline

Here is an example of the `gsmr` workflow to get started:

```
Under construction
```


# Improved version of GSMR (GSMR2)
We have developed a new version of GSMR, in which the HEIDI-outlier filtering algorithm is more robust to the directional pleiotropy. 
Please check the [GSMR2](https://github.com/jianyanglab/gsmr2) repository if you are interested.

# Citation

Zhu, Z. et al. (2018) Causal associations between risk factors and common diseases inferred from GWAS summary data. [[Full text](https://www.nature.com/articles/s41467-017-02317-2)]

For questions, please email us at Jian Yang (jian.yang@westlake.edu.cn)

For bugs, please raise an issue in this repository.
