# Ensemble Hindcast

This project aims to store the source code of the SWAN Model and the scripts in Python, used in the Ensemble Hindcast study of waves for southern Brazil.

SWAN wave model version 41.31 (http://swanmodel.sourceforge.net/).

Python codes were developed to process SWAN model output data for temporal and spatial analysis of waves.

This repository contains 3 data processing scripts (extension .ipynb), which are based on statistical functions previously created in "manuscript_functions_ensemble.py". The scripts must be read in the Jupyter Notebook platform and executed individually, based on the input of data from the simulations made with the SWAN model (matfiles format), regardless of the processing sequence.

For the temporal analyses, the "timeseries_analisys_Hs" and "timeseries_analisys_Tp" files follow, which help in the comparative analysis of the ensemble data obtained by SWAN with the buoys of Itajaí and Rio Grande. To spatially analyze the wave height behavior in 3 extreme events, the "spatial_analisys_ENSMean" script was developed and also attached in this repository. 

When opening each script, all cells are automated in sequence, so that a simple click on "Run" is enough to generate the final product: graphs of time series of significant wave height (from timeseries_analisys_Hs.ipynb), peak period (from timeseries_analisys_Tp.ipynb) and maps with the main extreme events (from spatial_analisys_ENSMean.ipynb) found during the analyzed time.
