# Identifying and Tracking Solar Magnetic Flux Elements with Deep Learning

Haodi Jiang, Jiasheng Wang, Chang liu, Ju Jing, Hao Liu, Jason T.L. Wang and Haimin Wang

New Jersey Institute of Technology

## Abstract

Deep learning has drawn a lot of interest in recent years due to its effectiveness in processing 
big and complex observational data gathered from diverse instruments. 
Here we propose a new deep learning method, called SolarUnet, 
to identify and track solar magnetic flux elements or features in observed vector
magnetograms based on the Southwest Automatic Magnetic Identification Suite (SWAMIS).
Our method consists of a data pre-processing component that prepares 
training data from the SWAMIS tool, a deep learning model implemented 
as a U-shaped convolutional network for fast and accurate image segmentation, 
and a post-processing component that prepares tracking results. 
SolarUnet is applied to data from the 1.6 meter Goode Solar 
Telescope at the Big Bear Solar Observatory. 
When compared to the widely used SWAMIS tool, 
SolarUnet is faster while agreeing mostly with SWAMIS on feature size and flux distributions, 
and complementing SWAMIS in tracking long-lifetime features. 
Thus, the proposed physics-guided deep learning-based tool 
can be considered as an alternative method for solar magnetic tracking.

----

Requirement: 

Tensorflow-GPU 1.12.0; Keras 2.2.4; astropy 4.0.1; numpy 1.16.1; scipy 1.2.0; sklearn 0.20.3; skimage 0.15.0; matplotlib 3.1.0; cv2 3.4.2
