
<!-- README.md is generated from README.Rmd. Please edit that file -->

# DNA Methylation Arrays Processing And Quality-Control <!--<img src="man/figures/dmapaq.png" align="right" width="120" />-->

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![GitHub
tag](https://img.shields.io/github/tag/mcanouil/dmapaq.svg?label=latest%20tag&include_prereleases)](https://github.com/mcanouil/dmapaq)
<!-- badges: end -->

## Installation

``` r
# Install dmapaq from CRAN:
install.packages("dmapaq")

# Or the the development version from GitHub:
# install.packages("remotes")
remotes::install_github("mcanouil/dmapaq")
```

## Overview

  - `read_idats()` allows to efficiently import idats files mostly using
    [minfi](https://bioconductor.org/packages/minfi/) functions.
  - `qc_idats()` allows to compute quality-control of methylation array
    from Illumina using a [rmarkdown
    template](inst/rmarkdown/templates/qc_idats/skeleton/skeleton.Rmd).
  - `ggheatmap()` allows to compute heatmap with dendrogram on x-axis
    and y-axis using [ggplot2](https://ggplot2.tidyverse.org/).

## Getting help

If you encounter a clear bug, please file a minimal reproducible example
on [github](https://github.com/omicsr/dmapaq/issues).  
For questions and other discussion, please contact the package
maintainer.

-----

Please note that this project is released with a [Contributor Code of
Conduct](.github/CODE_OF_CONDUCT.md).  
By participating in this project you agree to abide by its terms.
