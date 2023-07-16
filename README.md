# 2023 SISMID Spatial Epidemiology

**Course Dates**: Mon, July 17 to Wed, July 19

## Introduction

Welcome to the 2023 SISMID course on Spatial Statistics for Epidemiology and Public Health! 
Spatial methods are now used in many disciplines and play an important role in epidemiology and public health. This module gives an introduction to spatial methods. In particular, we will present methods for assessment of clustering, cluster detection, spatial regression, small area estimation, and disease mapping. Methods will be described for both point data (in which cases and non-cases (or a sample thereof) have an associated point location) and count data (in which the numbers of cases and non-cases in a set of geographical areas are available).

An introduction to Geographic Information Systems (GIS) will be provided. The important extension to space-time analysis will be described, which is crucial for the analysis of infectious disease data with a spatial component.

Many examples will be presented, with analysis carried out in the R programming environment.

## Prerequisites

This module assumes knowledge of the material in Module 1: Probability and Statistical Inference, though not necessarily from taking that module. Some prior knowledge of R would be helpful.

## Installing R and RStudio

This SISMID module exclusively uses R. We recommend R 4.0 and above. You can download a recent version [here](https://www.r-project.org/).

We also recommend using RStudio as the main GUI interface. You can install a free version [here](https://posit.co/download/rstudio-desktop/). 

Installation of R and RStudio should proceed smoothly on most operating systems. Detailed instructions can be found [here](http://rafalab.dfci.harvard.edu/dsbook/installing-r-rstudio.html). 

## Installing R-INLA

You will need to download the INLA package to run the code in this module. 

The [INLA](https://www.r-inla.org/) package performs approximate Bayesian inference for latent Gaussian models. Installing the package is a bit different than normal since it is not on CRAN, the central software repository for R packages. Detailed instructions for installing the stable/testing can be found [here](https://www.r-inla.org/download-install).

## Schedule

1. Introduction (**Waller**)
2. GIS, Mapping (**Waller**)
3. Areal Data (EDA, clustering) (**Chang**)
4. Disease Mapping  (CARs, SAR) (**Chang**)
5. Spatial regresssion + Spatial Coefficient (**Waller**)
6. Gaussian Process (**Chang**)
7. Point process (**Waller**)
8. Multivariate Process (**Chang**)
9. Spatial infectious disease (SIR), ecology (**Waller**)
10. Space-time models (**Chang**)

## Reference

[Waller, L. and Gotway, C. (2004). Applied Spatial Statistics for Public Health Data. New York, John Wiley and Sons.](https://onlinelibrary-wiley-com.proxy.library.emory.edu/doi/book/10.1002/0471662682)

[Geocomputation with R](https://r.geocompx.org/index.html)

[Spatial Data Science](https://r-spatial.org/book/)

[Spatial-Temporal Statistics with R](https://spacetimewithr.org/)

[Geospatial Health Data: Modeling and Visualization with R-INLA and Shiny](https://www.paulamoraga.com/book-geospatial/)

[Advanced Spatial Modeling with Stochastic Partial Differential Equations Using R and INLA](https://becarioprecario.bitbucket.io/spde-gitbook/index.html)

## Contact

If you have any questions feel free to contact the following course instructors and TA's, or send a message in the class Slack channel.

Instructors: [Lance Waller](mailto:lwaller@emory.edu), [Howard Chang](mailto:hhchang.emory.edu)

Teaching Assistant: [Thomas Hsiao](mailto:thomas.hsiao@emory.edu)
