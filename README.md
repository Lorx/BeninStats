
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BeninStats

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/Lorx/BeninStats.svg?branch=master)](https://travis-ci.org/Lorx/BeninStats)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
<!-- badges: end -->

The goal of BeninStats is to collect different data from different
sources for Benin Republic.

## Installation

You can install the released version of BeninStats from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("BeninStats")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Lorx/BeninStats")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(BeninStats)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
names(pop_by_age)
#> [1] "annee"                 "age"                   "both_sexes_population"
#> [4] "male_population"       "female_population"     "percent_both_sexes"   
#> [7] "percent_male"          "percent_female"        "sex_ratio"
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub\!
