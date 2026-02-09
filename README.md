# twophaseABtest
R code and data used for "A Two-Phase AB Test for Binary Outcomes on Network Data."

This contains all of the R code needed to reproduce the tables, simulations,
and figures in the paper titled "A Two-Phase A/B Test for Binary Outcomes on Network Data."

To run "caltechpowercurves.R" or "get_power_tables.R" you will need to change your working directory
to the location of "SimResults." For all other R files, make sure the working directory contains the
"two_phase_ABtest_source.R" file.

- SimResults Folder: Contains csv files that store simulation results in Section 4 of the paper.
- Caltech36.mat: Data on covariates used for Section 4.2.
- caltech36.R: Runs the data generation and analysis procedures used in Section 4.2.
- caltech36.txt: Contains data on the network structure used in Section 4.2.
- caltechpowercurves.R: Running this produces Figure 1 in Section 4.2.
- clusterABtestsim.R: Simulation code used for Section 4.1.
- get_power_tables.R: Used to produce Table 1 (tau = 2) and Table 2 (tau = 0) in Section 4.1.
- two_phase_ABtest_source.R: This R code contains functions used throughout the other R files.
