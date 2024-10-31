[![R-CMD-check](https://github.com/KWB-R/BerlinWaterModel/workflows/R-CMD-check/badge.svg)](https://github.com/KWB-R/BerlinWaterModel/actions?query=workflow%3AR-CMD-check)
[![pkgdown](https://github.com/KWB-R/BerlinWaterModel/workflows/pkgdown/badge.svg)](https://github.com/KWB-R/BerlinWaterModel/actions?query=workflow%3Apkgdown)
[![codecov](https://codecov.io/github/KWB-R/BerlinWaterModel/branch/main/graphs/badge.svg)](https://codecov.io/github/KWB-R/BerlinWaterModel)
[![Project Status](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/BerlinWaterModel)]()
[![R-Universe_Status_Badge](https://kwb-r.r-universe.dev/badges/BerlinWaterModel)](https://kwb-r.r-universe.dev/)

# BerlinWaterModel

R Package of Berlin Water Model.

## Installation

For details on how to install KWB-R packages checkout our [installation tutorial](https://kwb-r.github.io/kwb.pkgbuild/articles/install.html).

```r
### Optionally: specify GitHub Personal Access Token (GITHUB_PAT)
### See here why this might be important for you:
### https://kwb-r.github.io/kwb.pkgbuild/articles/install.html#set-your-github_pat

# Sys.setenv(GITHUB_PAT = "mysecret_access_token")

# Install package "remotes" from CRAN
if (! require("remotes")) {
  install.packages("remotes", repos = "https://cloud.r-project.org")
}

# Install KWB package 'BerlinWaterModel' from GitHub
remotes::install_github("KWB-R/BerlinWaterModel")
```

## Documentation

Release: [https://kwb-r.github.io/BerlinWaterModel](https://kwb-r.github.io/BerlinWaterModel)

Development: [https://kwb-r.github.io/BerlinWaterModel/dev](https://kwb-r.github.io/BerlinWaterModel/dev)
