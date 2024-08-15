# Computational Neuroscience Toolbox using Nilearn

Welcome to the Computational Neuroscience Toolbox repository! This toolbox leverages the Python library Nilearn to facilitate machine learning analyses with neuroimaging data, particularly focusing on functional magnetic resonance imaging (fMRI). Nilearn, an extension of scikit-learn, is specifically designed to handle NeuroImaging (NI) data.

## Overview

This repository contains templates and tutorials for building classifiers and regressors using functional connectivity data derived from fMRI scans. The templates provided are:

- **Classifier Functional Connectivity Template**: Template for building classifiers to predict labels from functional connectivity matrices.
- **Regressor Functional Connectivity Template**: Template for building regressors to predict continuous variables from functional connectivity matrices.

## Introduction to Functional MRI (fMRI)

Functional MRI is a neuroimaging technique that measures brain activity by detecting changes associated with blood flow. fMRI data consists of 4D volumes (x, y, z, t), where each voxel in the brain generates a time series reflecting changes in neuronal activity over time through the BOLD signal.

## Features

- **Data Representation**: Utilizes Nilearn's Masker objects to extract and transform fMRI data into structured formats suitable for machine learning.
- **Functional Parcellation**: Includes methods to define regions of interest (ROIs) using clustering algorithms (e.g., k-means) or pre-defined atlases (e.g., MSDL atlas).
- **Functional Connectivity**: Calculates pairwise correlations between ROIs to create functional connectivity matrices, a common method for studying brain networks.

## Usage

1. **Setup**: Ensure Python and necessary dependencies (Nilearn, scikit-learn) are installed.
   
2. **Data Preparation**: Obtain fMRI datasets in Nifti format. Prepare metadata and functional masks if needed.

3. **Template Usage**: 
   - Choose either the Classifier or Regressor template based on your analysis needs.
   - Customize the template by specifying your data paths, features of interest, and desired machine learning models.

4. **Run**: Execute the template script and observe outputs such as model performance metrics, connectivity matrices, and predictions.

## Getting Started

To get started with using this toolbox, refer to the detailed tutorials and example scripts provided in each template directory (`classifier_template` and `regressor_template`). 

## Resources

- [Nilearn Documentation](https://nilearn.github.io/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [fMRI Data Basics](https://en.wikipedia.org/wiki/Functional_magnetic_resonance_imaging)


## Acknowledgments

Special thanks to the Nilearn and scikit-learn communities for their contributions to open-source neuroscience tools.

![Uploading image.png…]()


