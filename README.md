
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rmddm

<!-- badges: start -->

[![Build
Status](https://travis-ci.org/wkdavis/rmddm.svg?branch=master)](https://travis-ci.org/wkdavis/rmddm)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/wkdavis/rmddm?branch=master&svg=true)](https://ci.appveyor.com/project/wkdavis/rmddm)
[![codecov](https://codecov.io/gh/wkdavis/rmddm/branch/master/graph/badge.svg)](https://codecov.io/gh/wkdavis/rmddm)
<!-- badges: end -->

## Overview

rmddm provides Rmarkdown templates for use in data mining, specifically
those projects following the
[CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining)
process. The package is based on the
[rticles](https://github.com/rstudio/rticles) package.

## Installation

Installing rmddm from github with:

``` r
# install.packages("remotes")
remotes::install_github("wkdavis/rmddm")
```

## Example

Creating an RMarkdown template with the CRISP-DM structure:

``` r
library(rmarkdown)
draft("MyReport.Rmd", template = "crispdm_report", package = "rmddm", edit=FALSE)
```
