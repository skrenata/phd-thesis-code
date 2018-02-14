# phd-thesis-code

Archive of R scripts and functions used for data analysis in my PhD thesis, "Dynamics, control and variability of plankton in the Northeast Atlantic and North Sea between 1958-2014". This work was developed at the University of Southampton - UK; with funding by CAPES - Brazil. 

This repository is intended as an archive only, and unlikely to change once I finish to upload all of its contents.

Contents:

1. informational_change_point
Check for a single change-point in a time-series, comparing between different possible models (noise, linear trend, change-point in the mean, change-point in the linear trend). 
There is a new R package from 2016 which is more efficient, refer to: https://github.com/rkillick/changepoint

2. var_analysis
Uses functions from package "vars" (http://www.pfaffikus.de/vars.html) to fit a VAR model with seasonality and exogenous covariates to a set of time-series.

3. nonlinear_analysis
Apply nearest neighbours forecasts of time-series in order to investigate the presence of deterministic chaos in the data (based on ideas from https://www.nature.com/articles/344734a0 and https://academic.oup.com/plankt/article/15/6/603/1522137)
Uses functions from package "rEDM" (https://cran.r-project.org/web/packages/rEDM/vignettes/rEDM-tutorial.html) to investigate the presence of nonlinearity in time-series.

4. cpr_setup
Format data from the CPR survey (https://www.sahfos.ac.uk/) into monthly averaged time-series.

The scripts are currently being formatted and commented, in order to make them more readily usable. This repository will be updated as this progresses, and this paragraph will be removed once all files have been uploaded.
