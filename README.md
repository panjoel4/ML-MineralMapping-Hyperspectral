# Mineral Mapping on Hyperspectral Imagery using Machine Learning

Mineral mapping on hyperspectral imagery usually done by classifying pixels with similar reflectance characteristics into groups. In this repository, all the images from hyperspectral sensor have been pre-processed from the digital number to reflectance value.
Each mineral has unique reflectance spectrum, the conventional method is to map the absorption features which indicate the footprint of the mineral. The band position, depth and shape of the absorption features related to the physical and chemical component of each mineral in respect to the ability of reflecting, absorbing and transmitting the light.
As mentioned above, the reflectance spectrum was used in this project and specificly within the infrared wavelength (1043 – 2486 nm).


In this repository I would like to share my attempt on classifying the groups of mineral using several supervised and unsupervised machine learning methods.
The unsupervised method will be K-means and PCA to cluster the pixels and identify them by comparing the existing spectral library from John Hopkins University and the supervised (coming soon) method will compare between gradient boosting (CatBoost), Random Forest and Convolutional Neural Network using the mineral mapping result from the thesis of my colleague as the validation and training dataset.
