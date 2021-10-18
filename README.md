
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rKenyaCensus

<!-- badges: start -->

<!-- badges: end -->

The goal of rKenyaCensus is to provide tidy datasets obtained from the
Kenya Population and Housing Census results.

## Installation

You can install the development version of rKenyaCensus from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github('Shelmith-Kariuki/rKenyaCensus')
```

And the released version from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("rKenyaCensus")
```

*Note: This package is not yet available on CRAN.*

**Disclaimer alert**: This package is still under development. The data
is being cleaned and refined on a daily basis. Changes are being pushed
to github every afternoon beginning 29th April, 2020. Please keep
refreshing (re-downloading) the package, so that you can have the most
updated version. Incase of any issue, please raise an issue on github.

## Example

Information on each of the datasets can be found in the DataCatalogue
dataset.

``` r
data("DataCatalogue")
```

The following is a basic example to show how the datasets can be
extracted:

``` r

## Suppose we want to obtain the dataset that shows the distribution of Population by Sex and County. This is Table 2.2 in Volume 1.

## Load the package
library(rKenyaCensus)

## Extract the table
df <- V1_T2.2

## To learn more about the dataset, run the following command
?V1_T2.2
```
