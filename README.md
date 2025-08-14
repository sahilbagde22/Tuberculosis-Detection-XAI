# 🫁 Tuberculosis Detection with Explainable AI (XAI)

## 📌 Overview
This project implements a **deep learning-based Tuberculosis (TB) detection system** using **chest X-ray images** from the TBX11K dataset.  
To enhance trust and transparency in medical AI, the project integrates **Explainable AI (XAI)** techniques (such as Grad-CAM) to visualize which regions of the X-ray images influenced the model's predictions.

## 📊 Dataset
- **Name:** TBX11K Chest X-ray Dataset
- **Content:** X-ray images labeled as TB-positive or TB-negative
- **Source:** Public medical imaging dataset
- **Preprocessing:**
  - Image resizing and normalization
  - Data augmentation (rotation, flipping, zooming, shifting)
  - Train-validation-test split

## 🛠 Tech Stack
- **Programming Language:** Python
- **Libraries:**
  - Deep Learning: `TensorFlow`, `Keras`
  - Data Processing: `pandas`, `numpy`, `cv2`
  - Visualization: `matplotlib`
  - Evaluation: `scikit-learn`
  - XAI: Grad-CAM implementation

## ⚙ Methodology
1. **Data Loading & Preprocessing**
   - Extract and organize TBX11K dataset
   - Resize and normalize chest X-ray images
2. **Data Augmentation**
   - Applied transformations to reduce overfitting
3. **Model Architecture**
   - Custom CNN / Transfer Learning backbone
   - Classification head for binary TB detection
4. **Training & Evaluation**
   - Binary classification (TB-positive / TB-negative)
   - Metrics: Accuracy, Precision, Recall, F1-score
5. **Explainable AI**
   - Grad-CAM heatmaps to highlight decision-making regions
6. **Visualization**
   - Training history plots
   - Confusion matrix
   - Grad-CAM overlays

## 📈 Results
- **High Recall** for TB-positive cases to minimize false negatives
- Grad-CAM visualizations showing the lung regions most relevant to predictions


