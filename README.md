scLink: Inferring gene networks from single-cell gene expression data
================
Wei Vivian Li

Rutgers Department of Biostatistics and Epidemiology

<!-- README.md is generated from README.Rmd. Please edit that file -->
Latest News
-----------
> 2020/06/01: Version 1.0.0 released!

> 2020/03/05: Version 0.0.9 released!

Introduction
------------

Any suggestions on the package are welcome! For technical problems, please report to [Issues](https://github.com/Vivianstats/scLink/issues). For suggestions and comments on the method, please contact Vivian (<vivian.li@rutgers.edu>).

You can also browse scLink's applications and results at its [web app](https://rutgersbiostat.shinyapps.io/sclink/).

Installation
------------

The package is available on CRAN. For installation please use the following codes in `R`
``` r
install.packages("scLink")
```
In addition, please also install the QUIC package
``` r
install.packages("QUIC")
```

Quick start
-----------

`scLink` has three main functions:

-   `sclink_norm` for pre-processing gene expression data
-   `sclink_cor` for calculating the co-expression matrix by scLink
-   `sclink_net` for constructing the gene co-expression network by scLink

For detailed usage, please refer to the package [manual](https://github.com/Vivianstats/scLink/blob/master/inst/docs/) or [vignette](https://github.com/Vivianstats/scLink/blob/master/vignettes/).

