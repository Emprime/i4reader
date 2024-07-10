# i4reader

Collective Repository for the I4Reader of the ARTMIS project

## Data-Processing and Data-Labeling

The [SOF-Utils repository](https://github.com/ithron/SOF-Utils) provides command-line tools for working with the SOF dataset, including extracting metadata from DICOM files, identifying corrupted DICOM files, exporting images, converting labels, converting datasets, detecting keypoints on hip radiographs, and identifying keypoint outliers. Each tool offers various options for customization and output formatting, aiming to streamline the preprocessing and analysis of medical imaging data.


## Data-Labeling

[This repository](https://github.com/Emprime/dcic) hosts the Data-Centric Image Classification (DCIC) Benchmark, designed to evaluate the impact of dataset tuning over model tuning across various image classification tasks.
It includes tools and addons like DC3, SPA, CleverLabel, and an annotation strategy for enhancing dataset quality.
The benchmark provides a structured pipeline for dataset preparation, annotation, and evaluation, supported by detailed hands-on tutorials and robust Docker-based installation and execution scripts.


## i4SQ

The i4SQ is a tool to automatically analyze CT images (dicom or nifti format) for vertebral fractures.
It will be made publicly available soon as a streamlit demo.
