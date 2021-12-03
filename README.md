
<!-- README.md is generated from README.Rmd. Please edit that file -->

# hydrofabric

<!-- badges: start -->

[![R-CMD-check](https://github.com/NOAA-OWP/hydrofabric/workflows/R-CMD-check/badge.svg)](https://github.com/NOAA-OWP/hydrofabric/actions)
<!-- badges: end -->

### Overview

There are three major types of network refactoring needed to meet a
broad set of needs:

1.  One based on a flowline length criteria (routing)
2.  One that aims for a uniform catchment size (rainfall-runoff)
3.  A POI version that forces things down to a set critical locations
    (PRMS).

`hydrofabric` is a set of packages that work in harmony to meet these
needs. The package is designed to make it easy to install and load core
packages across users and organizations in a single command.

## Installation

``` r
# Install the development version from GitHub
# install.packages("remotes")
remotes::install_github("NOAA-OWP/hydrofabric")
```

## Usage

`library(hydrofabric)` will load the core packages:

-   [nhdarrow]() (In development)
-   [nwmdata]() (In development)
-   [zonal](https://github.com/mikejohnson51/zonal) for catchment
    parameter estimation
-   [nhdplusTools](https://github.com/usgs-r/nhdplusTools/) for network
    manipulation
-   [hyRefactor](https://github.com/dblodgett-usgs/hyRefactor) for
    network factoring
-   [hyAggregate](https://github.com/mikejohnson51/hyAggregate) for
    network aggregation
-   [hyRelease](https://github.com/mikejohnson51/hyRelease) for data
    releases running elected subroutines

And you can check that all tidyverse packages are up-to-date with
`tidyverse_update()`:

## Code of Conduct

Please note that the project is released with a [Contributor Code of
Conduct](). By contributing to this project, you agree to abide by its
terms.
