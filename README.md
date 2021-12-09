
# greta.pkgdown 

<!-- badges: start -->

[![R-CMD-check](https://github.com/greta-dev/greta.pkgdown/workflows/R-CMD-check/badge.svg)](https://github.com/greta-dev/greta.pkgdown/actions)
<!-- badges: end -->

## Overview

`greta.pkgdown` provides a custom [pkgdown](https://pkgdown.r-lib.org)
template for greta extension packages. Please don’t use it for your own package.

## Templates

For all sites, ensure that `DESCRIPTION` contains:

    Config/Needs/website: greta-dev/greta.pkgdown

### greta packages

``` yaml
template:
  package: tidytemplate
  bootstrap: 5
```
