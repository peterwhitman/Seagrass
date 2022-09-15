# Seagrass

This repository contains a library of functions that can be used to process WorldView-2 and -3 satellite imagery. The library is intended to be used for mapping submerged aquatic vegitation with WorldView imagery, but it could be easily adapted for other applications and other sensors. There are functions for radiometric calibration, atmospheric correction, clipping, masking, and mosaicing the imagery. There are also functions to define and train a deep convolutional neural network (dcnn) and use it to classify an image. The metadata document provides a description and outline of the input arguments, output values, and ancillary details for each function. The two python scripts, 1_Image_Processing.py and 2_Image_Classification.py, are examples that illustrate the way in which the library of functions can be used to process and classify a WorldView image.
