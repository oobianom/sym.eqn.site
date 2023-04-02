# Installation

## Install from CRAN

With R installed on your Windows or UNIX operating system, install the symbol.equation.gpt package from the Comprehensive R Archive Network from the console as shown below

```r
install.packages("symbol.equation.gpt")
```


## Install from GitHub

To install from GitHub, you need to first install the devtools R package. This package provides functions for installing directly from GitHub

```r
install.packages("devtools")
library("devtools")
install_github("oobianom/symbol.equation.gpt")
```

## Install required dependencies

Know that various R packages are required in order to efficiently use and run the symbol.equation.gpt R package. Below are the three most important packages

```r
install.packages("r2symbols")
install.packages("nextGenShinyApps")
install.packages("shiny")
```

## Loading package after installation (optional)

You may load the package after installation. This is optional because the package is intended to run as an RStudio addins

```r
library("symbol.equation.gpt")
```
