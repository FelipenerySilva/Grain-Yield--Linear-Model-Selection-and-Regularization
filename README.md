# Linear Model Selection and Regularization: Grain Yield Project
 
This project is part of the Predictive Analytics course from the University of Newcastle (Uon). 
 
The data set Yield.dat contains the yield of grain together with soil quality measurements
at each of 215 sites in a portion of a field. Figure 1 shows the location of the measurement
sites. The measurement sites are identified in the data set by a variable, x, indicating the
measurement location along a particular east-west transect1. Each measurement location is 
approximately 12.2m apart. The 8 transects, identified by a variable, y, are approximately
48.8m apart. At harvest time, the harvesting machine was driven along each transect stopping
each 12.2m to measure the yield of grain for that part of the field in bushels/acre. Measurements
of 10 soil nutrients in parts per million (ppm) are made at each location: Boron (B), Calcium
(Ca), Copper (Cu), Iron (Fe), Potassium (K), Magnesium (Mg), Manganese (Mn), Sodium
(Na), Phosphorus (P), and Zinc (Zn). As can be seen in Figure 1, there were a number of
points in the site location grid where data was not available.

We are interested in determining which soil nutrients are most important in determining grain
yield.

Applied methods:
    ## Multiple Linear Regression;
    ### Outlier investigation;
    ### Model transformation;
    ### Subset Selection (Forward stepwise selection); 
    
    ## Model Regularisation;
    ### Lasso (using library(glmnet);
    ### Cross-Validation ;
