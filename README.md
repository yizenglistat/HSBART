# wsBART: Weighted Soft Bayesian Additive Trees

## Description

- To incorporate weights into softBART used for heteroskedastic model.
- To embed the softBART into a larger model without auto-updating variance parameters. 
- Add more flexibilities in MCMC.

## Installation

To install the package, if you are a mac OSX user, you should install the gfortran library from [here](https://cran.r-project.org/bin/macosx/tools/) first, otherwise, you simply install as follows:

``` r
library(devtools)
install_github("yizenglistat/wsBART")
```

## Usage

Assume that Y<sub>i</sub>= f(x) + &epsilon;<sub>i</sub> with &epsilon;<sub>i</sub> follows a normal distribution with mean 0 and variance &sigma;<sup>2</sup>/w<sub>i</sub>, for i=1,...,N. Here w<sup>1/2</sup>'s are our weight vector in the package. 

Note you could still recover the original SoftBart functionality without feeding the weights into it or set the weights to be ones. 