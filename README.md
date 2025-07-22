# 🌱 Seed Classification using Deep Learning (ResNet18)

Built a deep learning-based seed classification model using ResNet18 and transfer learning to automate and enhance seed variety recognition in agriculture, using a custom dataset of 759 manually captured and labeled seed images.

## ✨ Key Features

- 🚀 **Transfer Learning with ResNet18**: Leveraged a pretrained model for fast and effective training.
- 🖼️ **Custom Dataset**: 759 seed images captured and labeled manually, structured for PyTorch `ImageFolder`.
- 🧠 **High Accuracy**: Achieved **98.64% validation accuracy** and **96.6% test accuracy**.
- 🔄 **Data Augmentation**: Applied random flips, rotations, and normalization to improve generalization.
- 📊 **Training Visualization**: Plotted training loss and validation accuracy for monitoring progress.

## 🛠️ Tech Stack

- Python 3.x  
- PyTorch & Torchvision  
- Google Colab  
- OpenCV & Pillow (PIL)  
- Matplotlib  

## 🧪 Workflow

1. **Data Collection & Preprocessing**
   - Captured and labeled seed images manually
   - Applied transformations and augmentations

2. **Model Development**
   - Loaded pretrained ResNet18
   - Replaced final classification layer for custom seed classes
   - Trained using Adam optimizer and cross-entropy loss

3. **Evaluation**
   - Monitored training and validation curves
   - Achieved stable and high performance by epoch 10

4. **Prediction**
   - Implemented a function to classify new seed images with high confidence

## 📁 Dataset

- Total of 759 manually created seed images
- Controlled lighting and background for consistency
