# GC_DG_mems
contains likely members in all globular cluster and dwarf galaxies

Author: Ting Li, Jordan Bruce, Yingyi Song

email: ting.li@astro.utoronto.ca

Globular Cluster (GC) membership probability are taken from Vasiliev&Baumgardt(2021) using the following code:
https://github.com/GalacticDynamics-Oxford/GaiaTools

For each GC, distance is taken from aumgardt&Vasiliev(2021), line-of-sight velocities taken
from Baumgardt et al.(2019, MNRAS, 482, 5138), and proper motions (PM) computed using Gaia EDR3 by Vasiliev&Baumgardt(2021).

Several metallicity and age resourses are used here, mainly:

metallicity_K19, age_K19 from Kruijssen 2019 (average of 3 resource) 

metallicity_V20, age_V20 from Valcin et al. 2020 (derived from HST photometry)

metallicity_B19 from Bailin 2019 (combined of several spectroscopic metallicity resource)

metallicity_H10 from Harris 2010 (a compilation of different resource)

Contains two files for different probability threshold.
P03: probablilty > 0.3 (larger sample, completeness)
P09: probability > 0.9 (higher completeness, purity)

------------

Dwarf Galaxy (DG) membership probably are taken from Pace, Erkal & Li (2022) using the files from the following link:
https://zenodo.org/record/7158669#.Y8bHkuzMI_Y

For each GC, distance, proper motion, line-of-signt velocities, metallicities are all taken from Pace, Erkal & Li (2022) (summary table also in the zenodo link above).

Pace, Erkal & Li (2022) provides several membership probability. Here we used mem_fixed and mem_fixed_complete

P03: mem_fixed > 0.3 or mem_fixed_complete > 0.3
P09: mem_fixed > 0.9 or mem_fixed_combplete > 0.9

------------
This contains a total of 170 GC and 51 DG.



