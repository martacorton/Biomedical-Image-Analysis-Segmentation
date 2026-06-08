# Biomedical-Image-Analysis-Segmentation
This repository contains a collection of Python-based computer vision workflows focused on biomedical image analysis. The primary objective of this project is to develop automated, robust pipelines for medical image segmentation and classification, minimizing manual intervention and enhancing diagnostic workflows.

Currently, the repository features three main applications in clinical and experimental biology:
1.  **Nematode/Worm Segmentation:** Automated detection and morphological analysis of worms in microscopy images for high-throughput phenotyping.
2.  **Lung Contour Segmentation:** Automated identification and isolation of lung boundaries from medical imaging (e.g., X-rays/CT scans).

## Tech Stack & Tools
*   **Language:** Python 3.x
*   **Image Processing & Computer Vision:** OpenCV (`cv2`), `scikit-image`
*   **Data Manipulation:** `numpy`, `pandas`
*   **Data Visualization:** `matplotlib`, `seaborn`

## Project Structure
├── data/                   # Sample images or instructions to download the datasets
├── notebooks/              # Jupyter notebooks containing exploratory data analysis (EDA)
├── src/
│   ├── lung_segmentation/  # Scripts for lung contour extraction
│   ├── worm_segmentation/  # Scripts for nematode tracking and morphological analysis
│   └── utils.py            # Helper functions for image loading and plotting

## Key Features & Methodology
1. Nematode/Worm Segmentation
Methodology: Deployed OpenCV and scikit-image pipelines to perform background subtraction, thresholding, and contour extraction on microscopy datasets.

Feature Extraction: Calculated key morphological and phenotypic metrics such as length, thickness, and body curvature.

2. Lung Contour Extraction
Methodology: Utilized morphological operations, thresholding techniques, and contour detection to isolate the lung area from the background and surrounding tissues.

Challenge Solved: Overcame issues with varying lighting conditions and artifacts in the original clinical scans.

## Results & Visualizations

Worms: Successfully extracted worm contours and medial axes for high-throughput tracking.

Lungs: Generated accurate masks separating lung tissue from bone and background.


## Academic Context
This repository highlights applied projects and pipelines developed during the Master's program in Bioinformatics for Health Sciences at the University of A Coruña (UDC). The workflows represent hands-on experience bridging computer vision and clinical/experimental biology.

## Contact
[Marta López-Cortón Vázquez]

Bioinformatics & Data Analysis

[www.linkedin.com/in/marta-lopez-corton-vazquez-23337737a]
