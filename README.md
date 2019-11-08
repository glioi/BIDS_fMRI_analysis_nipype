# BIDS_fMRI_analysis_nipype
### Analysis pipeline for fMRI (and structural) images in BIDs format

This repository contains a series of processing pipelines for fMRI (and structural) dataset in BIDs format, in form jupyter notebooks.
The pipelines are implemented in [nipype](https://nipype.readthedocs.io/en/latest/) and are adapted from the [Michael Notter tutorial](https://miykael.github.io/nipype_tutorial/).
I used these scripts to analyze fMRI data colleted during a Motor Imagery Neurofeedback task, however they can be easily extended to other datasets in BIDs format.
To be able to use these notebooks and adapt them to your own analyisis, you need to have installed the dependencies necessary to use Nipype ()

The pipeline is organized in three modules

### 1. fMRI_preprocessing.ipynb
