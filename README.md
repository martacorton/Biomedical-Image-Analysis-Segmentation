# Biomedical-Image-Analysis-Segmentation
This repository contains a collection of Python-based computer vision workflows focused on biomedical image analysis. The primary objective of this project is to develop automated, robust pipelines for medical image segmentation and classification, minimizing manual intervention and enhancing diagnostic workflows.

Currently, the repository features three main applications in clinical and experimental biology:
1.  **Nematode/Worm Segmentation:** Automated detection and morphological analysis of worms in microscopy images for high-throughput phenotyping.
2.  **Lung Contour Segmentation:** Automated identification and isolation of lung boundaries from medical imaging (e.g., X-rays/CT scans).
3.  **Skin Lesion Classification:** Image processing pipelines designed to extract features and classify dermatological lesions.

## Tech Stack & Tools
*   **Language:** Python 3.x
*   **Image Processing & Computer Vision:** OpenCV (`cv2`), `scikit-image`
*   **Data Manipulation:** `numpy`, `pandas`
*   **Data Visualization:** `matplotlib`, `seaborn`

## Project Structure
├── data/                   # Sample images or instructions to download the datasets
├── src/
│   ├── lung_segmentation/  # Scripts for lung contour extraction
│   ├── skin_lesions/       # Scripts for skin lesion preprocessing and classification
│   ├── worm_segmentation/  # Scripts for nematode tracking and morphological analysis
│   └── utils.py            # Helper functions for image loading and plotting
