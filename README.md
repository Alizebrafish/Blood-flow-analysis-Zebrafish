# Blood-flow-analysis-Zebrafish
Automated blood flow and blood cells count in zebrafish and medaka 
## Background

Blood-flow measurement is important for studying cardiovascular development, drug effects, toxicology, and disease-related phenotypes in small animal models. Manual analysis can be time-consuming and observer-dependent. This project provides an OpenCV-based workflow to simplify video-based blood-flow analysis and generate quantitative outputs.

## Main Features

- Video-based blood-flow analysis
- Blood-flow velocity measurement
- Blood cell counting
- OpenCV-based image processing
- GUI-supported workflow for non-programming users
- Exportable quantitative results
- Suitable for zebrafish and medaka embryo experiments

## Scientific Applications

This tool can be useful for:

- zebrafish cardiovascular research
- medaka embryo blood-flow analysis
- developmental biology
- ecotoxicology and drug-screening studies
- automated biomedical image analysis
- comparison of cardiovascular phenotypes between treatment groups

## General Workflow

```text
Input video
    ↓
Frame extraction
    ↓
Region of interest selection
    ↓
Image preprocessing
    ↓
Blood-cell movement detection
    ↓
Velocity and cell-count measurement
    ↓
Export results
```

## Input Data

Recommended input:

```text
microscopy video files of fish embryo blood vessels
```

The video should have clear visibility of blood-cell movement and a stable imaging field. Better video quality usually improves measurement reliability.

## Outputs

Typical outputs include:

- blood-flow velocity values
- blood-cell count estimates
- processed frames or analysis visualization
- result tables for downstream statistical analysis

## Citation

If you use this software or workflow, please cite:

**Farhan A, Saputra F, Suryanto ME, Humayun F, Pajimna RM, Vasquez RD, Roldan MJ, Audira G, Lai HT, Lai YH, Hsiao CD. OpenBloodFlow: A User-Friendly OpenCV-Based Software Package for Blood Flow Velocity and Blood Cell Count Measurement for Fish Embryos. Biology. 2022.**

## Author

**Dr. Syed Muhammad Ali Farhan**  
Biomedical Imaging, OpenCV, Artificial Intelligence, and Bioinformatics  
ORCID: https://orcid.org/0000-0003-4735-7069

## Corresponding Laboratory

**Prof. Chung-Der Hsiao Lab**  
Department of Bioscience Technology  
Chung Yuan Christian University, Taiwan


This software is intended for research use. Results should be interpreted with proper experimental controls, video-quality assessment, and biological validation.
