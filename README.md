# CM1_ensembles
CM1 directories and python analysis software for analyzing ensemble simulations that use the VORTEX2 tornadic and nontornadic composite environments. 

The analysis code can be used for any CM1 simulations regardless of input soundings. 

Python scripts are meant to be used in a jupyter notebook and are not optimized to run in a terminal window. Most filenames and directories within the code are hardcoded and will need to be adjusted to reflect your own file locations.

For those new to CM1, the namelist files will need to be changed to namelist.input once they are placed in their resolution respective directories. 

The init3d.F file was copied here to give the user the updraft nudging settings used in our study (Dixon et al. 2026). All other src directory settings are standard for CM1 supercell simulations.
