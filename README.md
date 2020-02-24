# Class: CIS-544 DATA MINING & MACHINE LRNG
## Image classification
### last modified date 02/23/20

This project was about image classification, with a data set of over 16 GB of labeled images. Four seperate classifiers should be build:

Naïve Bayes
Random Forest
Deep Learning
Support Vector Machines

The models must take in images and their labels, then classify each image. All data and code must be on the cloud (EC2), model written only in R. The reporting should include hypothesis testing, Accuracy, Recall, Precision, Overfitting (AuC).

## Getting Started / About this repository

In order to understand the structure of this repository, please read following instructions:

### 00_Archiv

In this folder there are old scripts, which are not used anymore.

### 01_Data

In this folder the data is hosted. First, we took a subset of the data. The complete data is available at https://storage.googleapis.com/openimages/web/download.html

The complete dataset is split into 16 smaller files, so that the data in this folder represents the segmentations of folder "0".

### 02_Code

In this folder you find the code for the four models, including transforming the data into train and test.

### 03_Presentation

In this folder you find the final presentation for presenting the results of this project.

## Prerequisites

Install in R following packages / libraries:
 - tidyverse
 - lubridate
 - rockchalk
 - e1071
 - ROCR
 - caTools
 - party
 - knitr
 - rmarkdown
 - RMySQL
 - DBI
 - dplyr
 - readr
 - randomForest
 - neuralnet
 - kernlab
BiocManager::install(pkgs = "EBImage")
library(EBImage)

## Built With

R (https://www.r-project.org)
RStudio as an environment (https://rstudio.com)

## Authors

Max Franke & 
Damian Etchevest

## License

This project was a part of the class CIS-544 DATA MINING & MACHINE LRNG at St Thomas University

## Acknowledgments

None

