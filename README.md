Welcome! 

This is the teaching materials for a workshop introducing R and R-spatial at the [FOSS4G2022](https://2022.foss4g.org/index.php) conference.

![FOSS4G2022 logo](https://2022.foss4g.org/img/logo/logo-dark.png)

This workshop will be facilitated by Jakub Nowosad and Nicolas Roelandt, from 
Adam Mickiewicz University in Poznań (Poland) and Gustave Eiffel university (France) respectively.

![Gustave Eiffel university and Adam Mickiewicz University in Poznań logos](images/logos.png)

## Pre-requisites {-}

1. A working installation of R (following [CRAN recommandations](https://cran.r-project.org/) for your computer)

R comes with the RGui interface.
It is usable but for a better user experience we recommend using [Rstudio](https://www.rstudio.com/products/rstudio/download/#download).

<!--vscode??-->
[Jupyter Notebook](https://jupyter.org/) with the [IRKernel](https://irkernel.github.io/installation/) can also be a good option.

2. R packages

Please run those commands into the R console:

```{r pre-requisites-packages, eval = FALSE}
# Install remote package from CRAN Repo
install.packages(remotes)

# Install workshop and its dependencies
remotes::install_github("Bakaniko/foss4g2022-getting-started-rspatial")
```
