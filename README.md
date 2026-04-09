# 🫁 IPF Detection using Deep Learning

## 📌 Objective
Detect early-stage Idiopathic Pulmonary Fibrosis (IPF) from HRCT images using deep learning.

---

## 📂 Dataset
- HRCT lung images
- Classes: Pulmonary Fibrosis (PF) and Normal
- Note: Full dataset not uploaded due to size constraints

---

## ⚙️ Methodology
- Image preprocessing
- Lung segmentation
- CNN-based classification
- Explainable AI (Grad-CAM)

---

## 📊 Results
(Add your confusion matrix / Grad-CAM images here)

---

## 📁 Project Structure
- notebooks/ → experiments
- src/ → model code
- images/ → visualization outputs
- results/ → output files

---

## 🛠️ Tools & Technologies
- Python
- TensorFlow / PyTorch
- OpenCV
- NumPy

---

## 🚀 Future Work
- Multimodal AI integration
- Early-stage fibrosis detection improvement
- Clinical validation


----------------------------------------------------------

# IPF Detection using Deep Learning

## Objective
Detect early-stage Idiopathic Pulmonary Fibrosis (IPF) from HRCT images using deep learning techniques.

## Dataset
The full main dataset and class-imbalanced dataset files are not uploaded to this repository due to file size limitations.

This repository contains the project implementation, result references, and documentation only.

### Dataset categories used
- Pulmonary Fibrosis (PF)
- Normal

### Dataset details
- HRCT lung image dataset
- Original class-imbalanced dataset used for experiments
- Balanced/generated variants used for comparison during model development

### Local dataset structure used
```text
data/
├── train/
│   ├── PF/
│   └── Normal/
├── val/
│   ├── PF/
│   └── Normal/
└── test/
    ├── PF/
    └── Normal/

open -e README.md
