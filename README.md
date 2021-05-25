# Test different packages before data analyses

In this repository, I included the codes for testing some important packages 
that I used for my data analyses.

## Use `Rcpp`

This repository contains my test codes for using `Rcpp` package. 
By using `Rcpp`, we can implement C++ codes into R more conveniently. 

Some basic syntax of C++ were shown in `RcppTest1.Rmd` document.

## `TOAST` R package

This R package is recently published and used for estimating cell composition 
for different tissues. 

I will test and also compare `TOAST` package with `RefFreeEWAS` R package. 
These 2 packages are different in terms of the feature selection process, 
so I want to see whether the results from these 2 packages will be different 
or not.

## Test the cell type adjustment example, from the 2016 article 
(An evaluation of methods correcting for cell-type heterogeneity in DNA 
methylation studies)

This example is from github (https://github.com/GreenwoodLab/CellTypeAdjustment).

## `TCA` R package

This package contains TCA method of re-estimating cell proportion inferred from 
DNA methylation array data with reference-based method, and also method for 
performing cell type specific differential methylation analysis.

TCA vignette: 
https://cran.r-project.org/web/packages/TCA/vignettes/tca-vignette.html