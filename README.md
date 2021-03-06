# Sandia National Laboratories - Extreme Sea State Contour (SNL-ESSC)

## Abstract
Environmental contours describing extreme sea states are generated as the input for numerical or physical model simulations as a part of the standard current practice for designing marine structures to survive extreme sea states. These environmental contours are characterized by combinations of significant wave height (Hs) and either energy period (Te) or peak period (Tp) values calculated for a given recurrence interval using a set of data based on hindcast simulations or buoy observations over a sufficient period of record. The use of the inverse first-order reliability method (I-FORM) is a standard design practice for generating environmental contours. This paper develops enhanced methodologies for data analysis prior to the application of the I-FORM, including the use of principal component analysis (PCA) to create an uncorrelated representation of the variables under consideration as well as new distribution and parameter fitting techniques. These modifications better represent the measured data and, therefore, should contribute to the development of more realistic representations of environmental contours of extreme sea states for determining design loads for marine structures.

## References
The methodologies implemented in this code are described in the following paper. We ask that you please cite this paper if you use the Extreme Sea State Contour code in your work:

[1] Aubrey C. Eckert-Gallup, Cédric J. Sallaberry, Ann R. Dallman, Vincent S. Neary, "*Application of principal component analysis (PCA) and improved joint probability distributions to the inverse first-order reliability method (I-FORM) for predicting extreme sea states*", Ocean Engineering, Volume 112, 15 January 2016, Pages 307-319, ISSN 0029-8018, http://dx.doi.org/10.1016/j.oceaneng.2015.12.018.

## Note to Users
This code was developed in 2015 using versions of MATLAB and MATLAB toolboxes that were current at the time.  MATLAB versions and functions change over time, and users with newer versions of MATLAB may need to update function names and check for functionality changes for this code to be compatible. 

The code was more recently ported into Python in the WDRT toolbox (http://wec-sim.github.io/WDRT/). The WDRT toolbox includes expanded functionality and should not have the same deprecation issues. 
