---
title: Distance Sampling Examples
layout: index

---

# Distance Sampling Examples

Here you can find a set of worked examples ("vignettes") demonstrating various aspects of distance sampling design and analysis using free software tools we have created and maintain. At present they focus on R packages; for examples using Distance for Windows see Chapter 3 ("Getting started") of the Distance manual.

Examples below are based upon data sets available in the R packages `dssd` (for survey design) and `Distance` (for analysis of distance sampling surveys).  All examples are provided as Rmarkdown documents.  For information about using Rmarkdown files, consult [this RStudio website](https://rmarkdown.rstudio.com/).

# Examples with R packages


|  | Survey design | Simple analyses | Ancillary information | Covariates | Simulation | Model-based analyses | Buckland et al. (2015) |
|----------------------------------|---------------|-----------------|-----------------------|------------|------------|----------------------|------------------------|
| [Design, basic](dssd-getting-started/GettingStarted-distill.html) [Rmd](dssd-getting-started/GettingStarted-distill.Rmd)| X |  |  |  |  |  |  |
| [Design, two strata](dssd-multi-strata/MultiStrataVignette-distill.html) [Rmd](dssd-multi-strata/MultiStrataVignette-distill.Rmd) | X |  |  |  |  |  |  |
| [Line transects, songbirds](Distance-lines/lines-distill.html) [Rmd](Distance-lines/lines-distill.Rmd) |  | X |  |  |  |  | X |
| [Point transects, songbirds](Distance-points/pointtransects-distill.html) [Rmd](Distance-points/pointtransects-distill.Rmd) |  | X |  |  |  |  |  |
| [Variance estimation](Distance-variance/variance-distill.html) [Rmd](Distance-variance/variance-distill.Rmd) |  |  |  |  |  |  |  |
| [Stratification](Distance-strata/strata-distill.html) [Rmd](Distance-strata/strata-distill.Rmd) |  |  |  |  |  |  |  |
| [Covariates in detection function](Distance-covariates/covariates-distill.html) [Rmd](Distance-covariates/covariates-distill.Rmd) |  |  |  | X |  |  | X |
| [Multi-species surveys](Distance-spec-covar/species-covariate-distill.html) [Rmd](Distance-spec-covar/species-covariate-distill.Rmd) |  |  |  | X |  |  |  |
| [Size bias adjustment](Distance-groupsize/Remedy-size-bias-for-dolphin-surveys.html) [Rmd](Distance-groupsize/Remedy size bias for dolphin surveys.Rmd) |  |  |  | X |  |  |  |
| [Cue counts](Distance-cues/cuecounts-distill.html) [Rmd](Distance-cues/cuecounts-distill.Rmd) |  |  | X |  |  |  | X |
| [Deer surveys from pellets](Distance-mult/multipliers-distill.html) [Rmd](Distance-mult/multipliers-distill.Rmd) |  |  | X |  |  |  |  |
| [Double observer methods](mrds-golftees/mrds-golftees-distill.html) [Rmd](mrds-golftees/mrds-golftees-distill.Rmd) |  |  |  |  |  |  |  |
| [Density surface lines](dsm-line-dolphins/mexico-analysis.html) [Rmd](dsm-line-dolphins/mexico-analysis.Rmd) |  |  |  |  |  | X | X |
| [Density surface points](dsm-point/hare_point_transect_dsm-distill.html) [Rmd](dsm-point/hare_point_transect_dsm-distill.Rmd) |  |  |  |  |  | X |  |
| [Simulation truncation decisions](DSsim-truncation/DSsim-examples.html) [Rmd](DSsim-truncation/DSsim-examples.Rmd) |  |  |  |  | X |  |  |
| [Model-based inference](book-bobwhite/bobwhite.html) [Rmd](book-bobwhite/bobwhite.Rmd) |  |  | X |  |  | X | X |
| [Lure surveys](book-crossbills/book-crossbills.html) [Rmd](book-crossbills/book-crossbills.Rmd) |  |  |  |  |  |  | X |
| [Simulation design contrasts](book-DSsim/DSsimstudy.html) [Rmd](book-DSsim/DSsimstudy.Rmd) |  |  |  |  | X |  | X |

<!--
- [Getting started with survey design using `dssd`](dssd-getting-started/GettingStarted-distill.html): Use of the package `dssd` to create a survey design within a study-area, and examine properties of the design such as how well it covers the study area and  average transect lengths.  The example uses a parallel line transects; other designs available in the `dssd` package follow from this example. [Rmarkdown file](dssd-getting-started/GettingStarted-distill.Rmd)
- [Multiple strata in `dssd`](dssd-multi-strata/MultiStrataVignette-distill.html): An example of how to create a design in `dssd` that contains multiple strata, with different design characteristics in each stratum. [Rmarkdown file](dssd-multi-strata/MultiStrataVignette-distill.Rmd)
- [Analysis of line transect data](Distance-lines/lines-distill.html): Line transect data of winter wrens in Scotland.  An example of model fitting, model selection, goodness of fit assessment.  Basic analysis skills required for any distance sampling analysis. [Rmarkdown file](Distance-lines/lines-distill.Rmd)
- [Analysis of point transect data](Distance-points/pointtransects-distill.html): Point transect analysis of savannah sparrow data set from Knopf et al. (1988). [Rmarkdown file](Distance-points/pointtransects-distill.Rmd)
- [Variance estimation](Distance-variance/variance-distill.html): Variance estimation examining three approaches: delta-method, bootstrap and bootstrap incorporating model uncertainty.  Based on line transect data of winter wrens from Buckland (2006). [Rmarkdown file](Distance-variance/variance-distill.Rmd)
- [Stratification](Distance-strata/strata-distill.html): Analysis of stratified survey design, including model selection to determine whether stratum-specific detection functions are necessary.  Uses point transect analysis of savannah sparrow data set from Knopf et al. (1988). [Rmarkdown file](Distance-strata/strata-distill.Rmd)
- [Detection function modelling with covariates](Distance-covariates/covariates-distill.html): Bringing covariates into detection function, using amakihi data from Marques et al. (2007). [Rmarkdown file](Distance-covariates/covariates-distill.Rmd)
- [Multi-species survey, species as covariate](Distance-spec-covar/species-covariate-distill.html): Use of species covariate to produce species-specific density estimates when number of detections for some species is small. [Rmarkdown file](Distance-spec-covar/species-covariate-distill.Rmd)
- [Size bias adjustment with group size as covariate](Distance-groupsize/Remedy-size-bias-for-dolphin-surveys.html): Because of the detection process, average group size in sample is a positively biased estimate of average group size in population.  This bias can be compensated by employing group size as a covariate in the detection function. [Rmarkdown file](Distance-groupsize/Remedy size bias for dolphin surveys.Rmd)
- [Cue count analysis](Distance-cues/cuecounts-distill.html): Cue counting example based on line transect data of winter wrens from Buckland (2006).  Incorporating song rate in analysis. [Rmarkdown file](Distance-cues/cuecounts-distill.Rmd)
- [Indirect survey methods](Distance-mult/multipliers-distill.html): Estimation of Sika deer density based upon deer pellet distance sampling data.  Includes estimation of decay rate using logistic regression and multiplier based on dung production rates.  Using data from Marques et al. (2001). [Rmarkdown file](Distance-mult/multipliers-distill.Rmd)
- [Double observer methods](mrds-golftees/mrds-golftees-distill.html): Full independence and point independence analysis of golf tee data from multiple observers. [Rmarkdown file](mrds-golftees/mrds-golftees-distill.Rmd)
- [Density surface model for line transects](dsm-line-dolphins/mexico-analysis.html): Line transect survey of pantropical spotted dolphins in the Gulf of Mexico. Data from NOAA. [Rmarkdown file](dsm-line-dolphins/mexico-analysis.Rmd)
- [Density surface model for point transects](dsm-point/hare_point_transect_dsm-distill.html): Point transect survey of hares in France.  Simple density surface model with (x,y) predictor; thanks to Guillaume Souchay, French National Hunting and Wildlife Agency for data and analysis. [Rmarkdown file](dsm-point/hare_point_transect_dsm-distill.Rmd) *Place all following files in same directory as .Rmd*
    - [Point transect survey csv](dsm-point/Hare_data.csv)
    - [Study area shapefile shp](dsm-point/Contour_Rouillacais.shp)
    - [Study area shapefile shx](dsm-point/Contour_Rouillacais.shx)
    - [Study area shapefile dbf](dsm-point/Contour_Rouillacais.dbf)
    - [Point station shapefile shp](dsm-point/Rouillacais_points.shp)
    - [Point station shapefile shx](dsm-point/Rouillacais_points.shx)
    - [Point station shapefile dbf](dsm-point/Rouillacais_points.dbf)
- [Simulation of distance sampling surveys](DSsim-truncation/DSsim-examples.html): Simulate distance sampling surveys examining the effect of truncation distance and pooling robustness upon estimates of animal density (when true density is known). [Rmarkdown file](DSsim-truncation/DSsim-examples.Rmd)
-->
