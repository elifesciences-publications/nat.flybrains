# nat.flybrains
[![Build Status](https://travis-ci.org/jefferislab/nat.flybrains.svg)](https://travis-ci.org/jefferislab/nat.flybrains)

Additional data for use with the [NeuroAnatomy Toolbox](https://github.com/jefferis/nat) (nat)

## Installation
There is currently no released version on CRAN.

### Bleeding Edge
You can, however, download the [tar ball](https://github.com/jefferislab/nat.flybrains/tarball/master),
and run `R CMD INSTALL` on it, or use the **devtools** package to install the development version:

```r
# install.packages("devtools")
devtools::install_github("nat.flybrains", "jefferislab")
```

Note: Windows users need [Rtools](http://www.murdoch-sutherland.com/Rtools/) and
[devtools](http://CRAN.R-project.org/package=devtools) to install this way.
