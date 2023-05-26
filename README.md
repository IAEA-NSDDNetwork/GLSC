# GLSC

GLSC (Gamma to Level Scheme Computation) is a Java code for fitting gammas to obtain level energies and calculating level feedings, and also calculating absolute gamma emission probabilities from decay. It is an alternative to the GTOL and GABS Fortran code combined, with lots of improvements and new interactive features and options for user to control the fitting parameters. GLSC is part of the [ENSDF Analysis and Utility Programs](https://nds.iaea.org/public/ensdf_pgm/).

Please address any feedback to Jun Chen chenj@frib.msu.edu

## Change history

#### 2023-05
Added an option for calculating E(gamma) without uncertainties from level-energy differences and writing calculated E(gamma) to a new output dataset. To get this option, load an ENSDF file and right click on "Run" button. 

#### 2023-03
Bug fix.

#### 2023-02
Bug fix.

#### 2022-11
Add function to calculate absolute instensity balances (level feedings) directly in the normalization process, more accuate than calculations using the input NR factor and also solving the uncertainty overcounting issue where gamma intensities are used in normalization for obtaining NR.

#### 2022-10
Bug fix.

#### 2022-07
Regular update with minor bug fixes. 

#### 2020-04
Beta version.

## Disclaimer

Neither the author nor anybody else makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness or usefulness of any information disclosed, or represents that its use would not infringe privately owned rights.

