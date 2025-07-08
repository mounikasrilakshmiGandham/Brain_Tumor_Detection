# Brain Tumor Detection Using Deep Learning on MRI Images

This project performs **multi-class brain tumor classification** using a **VGG16-based convolutional neural network**. It processes MRI images of four categories: **glioma**, **meningioma**, **pituitary**, and **no tumor**, using Keras and TensorFlow.

---

## Dataset

The dataset used is organized as:
/Training/
├── glioma/
├── meningioma/
├── pituitary/
└── notumor/

/Testing/
├── glioma/
├── meningioma/
├── pituitary/
└── notumor/

## 🔧 Features

- VGG16 transfer learning (ImageNet weights)
- Custom image augmentation (brightness, contrast)
- Training on shuffled and preprocessed data
- Evaluation using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC-AUC
- Visualization:
  - Random image preview with labels
  - Training curves (accuracy, loss)
  - ROC curves
- Tumor detection function for any new image
