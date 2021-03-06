# UPDATE

Due to a change in circumstances, I'm unlikely to be able to upload these any time soon. If by any reason you would like access to this code, please contact me to request the "raw" uncommented version of the scripts.

# phd-thesis-code

`The scripts are currently being formatted and commented, in order to make them more readily usable. This repository will be updated as this progresses, and this sentence will be removed once all files have been uploaded.`

Archive of R scripts and functions used for data analysis in my PhD thesis, "Dynamics, control and variability of plankton in the Northeast Atlantic and North Sea between 1958-2014". This work was developed at the University of Southampton (UK) with funding by CAPES (Brazil). 

This repository is intended as an archive only, and unlikely to change once I finish to upload all of its contents.

Contents:

1. informational_change_point  
Check for a single change-point in a time-series, comparing between different possible models (noise, linear trend, change-point in the mean, change-point in the linear trend).  
R package ["changepoint"](https://github.com/rkillick/changepoint) was released in 2016, which is more efficient.

2. var_analysis  
Uses functions from R package ["vars"](http://www.pfaffikus.de/vars.html) to fit a VAR model with seasonality and exogenous covariates to a set of time-series.

3. nonlinear_analysis  
Apply nearest neighbours forecasts of time-series in order to investigate the presence of deterministic chaos in the data (based on ideas from [Sugihara and May, 1990](https://www.nature.com/articles/344734a0) and [Ascioti et al., 1993](https://academic.oup.com/plankt/article/15/6/603/1522137).  
Uses functions from R package ["rEDM"](https://cran.r-project.org/web/packages/rEDM/vignettes/rEDM-tutorial.html) to investigate the presence of nonlinearity in time-series.

4. cpr_setup  
Format data from the [CPR survey](https://www.sahfos.ac.uk/) into monthly averaged time-series.
