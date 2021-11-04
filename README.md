# OptimalEstimators
''''
Optimal Estimator Project 1 - Fitting line/curve/surface by using Least Squares
by Nikeet Pandit
******************** ALL UTILITIES ARE GIVEN SUMMARIES DESCRIBING FUNCTIONALITY ******************** 
This module comprises of a series of executables that allows you to fit a geometry to a dataset using LS and WLS
(1) line, curve (polynomial-quadractic), surface (plane), and sinusoid (or ellipse in 3D)
(2) user must select this my setting OptionToSet variable which is -> Linear, Polynomial, Ellipse
(3) all descriptions of routines are provided so that can easily be manipulated 
(4) functions will work (may require some manipulation) for any dataset, but it is optimized to work with GRACE-FO Ephemeris files
(5) module calls LSSA to estimate fundamental frequency of sine waves written by Professor Ebrahim Ghaderpour
(6) module calls DataFormCallFunctions and DataFormat2 which read in the GRACE-FO data files provided by JPL which I have previously written
(7) the plane fitting option is not included as an OptionToSet because it is not necessary for this project, but can easily be if needed
(7) for a further application. It was added to show that it could easily be done for my own learning. 
(8) user must specifiy the DataProd using the DataFormatCallFunctions, the ID (GRACE-FO identifier), the Hours of the dataset to fit
(8) and the weighted scheme which is a [1,2] list. The first element denotes if weighted is used (1) or not (0). The second element 
(9) denotes the type of weighting scheme to be used. For example to not weight you would specify P as P = [0,0]. To weight
(9) and specify weighting scheme 3... you would specify P as P = [1,3]. More info is given in SUMMARY OF
