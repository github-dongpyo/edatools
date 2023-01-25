
# edatools

<!-- badges: start -->
<!-- badges: end -->

This is a demonstration package for the book [R in Action (3rd ed.)]
(https://www.manning.com/books/r-in-action-third-edition).
It contains functions for exploratory data analysis.

## Installation

You can install the development version of edatools like so:

``` r
if(!require(remotes)){
   install.packages("remotes")
}
remotes::install_github("rkabacoff/edatools")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(edatools)
## basic example code
df_info<- contents(happiness)
df_info
plot(df_info)
```

