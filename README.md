
# mathR

The goal of mathR is to ...

## Installation

You can install the development version of mathR using:

``` r
if (!require(remotes)){
  install.packages("remotes")
  library(remotes)
}

remotes::install_github("marginal-latte/mathR")
```

## Example

This is a basic example which shows you how to add two vectors:

``` r
library(mathR)
x <- 1:3
y <- c(10,15,20)

add(x,y)
```

