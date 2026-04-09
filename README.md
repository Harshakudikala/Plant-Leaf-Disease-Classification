# Leaf Disease Classification using Image Processing and ML

![Python](https://shields.io)
![OpenCV](https://shields.io)
![ML](https://shields.io)

## 🌿 Overview
This project provides an automated system for the early detection of plant leaf diseases. By leveraging **Image Processing** and **Machine Learning**, the solution identifies healthy and diseased leaves, significantly reducing the need for manual monitoring in large-scale agricultural fields.

## 🚀 Key Features
*   **Automated Detection**: Eliminates human error in identifying crop infections.
*   **Image Processing**: Uses OpenCV for noise reduction, resizing, and color space conversion.
*   **ML Classification**: Employs supervised learning to categorize leaf health.
*   **Scalable**: Designed for integration into drone-based or IoT monitoring systems.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** OpenCV, NumPy, Scikit-learn, Matplotlib
- **Tools:** Jupyter Notebook / VS Code

## 📋 Workflow
1.  **Image Acquisition**: Collecting leaf samples from the dataset.
2.  **Preprocessing**: Grayscale conversion, Histogram Equalization, and Background Removal.
3.  **Segmentation**: Isolating the diseased spots using K-means or Contour detection.
4.  **Feature Extraction**: Extracting texture, color, and shape descriptors.
5.  **Classification**: Training the model (SVM/Random Forest/CNN) to predict the disease.

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com

# Navigate to the directory
cd leaf-disease-classification

# Install dependencies
pip install -r requirements.txt
