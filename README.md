# CNN Model Comparison with Weighted Loss for Breast Cancer Classification

This repository contains the implementation of my undergraduate thesis project titled:  
**"Komparasi Model CNN terhadap Penggunaan Weighted Loss pada Klasifikasi Kanker Payudara"**

## 🎯 Project Objective

The objective of this study is to compare the impact of applying **Weighted Loss** on CNN-based models — **MobileNetV2**, **DenseNet121**, and **ResNet50** — for breast cancer detection using histopathological images. The goal is to evaluate whether weighted loss improves both class-specific performance (especially for cancer detection) and overall model metrics.

## 🧠 CNN Architectures Used
- MobileNetV2  
- DenseNet121  
- ResNet50

## 🛠 Tools & Technologies
- Python  
- TensorFlow / Keras  

## 📊 Key Findings

This study evaluates the effect of weighted loss using 5% and 10% subsets of histopathology image data. The weighted loss proved effective in enhancing cancer detection performance, particularly in MobileNetV2.

### 🔎 MobileNetV2 Performance Highlights:
- **Highest Recall**:  
  - 46.15% (on 5% data)  
  - 57.45% (on 10% data)  
- **F1-Score Improvement**:  
  - +5.08% (5% data)  
  - +8.77% (10% data)  
- **Precision Change**:  
  - −24.64% (5% data)  
  - +26.03% (10% data)  
- **Accuracy Slightly Decreased**:  
  - −5.75% (5% data)  
  - −4.76% (10% data)  
- **AUC Improvement**:  
  - +2.30% (5% data)  
  - 0% (10% data)

## 📁 Project Structure (Optional)
```bash
.
├── models/              # Saved models
├── notebook/            # Jupyter Notebooks
├── dataset/             # Link or description for dataset
├── scripts/             # Python training scripts
├── results/             # Graphs, performance logs
├── README.md
└── requirements.txt     # List of Python dependencies
