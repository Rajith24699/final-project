
# 🧠 Brain Tumor Classification Using Deep Learning

This project investigates and compares advanced deep learning techniques for automatic brain tumor detection and classification using MRI images. Three primary architectures—Convolutional Neural Network (CNN), CNN with VGG-16, and ResNet50—are implemented and evaluated.

## 🎓 Project Overview

- **Project Title:** Enhanced Deep Learning Techniques for Automatic Brain Tumor Identification and Categorization Using MRI Images
- **Author:** Rajith Narasimha Murthy (SRN: 23004934)
- **Supervisor:** William Alston
- **Institution:** University of Hertfordshire – MSc Data Science (7PAM2002)
- **Submission Date:** 29/04/2025

## 🚀 Objectives

- Develop CNN, CNN-VGG-16, and ResNet50-based classifiers for brain tumor detection.
- Evaluate and fine-tune these models for optimal accuracy and performance.
- Conduct comparative analysis to determine the most effective model for clinical use.

## 📊 Dataset

- Publicly available MRI brain scan dataset.
- Comprises 7,023 images classified into:
  - Glioma
  - Meningioma
  - Pituitary Tumor
  - No Tumor
- Preprocessing steps:
  - Resizing (250x250)
  - Grayscale conversion
  - Augmentation (flipping, rotation, zoom, contrast)

## 🛠️ Tools and Frameworks

- Python, TensorFlow, Keras
- VGG-16 and ResNet50 (Transfer Learning)
- Google Colab for model training
- Matplotlib, Seaborn for visualizations

## 🧪 Model Performance

| Model        | Training Accuracy | Testing Accuracy |
|--------------|-------------------|------------------|
| CNN          | 99.91%            | 99.16%           |
| CNN-VGG-16   | 98.91%            | 98.47%           |
| ResNet50     | 75.96%            | 67.43%           |

- CNN performed best with high accuracy and generalization.
- ResNet50 underperformed due to underfitting and architectural complexity.

## 📈 Key Metrics

- **Precision, Recall, F1-Score:** Averaged ~0.99 for CNN
- **Confusion Matrices:** Provided for all models
- **Model Comparison:** CNN outperforms prior studies in accuracy

## 📚 Literature Support

This project builds on recent advances in deep learning applied to medical imaging. Several benchmark studies and methods are discussed, with our CNN implementation exceeding many previous benchmarks.

## 🔍 Challenges Faced

- Overfitting on smaller datasets
- Grad-CAM errors with uninitialized layers
- Computational constraints with deeper networks like ResNet50

## 📁 Repository Contents

```
📁 /models         # Trained model files (CNN, VGG-16, ResNet50)
📁 /notebooks      # Jupyter/Colab notebooks
📁 /images         # Sample tumor images & augmentations
📄 README.md       # Project documentation
📄 report.pdf      # Full MSc dissertation
```

## 🧠 Future Enhancements

- Integrate Grad-CAM for explainable AI
- Experiment with hybrid ensemble models
- Use BraTS 2023 dataset for further robustness

## 🔗 Project Link

[🔗 GitHub Repository](https://github.com/Rajith24699/final-project)

---

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.
