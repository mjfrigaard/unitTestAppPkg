
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `utap`

<!-- badges: start -->
<!-- badges: end -->

The goal of `utap` is to demonstrate how to perform unit tests for shiny
utility functions with [`testthat`](https://testthat.r-lib.org/).

## Installation

You don’t want to install this package, but you might want to download
it as an example (or read through [this
post](https://mjfrigaard.github.io/posts/test-shiny-p1/) to learn about
it’s contents).

# R files

    #> R/
    #> ├── column_classes.R
    #> ├── pull_binary_cols.R
    #> ├── pull_cat_cols.R
    #> ├── pull_facet_cols.R
    #> ├── pull_numeric_cols.R
    #> ├── utap-package.R
    #> └── utils.R

# Unit tests

    #> tests/testthat/
    #> ├── test-column_classes.R
    #> ├── test-pull_binary_cols.R
    #> ├── test-pull_cat_cols.R
    #> ├── test-pull_facet_cols.R
    #> ├── test-pull_numeric_cols.R
    #> └── test-utils.R

# Unit test results

``` bash
==> devtools::test()

ℹ Testing utap
✔ | F W S  OK | Context
✔ |        25 | column_classes                     
✔ |        29 | pull_binary_cols                   
✔ |         4 | pull_cat_cols                      
✔ |        20 | pull_facet_cols                    
✔ |         5 | pull_numeric_cols                  
✔ |         3 | utils                              

══ Results ════════════════════════════════════════
Duration: 1.8 s

[ FAIL 0 | WARN 0 | SKIP 0 | PASS 86 ]
```
