# flux2nc
Convert VIC fluxes files to netCDF format

Program to convert VIC 4.x model output to netCDF file.

[VIC][1] is a macroscale hydrologic model developed by Xu Liang at the University of Washington. For a better description of the model itself, please, visit the model home page.

This repository hosts a conversion program, written in 2004, and applicable for an older version of the model (4.x). I'm creating this repository just in case someone is still using the old model.

Version 4.x of the model output consists of several ASCII files (flux files) with precipitation, evapotranspiration, runoff and other variables, for each cell. Back in Dec-2004 I wrote this program to convert all fluxes files into a netCDF file, that could be opened in [GrADS][2] or other netCDF viewer.

When I wrote this, I used the (_now defunct_) libraries Numeric and Scientific. I've now replaced those libraries.

Since I'm not running VIC anymore, tests and code debugging was done by Stuart Smith (smit1770 at purdue dot edu).
Also, it appears that some VIC outputs now include header lines in the flux file.

_Beware_: This is old code, written by an inexperienced programmer...



[1]: http://vic.readthedocs.io/en/master/
[2]: http://cola.gmu.edu/grads/
