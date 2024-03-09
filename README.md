<!-- badges: start -->

[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental) [![R-CMD-check](https://github.com/drejom/scCity/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/drejom/scCity/actions/workflows/R-CMD-check.yaml)

<!-- badges: end -->

# scCity <img src="man/figures/logo.png" align="right" height="240"/>

The goal of scCity is to streamline the process of conducting single-cell analyses on the City of Hope High-Performance Computing (HPC) infrastructure. By leveraging the `hprcc` package (https://github.com/cohmathonc/hprcc/), scCity abstracts the complexities involved in a typical single-cell analysis, enabling researchers to quickly and efficiently begin their work. The package integrates seamlessly with the R/Bioconductor container environment, as detailed here (https://github.com/drejom/vscode-rbioc), facilitating a smooth workflow for users of the City of Hope HPC.

## Installation

To install the development version of scCity, use the following command:

``` r
remotes::install_github("drejom/scCity")
```
Please note, the remotes package is required for this installation method. If you do not have remotes installed, you can install it first using install.packages("remotes").

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(scCity)
## basic example code
```
