
This repository contains the analysis scripts for Koch et al. (2019). We compare the HI and CO spectral properties in M33.

HI data products are available [here](https://doi.org/10.11570/18.0003). Use of these data should cite [Koch et al. (2018)](https://ui.adsabs.harvard.edu/#abs/2018MNRAS.479.2505K/abstract).

The CO data is hosted by IRAM [here](http://www.iram-institute.org/EN/content-page-329-7-158-240-329-0.html). The link refers to the papers that should be cited when using these data.

Scripts to reproduce the HI reduction and imaging can be found [here](https://github.com/e-koch/VLA_Lband).

These analyses scripts are setup to run from this directory and rely on paths to the data defined in `paths.py`. The disc parameters (inclination, position angle, etc) are required for some script and are loaded through the `galaxy_params.py` script. The file that is loaded in this script is available from the HI data link above (`DR1/HI/rotation_curve/rad.out.params.csv`).

These scripts rely on two personal python packages that require installing from the source code:

* [galaxies](https://github.com/low-sky/galaxies)
* [CubeAnalysis](https://github.com/e-koch/CubeAnalysis)

