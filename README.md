# rEDM
```
Package: rEDM
Type: Package
Title: Applications of Empirical Dynamic Modeling from Time Series
Version: 0.4.7.1
Date: 2016-04-21
Author: Hao Ye, Adam Clark, Ethan Deyle
Maintainer: Hao Ye <hye@ucsd.edu>
Description: Contains C++ compiled objects that use time delay embedding to perform state-space reconstruction and nonlinear forecasting and an R interface to those objects using 'Rcpp'. It supports both the simplex projection method from Sugihara & May (1990) <DOI:10.1038/344734a0> and the S-map algorithm in Sugihara (1994) <DOI:10.1098/rsta.1994.0106>. In addition, this package implements convergent cross mapping as described by Sugihara et al. (2012) <DOI:10.1126/science.1227079>.
License: GPL-3 | file LICENSE
NeedsCompilation: yes
Imports: Rcpp (>= 0.11.5), methods
LinkingTo: Rcpp
RcppModules: lnlp_module, block_lnlp_module, ccm_module
Suggests: knitr,
    rmarkdown
VignetteBuilder: knitr
```
