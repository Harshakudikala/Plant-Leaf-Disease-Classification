# 🌿 PlantGuard AI — Leaf Disease Detection System

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-red?style=flat-square&logo=opencv&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat-square&logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

> Automated plant leaf disease detection via image processing and machine learning — enabling early diagnosis and scalable monitoring in large-scale agriculture.

---

## 📌 Overview

PlantGuard AI is an end-to-end computer vision system that **detects and classifies plant leaf diseases** from images using OpenCV preprocessing pipelines and machine learning models.

Designed for large-scale agricultural operations, it reduces the need for manual crop monitoring by enabling **early diagnosis** before disease spreads — improving treatment outcomes and protecting crop yields.

---

## ✨ Key Features

- 🔍 **Automated detection** — Identifies leaf diseases from raw field images
- ⚡ **Fast classification** — Processes images in real-time without manual intervention
- 🌱 **Early-stage diagnosis** — Catches disease before visible widespread damage
- 📊 **Confidence scoring** — Outputs disease type with probability estimate
- 🖥️ **Lightweight** — Runs on standard hardware, no GPU required

---

## 🔬 How It Works

```
Image Input → Preprocessing → Segmentation → Feature Extraction → ML Classification → Diagnosis
```

| Step | Description |
|------|-------------|
| **1. Image Input** | Accept leaf images from camera, drone, or file upload |
| **2. Preprocessing** | Noise reduction, resizing, and color normalization via OpenCV |
| **3. Segmentation** | Isolate the leaf region from background using masking |
| **4. Feature Extraction** | Extract color histograms, texture features, and shape descriptors |
| **5. Classification** | ML model predicts disease class from extracted features |
| **6. Diagnosis** | Output disease label + confidence score for farmer/agronomist |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.9+** | Core language |
| **OpenCV** | Image preprocessing, segmentation |
| **Scikit-learn / TensorFlow** | Model training and inference |
| **NumPy / Pandas** | Data processing |
| **Matplotlib** | Result visualization |
| **PIL / Pillow** | Image I/O and format handling |

---

## 📈 Results

| Metric | Value |
|--------|-------|
| Classification Accuracy | **95%+** |
| Speed vs Manual Inspection | **~10x faster** |
| Detection Stage | **Early (pre-spread)** |
| Hardware Requirement | Standard CPU |

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.9+
pip
```

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/plantguard-ai.git
cd plantguard-ai

# Install dependencies
pip install -r requirements.txt
```

### Run Detection

```bash
# Detect disease in a single leaf image
python detect.py --image leaf.jpg --model models/classifier.pkl

# Example output
→ Detected: Bacterial Blight (confidence: 94.2%)
```

### Train on Custom Dataset

```bash
# Train a new model on your own labeled data
python train.py --dataset data/leaves/ --output models/my_model.pkl
```

---

## 📂 Project Structure

```
plantguard-ai/
├── detect.py              # Main inference script
├── train.py               # Model training pipeline
├── preprocess.py          # OpenCV image preprocessing utilities
├── models/
│   └── classifier.pkl     # Pretrained ML model
├── data/
│   └── leaves/            # Training dataset (not included)
├── notebooks/
│   └── exploration.ipynb  # EDA and model evaluation
├── requirements.txt
└── README.md
```

---

## 🌾 Impact

- **Reduces crop loss** — Timely alerts help farmers intervene before yields are impacted
- **Scales monitoring** — Process thousands of images per batch automatically
- **Lowers costs** — Eliminates the need for constant manual field inspection
- **Accessible** — Works on standard hardware; no specialized equipment needed

---

## 🗺️ Roadmap

- [ ] Web interface for non-technical users
- [ ] Mobile app integration (field use)
- [ ] Support for drone/satellite imagery
- [ ] Expand to 50+ disease classes
- [ ] Real-time video stream detection

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

> ⭐ If this project helped you, consider giving it a star!
