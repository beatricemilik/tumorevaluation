# Statistical methods for tumor evaluation
This repository contains the code that I wrote for my Bachelor's Thesis. The aim of the study that I conducted was to develop a classification algorithm for MRI images of several types of brain tumors based on statisical methods (the Smirnov and the Kolmogorov-Smirnov tests).

The database that was used in this study contains 3064 T1-weighted magnetic resonance images from 233 patients with three types of brain tumors: meningioma (708 sections), glioma (1426 sections) and pituary tumors (930 sections). The image resolution is 512x512 pixels and the pixel values are stored in uint16.

The data set is stored in .mat format and each file contains a structure (struct) for each image with the following fields:
- cjdata.label (1 for meningioma, 2 for glioma and 3 for pituary tumors);


