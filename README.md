# Semiparametric-Regression-Cure-Model-for-Interval-Censored-Data
C code for "A Semiparametric Regression Cure Model for Interval-Censored Data" by Liu and Shen, Journal of the American Statistical Association, 2009 Dec 1; 104(487): 1168–1178.

http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2846840/


The programs for the paper were written in C language. These files were complied successfully under a Mac OS with the use of open source GSL library. All relevant subroutines are inlcuded in one file (data_ana.c).  It requires an external minimizer/maximizer subroutine. The mybfgs.c contains the conjugate gradient algorithm, tranlated from Fortran code for the subroutine CONMIN, downloaded from netlib.  In addition, the main function needs the random variable generator subroutinesfrom the open source GSL library. The C codes can be easily translated into R.
