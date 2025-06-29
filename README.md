# 🧬 Skin Cancer Detection using Deep Learning

This project uses a Convolutional Neural Network (CNN) model to classify skin lesions as **Benign** or **Malignant** using medical image data. The final model is served via a user-friendly Gradio interface for easy testing and interaction.

---

## 🚀 Features

- 📂 Image dataset mounted from Google Drive
- 🧠 CNN-based classification model
- 📊 Visualizations of data distribution and training performance
- 🧪 Early stopping to avoid overfitting
- ⚖️ Class balancing with `class_weight`
- 🎛️ Interactive Gradio-based UI for predictions
- ✅ Model accuracy and performance metrics displayed with plots

---

## 🗂️ Dataset

- **Source**: Private dataset uploaded in Google Drive
- **Path Used in Colab**:  
  `/content/drive/MyDrive/Skin Cancer Detection/Datasets/skin_cancer`
- **Classes**:
  - `benign`
  - `malignant`

> To use the dataset:  
> Upload your dataset to your own Google Drive and mount it using:
```python
from google.colab import drive
drive.mount('/content/drive')
