# Viskari_etal_ED2_radiation_uncertainty
The influence of canopy radiation parameter uncertainty on model projections of terrestrial carbon and energy cycling



This archive contains the model simulation results and analyses that form the basis of the manuscript results. The compressed file named RTM_SinglePFTCanopy_Sensitivity_Results contains the folders for the single PFT canopy runs, RTM_EMLCanopy_Sensitivity_Results for the mixed EML canopy, RTM_MLECanopy_Sensitivity_Results for the MLE canopy and RTM_InventoriedCanopy_Sensitivity_Results for the Inventory canopy.

The simulation outputs are stored in folders corresponding with the initial canopy used for the simulation. 

The subfolder named 'out' contains all the simulated outputs for the different parameter values, with the each varied parameter ouput in a subsequent subfolder named after the parameter and how much the value has been deviated. The outputs used for the analysis and figures are contained the -T- HDF5 files. The file format is similar to NetCDF and can be opened with similar tools. As it is a hierarchial filing system, the different outputs are clearly organized within the file.

The subfolder pft contains the sensitivity analysis for each simulation divided in to folders based on the PFT.

The subfolder run contains the setup for each ED2 run to ease replication.

The folder root contains the R output files from which the figures in the article were drawn from.
