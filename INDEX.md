
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/plinkQC)](https://cran.r-project.org/package=plinkQC) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Downloads](http://cranlogs.r-pkg.org/badges/grand-total/plinkQC?color=blue)](http://cran.rstudio.com/web/packages/plinkQC/index.html)

<i class="fa fa-map" aria-hidden="true"></i> plinkQC
----------------------------------------------------

**plinkQC** is a R/CRAN package for **genotype quality control** in genetic association studies. It makes PLINK basic statistics (e.g.missing genotyping rates per individual, allele frequencies per genetic marker) and relationship functions easily accessible from within R and allows for automatic evaluation of the results.

**plinkQC** generates a per-individual and per-marker quality control report. A step-by-step guide on how to run these analyses can be found [here](https://hannahvmeyer.github.io/plinkQC/articles/plinkQC.html).

Individuals and markers that fail the quality control can subsequently be removed with **plinkQC** to generate a new, clean dataset.

**plinkQC** facilitates an ancestry check for study individuals based on comparison to reference datasets. The processing of the reference datasets is documented in detail [here](https://hannahvmeyer.github.io/plinkQC/articles/AncestryCheck.html).

Removal of individuals based on relationship status via **plinkQC** is optimised to retain as many individuals as possible in the study.

![](docs/qc.png)

<i class="fa fa-rocket" aria-hidden="true"></i> Installation
------------------------------------------------------------

The current github version of **plinkQC** is: 0.2.0 and can be installed via

``` r
library(devtools)
install_github("HannahVMeyer/plinkQC")
```

The current CRAN version of **plinkQC** is: 0.2.0 and can be installed via

``` r
install.packages("plinkQC")
```

A log of version changes can be found [here](news/index.html).
