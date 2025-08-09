This repository contains polarization and molecular line datasets for scientific analysis.
It includes calibrated Stokes I, Q, and U FITS files, as well as JCMT HARP C¹⁸O moment-0, moment-1, and moment-2 FITS maps.
A processed polarization catalog in CSV format is provided with derived quantities for each selected pixel.CSV columns include: RA, DEC, I, DI, Q, DQ, U, DU, P, DP, ANG, DANG, PI, and DPI.
Polarization position angle (ANG) is calculated as 0.5·arctan2(U, Q) in degrees, following the electric vector convention.
Selection criteria applied are: I/DI >= 10, PI/DPI >= 2, and P <= 30 %.
All FITS files preserve original WCS information to allow direct astronomical coordinate mapping.
Moment maps provide integrated intensity, velocity centroid, and velocity dispersion of the C¹⁸O emission.
These data products are intended for studies of magnetic field structure and gas kinematics in the observed region.
