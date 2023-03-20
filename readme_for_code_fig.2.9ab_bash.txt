##########################################################################
# ---------------------------------------------------------------------------------------------------------------------
# This is bash code to produce IPCC AR6 WGI Figure 2.9a,b*
# Creator: Johannes Quaas, Leipzig University
# Contact: johannes.quaas@uni-leipzig.de
# Last updated on: 24 November 2021
# --------------------------------------------------------------------------------------------------------------------
#
# - Code functionality: Convert original csv data to Netcdf
# - Input data: from IPCC archive: fig_2.9a_ice-core_data_sulfate.csv and fig_2.9b_ice-core_data_bc.csv
# - Output variables: same data, just in NetCDF format
#
# ----------------------------------------------------------------------------------------------------
# Information on  the software used
# - Software Version: n/a
# - Landing page to access the software: n/a
# - Operating System: Linux (any)
# - Environment required to compile and run: sed, awk, ncgen
#  ----------------------------------------------------------------------------------------------------
#
#  License: Default license: Apache 2.0
#
# ----------------------------------------------------------------------------------------------------
# How to cite: 
Gulev, S.K., P.W. Thorne, J. Ahn, F.J. Dentener, C.M. Domingues, S. Gerland, D. Gong, D.S. Kaufman, H.C. Nnamchi, J. Quaas, J.A. Rivera, S. Sathyendranath, S.L. Smith, B. Trewin, K. von Schuckmann, and R.S. Vose, 2021: Changing State of the Climate System. In Climate Change 2021: The Physical Science Basis. Contribution of Working Group I to the Sixth Assessment Report of the Intergovernmental Panel on Climate Change[Masson-Delmotte, V., P. Zhai, A. Pirani, S.L. Connors, C. Péan, S. Berger, N. Caud, Y. Chen, L. Goldfarb, M.I. Gomis, M. Huang, K. Leitzell, E. Lonnoy, J.B.R. Matthews, T.K. Maycock, T. Waterfield, O. Yelekçi, R. Yu, and B. Zhou (eds.)]. Cambridge University Press, Cambridge, United Kingdom and New York, NY, USA, pp. 287–422, doi:10.1017/9781009157896.004.

# When citing this code, please include both the code citation and the following citation for the related report component:
https://doi.org/10.5281/zenodo.6353829
########################################################################














Am keeping this for reference:
# ----------------------------------------------------------------------------------------------
# Acknowledgement: The template for this file was created by Lina E. Sitz (https://orcid.org/0000-0002-6333-4986), Paula A. Martinez (https://orcid.org/0000-0002-8990-1985), and J. B. Robin Matthews (https://orcid.org//0000-0002-6016-7596)
