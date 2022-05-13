# Chapter-3_Figure3.29

This directory contains:

A metadata file: Fig3-29_md

(Data files available on ESGF-LLNL node as of 02 February 2021 were used in creating this figure.)


SUBDIRECTORIES:
I ./OBS/

The Observed data is from the Assessed thermosteric sea level change data (from Chapter 2) - a csv file:
AR6_FGD_AssessmentTimeseriesThSL.csv

The data in the csv file was written into netcdf format:
ThSL_Observed_AR6_FGD_Assessment_Timeseries.nc


II ./SCRIPTS/

The following 4 .py files that were created to process and plot the zostoga variable files
for the CMIP6 historical experiment and DAMIP experiments.


CodeStep1_GatherData.py
CodeStep2_Create_zostoga_AnnualMeans.py
CodeStep3_createFinalPlotDict.py
CodeStep4_plotFinal_1panel_mpl.py


Also in the directory are the following codes:

1. zostogaAvailableDataDict.py (This is a dictionary of all the zostoga data files available on the LLNL node on 02-02-2021)
2. zostogaProcessedPlotDataDict.py (The final plot is created using the annual means available in this dictionary)
3. PercentileFunctions.py (called by CodeStep4_plotFinal_1panel_mpl.py)
4. createObsncfile.py (used to convert observed ThSL in csv format to netcdf format)

