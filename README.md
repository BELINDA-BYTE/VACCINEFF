
## *vaccineff*: an R package with tools for estimating vaccine effectiveness and vaccinne related metrics <img src="man/figures/vaccineff.png" align="right" width="130"/>

<!-- badges: start -->

[![License:
MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/license/mit/)
[![Codecov test
coverage](https://codecov.io/gh/%7B%7B%20gh_repo%20%7D%7D/branch/main/graph/badge.svg)](https://app.codecov.io/gh/%7B%7B%20gh_repo%20%7D%7D?branch=main)
[![lifecycle-concept](https://raw.githubusercontent.com/reconverse/reconverse.github.io/master/images/badge-concept.svg)](https://www.reconverse.org/lifecycle.html#concept)

<!-- badges: end -->

**vaccineff** is an R package that offers tools for estimating the
vaccine effectiveness, using a series of epidemiological designs
(including cohort studies, test-negative case-control, and screening
methods). The package provides a set of features for preparing the data,
to analyse different study designs and for assessing the performance of
the models.

**vaccineff** is developed at [Pontificia Univeridad
Javeriana](https://www.javeriana.edu.co/inicio) as part of the
[Epiverse-TRACE program](https://data.org/initiatives/epiverse/).

## Installation

You can install the development version of **vaccineff** from
[GitHub](https://github.com/) with:

``` r
if(!require("remotes")) install.packages("remotes")
remotes::install_github("TRACE-LAC/vaccineff")
```

## Quick start

**vaccineff** provides a minimal datasets that can be used to test out
each design `(cohortdata, testnegdata, screeningdata)`

\# Load example `cohortdata` incuded in the package

### Contributions

Contributors to the project include:

-   [David Santiago Quevedo](https://github.com/davidsantiagoquevedo)
    (author)

-   [Zulma M. Cucunubá](https://github.com/zmcucunuba) (author)

-   [Santiago Loaiza](https://github.com/santilo9513) (author)

-   [Geraldine Gómez](https://github.com/GeraldineGomez) (contributor)
