---
title: Distance Sampling Examples
layout: indexnew

---

# Distance Sampling Examples

Here you can find a set of worked examples ("vignettes") demonstrating various aspects of distance sampling design and analysis using free software tools we have created and maintain. At present they focus on R packages; for examples using Distance for Windows see Chapter 3 ("Getting started") of the Distance manual.

Examples below are based upon data sets available in the R packages `dssd` (for survey design), `Distance` (for analysis of distance sampling surveys), `mrds` for double observer methods and `dsm` for spatial models.  Data for the example of spatial models for point transect are described below the table; data for model-based inference is linked to the HTML description.   All examples are provided as Rmarkdown documents.  For information about using Rmarkdown files, consult [this RStudio website](https://rmarkdown.rstudio.com/).

# Examples with R packages

<form>
  <input type="search" id="table-filter" data-table="order-table" placeholder="Search">
  <input type="radio" id="all" name="filter" value="all" checked>
  <label for="all">All</label>
  <input type="radio" id="buckland" name="filter" value="buckland">
  <label for="buckland">Buckland et al (2015) examples</label>
</form> 

{:.order-table}
| Vignette | Description | Keywords | Category | Buckland2015 |
|----------|-------------|----------|----------|--------------|
| [Getting started with survey design using `dssd`](dssd-getting-started/GettingStarted-distill.html) ([Rmd](dssd-getting-started/GettingStarted-distill.Rmd))|  Use of the package `dssd` to create a survey design within a study-area, and examine properties of the design such as how well it covers the study area and  average transect lengths.  The example uses a parallel line transects; other designs available in the `dssd` package follow from this example. | line transect, design, `dssd`, parallel | Design |
| [Multiple strata in `dssd`](dssd-multi-strata/MultiStrataVignette-distill.html) ([Rmd](dssd-multi-strata/MultiStrataVignette-distill.Rmd)) | An example of how to create a design in `dssd` that contains multiple strata, with different design characteristics in each stratum. | line transect, design, `dssd`, stratification | Design |
| [Analysis of line transect data](Distance-lines/lines-distill.html) ([Rmd](Distance-lines/lines-distill.Rmd)) | Line transect data of winter wrens in Scotland.  An example of model fitting, model selection, goodness of fit assessment.  Basic analysis skills required for any distance sampling analysis.  | Line transect, songbirds | Analysis | XXXX |
| [Analysis of point transect data](Distance-points/pointtransects-distill.html) ([Rmd](Distance-points/pointtransects-distill.Rmd)) |  Point transect analysis of savannah sparrow data set from Knopf et al. (1988) | point transects, songbirds | Analysis |
| [Variance estimation](Distance-variance/variance-distill.html) ([Rmd](Distance-variance/variance-distill.Rmd)) | Variance estimation examining three approaches: delta-method, bootstrap and bootstrap incorporating model uncertainty.  Based on line transect data of winter wrens from Buckland (2006). | bootstrap, variance | Analysis |
| [Stratification](Distance-strata/strata-distill.html) ([Rmd](Distance-strata/strata-distill.Rmd)) | Analysis of stratified survey design, including model selection to determine whether stratum-specific detection functions are necessary.  Uses point transect analysis of savannah sparrow data set from Knopf et al. (1988). | stratification, point transects | Analysis |
| [Covariates in detection function](Distance-covariates/covariates-distill.html) ([Rmd](Distance-covariates/covariates-distill.Rmd)) | Bringing covariates into detection function, using amakihi data from Marques et al. (2007). | point transects, songbirds, covariates | Analysis | XXXX |
| [Multi-species surveys](Distance-spec-covar/species-covariate-distill.html) ([Rmd](Distance-spec-covar/species-covariate-distill.Rmd)) | Use of species covariate to produce species-specific density estimates when number of detections for some species is small. | multi-species | Analysis |
| [Size bias adjustment](Distance-groupsize/Remedy-size-bias-for-dolphin-surveys.html) ([Rmd](Distance-groupsize/Remedy-size-bias-for-dolphin-surveys.Rmd)) | Because of the detection process, average group size in sample is a positively biased estimate of average group size in population.  This bias can be compensated by employing group size as a covariate in the detection function. | group size | Analysis |
| [Cue counts](Distance-cues/cuecounts-distill.html) ([Rmd](Distance-cues/cuecounts-distill.Rmd)) | Cue counting example based on line transect data of winter wrens from Buckland (2006).  Incorporating song rate in analysis. | Cue counts, line transects | Analysis | XXXX |
| [Indirect survey methods](Distance-mult/multipliers-distill.html) ([Rmd](Distance-mult/multipliers-distill.Rmd)) | Estimation of Sika deer density based upon deer pellet distance sampling data.  Includes estimation of decay rate using logistic regression and multiplier based on dung production rates.  Using data from Marques et al. (2001). | multipliers, line transects | Analysis |
| [Double observer methods](mrds-golftees/mrds-golftees-distill.html) ([Rmd](mrds-golftees/mrds-golftees-distill.Rmd)) | Full independence and point independence analysis of golf tee data from multiple observers. | mark-recapture distance sampling | Analysis |
| [Density surface modelling - lines](dsm-line-dolphins/mexico-analysis.html) ([Rmd](dsm-line-dolphins/mexico-analysis.Rmd)) | Line transect survey of pantropical spotted dolphins in the Gulf of Mexico. | spatial model, dolphins, line transect | Analysis | XXXX |
| [Density surface modelling - points](dsm-point/hare_point_transect_dsm-distill.html) ([Rmd](dsm-point/hare_point_transect_dsm-distill.Rmd)) | Point transect survey of hares in France.  Simple density surface model with (x,y) predictor; thanks to Guillaume Souchay, French National Hunting and Wildlife Agency for data and analysis. | point transect, spatial modelling | Analysis |
| [Simulation truncation decisions](DSsim-truncation/DSsim-examples.html) ([Rmd](DSsim-truncation/DSsim-examples.Rmd)) |  Simulate distance sampling surveys examining the effect of truncation distance and pooling robustness upon estimates of animal density (when true density is known). | simulation, truncation | Simulation |
| [Model-based inference](book-bobwhite/bobwhite.html) ([Rmd](book-bobwhite/bobwhite.Rmd)) | Model-based inference combining detection function and density modelling in a single step. Demonstrates both likelihood-based and Bayesian approaches. | model-based, point transects | Analysis | XXXX |
| [Lure surveys](book-crossbills/book-crossbills.html) ([Rmd](book-crossbills/book-crossbills.Rmd)) | Point counts supplemented by trials to assess birds' response to lures.  Combined analysis adjusts counts to adjust for probability of responding to lure. | survey design, point transects | Analysis | XXXX |
| [Simulation design contrasts](book-DSsim/DSsimstudy.html) ([Rmd](book-DSsim/DSsimstudy.Rmd)) | Simulation package evaluates randomised and non-randomised surveys designs when animals avoid human trails. | design, randomisation | Simulation | XXXX |
| [Density surface modelling data formatting](dsm-data-formatting/dsm-data-formatting.html) ([Rmd](dsm-data-formatting/dsm-data-formatting.Rmd)) | How to format line transect data for the `dsm` package. | spatial model, line transect | Data processing | XXXX |
| [Camera trap analysis with distance sampling](Distance-cameratraps/camera-distill.html) ([Rmd](Distance-cameratraps/camera-distill.Rmd)) | Replicates analyses of duiker data presented by Howe et al. (2017) including model selection methods in presence of overdispersion (Howe et al. 2019) | camera traps, point transects | Analysis | |
| [Inference regarding density estimate differences](differences/differences.html) ([Rmd](differences/differences.Rmd)) | Statistical comparison of density estimates between strata.  Uses formulation provided in Buckland et al. (2001) Sect. 3.6.5 | stratification, inference | Analysis | |


