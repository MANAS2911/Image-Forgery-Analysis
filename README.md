# 🖼️ Image Forgery Analysis

A deep learning-powered image forensics system built using Convolutional Neural Networks (CNN) combined with Error Level Analysis (ELA) and image denoising techniques to classify images as real or forged. The system detects manipulations like copy-move, splicing, and removal forgeries, contributing to digital media integrity and forensics.

---

## 🚀 Features

- 📊 Comprehensive EDA and preprocessing for digital image analysis.
- 🖼️ Error Level Analysis (ELA) for pre-detection manipulation highlighting.
- 📈 Model training using CNN with Keras for binary classification.
- 🔄 Implemented data augmentation techniques — shifting, flipping, rotation, brightness adjustment.
- 🧹 Denoising images using BayesShrink and VisuShrink wavelet-based filters.
- 📑 Separate model evaluation for CASIA v1.0 and CASIA v2.0 datasets.
- 📈 Model performance analyzed using confusion matrices and bulk image classification.
- 📊 Achieved reliable classification accuracy on multiple forgery types.

---

## 📁 Project Structure

Image-Forgery-Analysis
- dataset (CASIA v1.0 and v2.0 datasets)
- eda_visualizations           (Preprocessing, ELA, and denoising plots)
- data_preprocessing     (Grayscale conversion, normalization)
- data_augmentation (Flipping, shifting, rotation)
- ela_preprocessing (Error Level Analysis scripts)
- denoising (BayesShrink and VisuShrink methods)
- cnn_model (CNN architecture and model training)
- evaluate_model       (Confusion matrix and bulk classification)
- README.md                     (Project documentation)

---

## 📊 Model Details

The forgery analysis uses:
- Convolutional Neural Networks (CNN) for binary image classification.
- ELA preprocessing to highlight manipulated image regions.
- Data augmentation to increase dataset diversity.
- Denoising with wavelet transforms (BayesShrink & VisuShrink).
- Separate training and evaluation on:
  - CASIA v1.0 Dataset: 800 authentic & 925 forged images
  - CASIA v2.0 Dataset: 7491 authentic & 5123 forged images.
  
---

## 📈 Data Insights & Visualizations

- 📊 ELA highlighted tampered regions effectively in compressed JPEG images.
- 📈 Wavelet-based denoising improved feature extraction for subtle manipulations.
- 🔄 Data augmentation techniques enhanced model generalization on unseen images.
- 📑 Model achieved high precision in identifying copy-move, splicing, and removal forgeries.

---

## 🙋‍♂️ Author

Manas Choudhary,
Final Year Computer Engineering Student,
Project: Image Forgery Analysis

Feel free to connect on [LinkedIn](www.linkedin.com/in/contactmanaschoudhary) or raise an issue or PR.

---

## ⭐ Star This Repository
If you like this project, give it a ⭐ to help others find it!

