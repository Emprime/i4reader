# i4reader

Collective Repository for the I4Reader of the ARTEMIS project, financially supported by the Federal Ministry of Education and Research funded by the (grant 01EC1908C).
Not for clinical use.

## Data-Processing and Data-Labeling

The [SOF-Utils repository](https://github.com/ithron/SOF-Utils) provides command-line tools for working with the SOF dataset, including extracting metadata from DICOM files, identifying corrupted DICOM files, exporting images, converting labels, converting datasets, detecting keypoints on hip radiographs, and identifying keypoint outliers. Each tool offers various options for customization and output formatting, aiming to streamline the preprocessing and analysis of medical imaging data.


## Data-Labeling

[This repository](https://github.com/Emprime/dcic) hosts the Data-Centric Image Classification (DCIC) Benchmark, designed to evaluate the impact of dataset tuning over model tuning across various image classification tasks.
It includes tools and addons like DC3, SPA, CleverLabel, and an annotation strategy for enhancing dataset quality.
The benchmark provides a structured pipeline for dataset preparation, annotation, and evaluation, supported by detailed hands-on tutorials and robust Docker-based installation and execution scripts.


## i4SQ

The i4SQ is a tool to automatically analyze CT images (dicom or nifti format) for vertebral fractures.
The i4SQ-Pipeline was published as

[1](https://link.springer.com/chapter/10.1007/978-3-030-87589-3_39) E. B. Yilmaz et al., “Automated Deep Learning-Based Detection of Osteoporotic Fractures in CT Images,” in Machine Learning in Medical Imaging, Cham: Springer International Publishing, 2021, pp. 376–385.

[2](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12465/2653526/Towards-fracture-risk-assessment-by-deep-learning-based-classification-of/10.1117/12.2653526.short) E. B. Yilmaz et al., “Towards fracture risk assessment by deep-learning-based classification of prevalent vertebral fractures,” in Medical Imaging 2023: Computer-Aided Diagnosis, K. M. Iftekharuddin and W. Chen, Eds., in Proc. of SPIE, vol. 12465. San Diego, United States: SPIE, Apr. 2023. doi: 10.1117/12.2653526.

It is available as a Streamlit-based demo upon request from the authors.
