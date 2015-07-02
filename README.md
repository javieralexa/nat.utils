# nat.utils
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/nat.utils)](http://cran.r-project.org/web/packages/nat.utils) 
[![Release Version](https://img.shields.io/github/release/jefferis/nat.utils.svg)](https://github.com/jefferis/nat.utils/releases/latest) 
[![Build Status](https://travis-ci.org/jefferis/nat.utils.png)](https://travis-ci.org/jefferis/nat.utils)
[![Coverage Status](https://img.shields.io/coveralls/jefferis/nat.utils.svg)](https://coveralls.io/r/jefferis/nat.utils?branch=master)
An R package containing utility functions to support the NeuroAnatomy Toolbox (nat)

## Background
This package is part of a primarily R based toolbox for neuroanatomy that has
been in continuous development since 2002. Originally a loosely organised
collection of R functions and scripts, I am now transitioning some of the code
that may be of more general use to formal R packages. As one of the smaller sets
of code with minimal dependencies, these utility functions are the first group
of functions to be converted.

The main original code base is at https://github.com/jefferis/AnalysisSuite. The
recommended way to access this code is through a wrapper R package
[nat.as](https://github.com/jefferis/nat.as) available on github. There is now
also a formal [nat](https://github.com/jefferis/nat) R package undergoing
rapid development on github (the recommended installation source). A stable 
release is also available on CRAN. In the fullness of time I expect that this
`nat` package will collect together a number of sub-packages or extension 
packages called `nat.*`.

## Installation

### Released versions
From CRAN - the recommended option for simplicity and since this package is not
under heavy development:

```r
install.packages("nat.utils")
```

### Bleeding Edge
Straight from github with Hadley Wickham's [devtools](https://github.com/hadley/devtools) package:

```r
if(!require("devtools")) install.packages("devtools")
devtools::install_github('nat.utils','jefferis')
```
Note: Windows users need [Rtools](http://www.murdoch-sutherland.com/Rtools/) to
install in this way.
