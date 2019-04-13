
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ff4

<!-- badges: start -->

<!-- badges: end -->

The goal of ff4 is to …

## Installation

Install the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ijlyttle/ff4")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ff4)
## basic example code

x <- factor(c("a", "b"))
y <- factor(c("c", "d"))

fbind(x, y)
#> [1] a b c d
#> Levels: a b c d
```
