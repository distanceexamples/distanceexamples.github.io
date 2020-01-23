---
title: Distance Sampling Examples
layout: index

---

# Distance Sampling Examples

Here you can find a set of worked examples ("vignettes") demonstrating various aspects of distance sampling design and analysis using free software tools we have created and maintain. At present they focus on R packages; for examples using Distance for Windows see Chapter 3 ("Getting started") of the Distance manual.

# Examples with R packages

- [Getting started with survey design using `dssd`](dssd-getting-started/GettingStarted.html): Use of the package `dssd` to create a survey design within a study-area, and examine properties of the design such as how well it covers the study area and  average transect lengths.  The example uses a parallel line transects; other designs available in the `dssd` package follow from this example.
- [Multiple strata in `dssd`](dssd-multi-strata/MultiStrataVignette.html): An example of how to create a design in `dssd` that contains multiple strata, with different design characteristics in each stratum.
- [Analysis of line transect data](Distance-lines/linetransects.html): Line transect data of winter wrens in Scotland.  An example of model fitting, model selection, goodness of fit assessment.  Basic analysis skills required for any distance sampling analysis.
- [Analysis of point transect data](Distance-points/pointtransects.html): Point transect analysis of savannah sparrow data set from Knopf et al. (1988).
- [Variance estimation](Distance-variance/variance.html): Variance estimation examining three approaches: delta-method, bootstrap and bootstrap incorporating model uncertainty.  Based on line transect data of winter wrens from Buckland (2006).
- [Stratification](Distance-strata/strata.html): Analysis of stratified survey design, including model selection to determine whether stratum-specific detection functions are necessary.  Uses point transect analysis of savannah sparrow data set from Knopf et al. (1988).
- [Detection function modelling with covariates](Distance-covariates/covariates.html): Bringing covariates into detection function, using amakihi data from Marques et al. (2007).
- [Cue count analysis](Distance-cues/cuecounts.html): Cue counting example based on line transect data of winter wrens from Buckland (2006).  Incorporating song rate in analysis.
- [Indirect survey methods](Distance-mult/multipliers.html): Estimation of Sika deer density based upon deer pellet distance sampling data.  Includes estimation of decay rate using logistic regression and multiplier based on dung production rates.  Using data from Marques et al. (2001).
