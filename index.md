---
title: Distance Sampling Examples
layout: index

---

# Distance Sampling Examples

Here you can find a set of worked examples ("vignettes") demonstrating various aspects of distance sampling design and analysis using free software tools we have created and maintain. At present they focus on R packages; for examples using Distance for Windows see Chapter 3 ("Getting started") of the Distance manual.

Examples below are based upon data sets available in the R packages `dssd` (for survey design) and `Distance` (for analysis of distance sampling surveys).  All examples are provided as Rmarkdown documents.  For information about using Rmarkdown files, consult [this R-Studio website](https://rmarkdown.rstudio.com/).

# Examples with R packages

- [Getting started with survey design using `dssd`](dssd-getting-started/GettingStarted.html): Use of the package `dssd` to create a survey design within a study-area, and examine properties of the design such as how well it covers the study area and  average transect lengths.  The example uses a parallel line transects; other designs available in the `dssd` package follow from this example. [Rmarkdown file](dssd-getting-started/GettingStarted.Rmd)
- [Multiple strata in `dssd`](dssd-multi-strata/MultiStrataVignette.html): An example of how to create a design in `dssd` that contains multiple strata, with different design characteristics in each stratum. [Rmarkdown file](dssd-multi-strata/MultiStrataVignette.Rmd)
- [Analysis of line transect data](Distance-lines/linetransects.html): Line transect data of winter wrens in Scotland.  An example of model fitting, model selection, goodness of fit assessment.  Basic analysis skills required for any distance sampling analysis. [Rmarkdown file](Distance-lines/linetransects.Rmd)
- [Analysis of point transect data](Distance-points/pointtransects.html): Point transect analysis of savannah sparrow data set from Knopf et al. (1988). [Rmarkdown file](Distance-points/pointtransects.Rmd)
- [Variance estimation](Distance-variance/variance.html): Variance estimation examining three approaches: delta-method, bootstrap and bootstrap incorporating model uncertainty.  Based on line transect data of winter wrens from Buckland (2006). [Rmarkdown file](Distance-variance/variance.Rmd)
- [Stratification](Distance-strata/strata.html): Analysis of stratified survey design, including model selection to determine whether stratum-specific detection functions are necessary.  Uses point transect analysis of savannah sparrow data set from Knopf et al. (1988). [Rmarkdown file](Distance-strata/strata.Rmd)
- [Detection function modelling with covariates](Distance-covariates/covariates.html): Bringing covariates into detection function, using amakihi data from Marques et al. (2007). [Rmarkdown file](Distance-covariates/covariates.Rmd)
- [Cue count analysis](Distance-cues/cuecounts.html): Cue counting example based on line transect data of winter wrens from Buckland (2006).  Incorporating song rate in analysis. [Rmarkdown file](Distance-cues/cuecounts.Rmd)
- [Indirect survey methods](Distance-mult/multipliers.html): Estimation of Sika deer density based upon deer pellet distance sampling data.  Includes estimation of decay rate using logistic regression and multiplier based on dung production rates.  Using data from Marques et al. (2001). [Rmarkdown file](Distance-mult/multipliers.Rmd)
- [Double observer methods](mrds-golftees/mrds-golftees.html): Full independence and point independence analysis of golf tee data from multiple observers. [Rmarkdown file](mrds-golftees/mrds-golftees.Rmd)
- [Density surface model for point transects](dsm-point/hare_point_transect_dsm.html): Point transect survey of hares in France.  Simple density surface model with (x,y) predictor; thanks to Guillaume Souchay, French National Hunting and Wildlife Agency for data and analysis. [Rmarkdown file](dsm-point/hare_point_transect_dsm.Rmd) *Place all following files in same directory as .Rmd*
    - [Point transect survey csv](dsm-point/Hare_data.csv)
    - [Study area shapefile shp](dsm-point/Contour_Rouillacais.shp)
    - [Study area shapefile shx](dsm-point/Contour_Rouillacais.shx)
    - [Study area shapefile dbf](dsm-point/Contour_Rouillacais.dbf)
    - [Point station shapefile shp](dsm-point/Rouillacais_points.shp)
    - [Point station shapefile shx](dsm-point/Rouillacais_points.shx)
    - [Point station shapefile dbf](dsm-point/Rouillacais_points.dbf)
    
