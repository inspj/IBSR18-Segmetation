Image segmentation presents essential part of computer vision and as a result of a segmentation an image is partitioned in distinctive parts which enable localization of specific objects. Furthermore, each part is labeled with a specific value which is unambiguous among parts.

Segmentation of the MRI data into specific tissue types and identification  of specific anatomical structures is a useful diagnostic tool. It enables visualizing anatomical features, assessing brain changes, defining diseased regions etc. [1]

At its most fundamental level, the anatomy of the brain is divided into three separate classes: white matter (WM), gray matter (GM), and cerebrospinal fluid (CSF). The IBSR18 dataset was used to segment the three classes indicated above. The criteria for evaluation were Dice score (DSC), Hausdorff distance (HD) and average volumetric difference (AVD).

In this project as part of MAIA coursework in Medical Image Segmentation IBSR18 dataset was used. The dataset was set up so that 10 images were used for training, 5 images for validation, and 3 images were used for testing. The images used for training and validation included their respective ground truth data for labels, but no ground truth data for test data was provided. The voxel spacing varied between cases. Size of the volume equaled between cases and is 256 x 128 x 256.

![alt-text-1](https://raw.githubusercontent.com/inspj/IBSR18-Segmetation/main/Images/Base_Images.png "Intensity Images") ![alt-text-2](https://github.com/inspj/IBSR18-Segmetation/blob/main/Images/Base_Labels.png?raw=true "Label Images")
