##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is NCL and Bash code to produce IPCC AR6 WGI Figure 2.9a,b*
# Creator: Johannes Quaas, Leipzig University
# Contact: johannes.quaas@uni-leipzig.de
# Last updated on: 24 November 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: Plot the ice core data - Convert original csv data to Netcdf
# - Input data: Ice core data converted using tx2nc.ksh - from IPCC archive: fig_2.9a_ice-core_data_sulfate.csv and fig_2.9b_ice-core_data_bc.csv
# - Output variables: Fig 2.9a,b - same data, just in NetCDF format
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version:  NCAR Command Language Version 6.4.0
# - Landing page to access the software: https://www.ncl.ucar.edu
# - Operating System: Linux - Linux(any)
# - Environment required to compile and run: n/a - sed, awk, ncgen
#  ----------------------------------------------------------------------------------------------------
#
#  License: Default license: Creative Commons Attribution 4.0 International License (http://creativecommons.org/licenses/by/4.0/)]*
#
# ----------------------------------------------------------------------------------------------------
# How to cite: https://doi.org/10.5281/zenodo.6353829
# When citing this code, please include both the code citation and the following citation for the related report component:
########################################################################














Am keeping this for reference:
# ----------------------------------------------------------------------------------------------
# Acknowledgement: The template for this file was created by Lina E. Sitz (https://orcid.org/0000-0002-6333-4986), Paula A. Martinez (https://orcid.org/0000-0002-8990-1985), and J. B. Robin Matthews (https://orcid.org//0000-0002-6016-7596)
