# Chromatin-interaction-from-Hi-C-data
Exploring Chromatin Interaction Between Two Human Cell Types and Different Normalization Techniques for HI-C Data


# Introduction
This study utilized the Hi-C matrix for analyzing the relationship between two different cell types in the human body. For identifying similarities this paper analyzed Pearson's and Spearman's R correlation between genomic loci from HiC matrix data. Additionally, different normalization techniques have been explored to see which normalization methods can perform well in HiC data. 

# Correlational Methods:
The following correlational methods have been employed for similarity measurement:

Pearson's 

Spearman's R

# Normalization Methods:
This study utilized four different normalization approaches for visualizing Hi-C interaction and comparison purpose.

Min-max 

Min Absolute Value Scaling 

Preprocess Normalize

Robust Scaling

# Dataset:
The data folder contains the Hi-C dataset for two human cell types. These datasets are sparse matrices containing a higher amount of zeroes. The dataset does not contain the header. Each column represents a bin.

Human ES Cell

IMR90 Fibroblasts Cell

# Getting Setup with Python
Ensure that you have the below software installed.
Software you require

Jupyter Notebook(Recommended Version 6.3.0)

Anaconda (Recommended Version 4.10.1)

# Dependencies:

The following libraries need to be installed before running the program

pip install matplotlib

pip install pandas

pip install numpy

pip install seaborn

pip install scikit-learn

pip install xarray

pip install plotly

# Files:
This folder contains two python scripts for this study.
