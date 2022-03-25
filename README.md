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

\begin{equation}
Y=x+s+\epsilon_i
\end{equation}

To Be Continue