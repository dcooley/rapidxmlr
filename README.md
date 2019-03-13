# rapidxml

R interface to the C++ header-only Rapidxml library

This package is using v1.13 of rapidxml. 

## Install

Install the development version with

```r
devtools::install_github("tospig/rapidxml")
```

## Using rapidxml

To use rapidxml in your own package, add a dependency to rapidxml to your cpp files before a call to #include <Rcpp.h>

```c++
// [[Rcpp::depends(rapidxml)]]

#include <Rcpp.h>
```



