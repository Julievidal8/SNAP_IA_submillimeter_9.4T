# SNAP_IA_submillimeter_9.4T
Interthalamic adhesion's mask on the UltraCortex repository

All associated T1w MRIs are publicly available: [https://openneuro.org/datasets/>](https://openneuro.org/datasets/ds005216/versions/1.1.0)
Those analyses follow a protocol named SNAP, which is in preparation.

The IA_masks_UltraCortex.zip file contains all the IA's masks by subject. Those masks are the overlap of two raters' segmentation when the Dice coefficient was superior to 0.80, demonstrating high agreement.

UltraCortex_analysis_github.ods is the file with the IA's characterization, including its presence or absence, anatomical variant, and area corrected by the partial volume effect (PVE). PVE are obtained using FSL FAST segmentation outputs overlapped with the IA's mask to estimate the partial volume effect (i.e mean rate of CSV by masks).

Up to two masks by IA were segmented and averaged to extract the mean area corrected for the PVE. 

