# VinDr-CXR-chest-X-ray-classification-and-detection-project

# 🩻 Chest X-Ray Abnormalities Detection

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red)
![Kaggle](https://img.shields.io/badge/Run%20on-Kaggle-brightgreen)

This repository contains a Kaggle Notebook for detecting abnormalities in chest X-rays using the **VinDr-CXR dataset**.

---

## 📘 About

- Developed and executed entirely on **Kaggle**.  
- Implements an end-to-end pipeline:
  - Dataset preparation (DICOM → PNG, annotations → COCO/YOLO)
  - Baseline classification (ResNet18 with AUC/F1)
  - Object detection (YOLO / Faster R-CNN with mAP evaluation)
  - Grad-CAM visualizations for interpretability
- Updated notebook includes:
  - ✅ Dataset provenance checks  
  - ✅ Baseline classifier  
  - ✅ Validation summary  

---

## 🚀 How to Use

1. Open the notebook on [Kaggle](https://www.kaggle.com/) or clone this repo.  
2. The dataset is available at [VinDr-CXR on Kaggle](https://www.kaggle.com/datasets/vinbigdata/vindr-cxr).  
3. Run the notebook cells in sequence:
   - **Section 1**: Data preparation & verification  
   - **Section 2**: Classification & detection training  
   - **Section 3**: Evaluation & visualization  

---

## 📊 Results

- **Classification baseline**: Reports **AUC** and **F1-score**  
- **Detection models**: Evaluated with **mAP** at multiple IoU thresholds  
- **Grad-CAM**: Generates heatmaps to highlight important regions  

---

## 📌 Notes

- 📂 No dataset files are included in this repo — dataset is handled via Kaggle.  
- 📝 The notebook runs end-to-end on Kaggle without extra setup.  
- 🔄 Pushes to GitHub only include the notebook (`.ipynb`).  

---
