# Mineral Mapping on Hyperspectral Imagery using Machine Learning

Mineral mapping on hyperspectral imagery usually done by classifying pixels with similar reflectance characteristics into groups. In this repository, all the images from hyperspectral sensor have been pre-processed from the digital number to reflectance value.
Each mineral has unique reflectance spectrum, the conventional method is to map the absorption features which indicate the footprint of the mineral. The band position, depth and shape of the absorption features related to the physical and chemical component of each mineral in respect to the ability of reflecting, absorbing and transmitting the light.
As mentioned above, the reflectance spectrum was used in this project and specificly within the shortwave infrared (SWIR) wavelength (1043 – 2486 nm).

Example of reflectance spectrum of several clay minerals from John Hopkins University library:
![alt text](https://github.com/panjoel4/MineralMapping/blob/main/Data/spectrum.png?raw=true)

In this repository I would like to share my attempt on classifying the groups of mineral using several supervised and unsupervised machine learning methods.
The [unsupervised mineral mapping method](https://github.com/panjoel4/ML-MineralMapping-Hyperspectral/blob/main/ipynb/Unsupervised%20Mapping.ipynb) used are K-means and PCA to cluster the pixels and identify them by comparing the existing spectral library from John Hopkins University. While the supervised mineral mapping (coming soon) method will compare between gradient boosting (CatBoost), Random Forest and Convolutional Neural Network using the mineral mapping result from the thesis of my colleague as the validation and training dataset.

Pictures below are the RGB picture of the rock samples and the mineral map used as reference in this repository:
![alt text](https://github.com/panjoel4/MineralMapping/blob/main/Data/Sample%20Files.png?raw=true)

These mineral maps taken from the MSc Thesis of Mr. Rifat Noor and can be downloaded [here](http://essay.utwente.nl/83451/).


I am currently working on taking this idea into an article and use a bigger dataset (Drill Core Scan Data from Geological Survey of Sweden).
