# HaloFinder
Spherical overdensity halo finder

compile by typing g++ HaloFinder2019.c -fopenmp

# You need to install
openmp

# INPUTS
dark matter catalog

ASCII format with 39 coumns: x, y, z in Mpc/h



# OUTPUTS
dark matter haloes catalog

ASCII format with 39 (3+4*9) coulmns:

x, y, z

mass, mass_error, rad, rad_error (4 columns) for Delta_200,300,400,600,800,1200,1800,2400,3200 (9 Delta casses) [Delta related to the matter density]

where positions anr radous are in Mpc/h, and masses are in 10^10 M\sun units
 
