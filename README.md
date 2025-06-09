# DeepSight DR: Deep Learning-Powered Diabetic Retinopathy Detection

> An AI-powered, scalable, and accessible solution for early detection of Diabetic Retinopathy using InceptionV2 & InceptionV3 CNN architectures.

## 🚀 Overview

DeepSight DR is a deep learning-based system for classifying Diabetic Retinopathy (DR) severity from retinal fundus images. It uses CNN models—InceptionV2 and InceptionV3—enhanced with transfer learning and a robust preprocessing pipeline to enable accurate detection across five severity levels. The system is scalable, web-deployable, and future-ready for edge/mobile devices.

## 💡 Key Features

- 🧠 Dual-model architecture: InceptionV2 and InceptionV3
- ⚙️ Transfer learning for low-data environments
- 🔄 Preprocessing with Gaussian filtering & CLAHE
- 🌐 Flask-based web app with real-time inference
- 📊 Grad-CAM explainability for visual diagnostics
- 🧪 Evaluated using ROC-AUC, precision, recall, F1-score
- 🧯 Batch processing support for scalability
- 📱 Future-ready for mobile and edge deployment

## 🖼️ DR Classification Categories

1. **No DR**
2. **Mild**
3. **Moderate**
4. **Severe**
5. **Proliferative DR**

## 🔬 Methodology

### Data Preparation
- Dataset: EyePACS + other public retinal databases
- Augmentation: Rotation, flipping, noise, GANs
- Resolution: Standardized to 299x299 for Inception compatibility

### Model Training
- Pretrained on ImageNet
- Fine-tuned with custom top layers
- Optimizer: Adam (LR: 0.0001)
- Loss: Categorical Crossentropy
- Regularization: Dropout, L2 weight decay

### Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- ROC-AUC
- Confusion Matrix
- K-Fold Cross Validation

### Explainability
- Grad-CAM heatmaps to highlight decision areas

## 🛠️ System Implementation

- Python (TensorFlow, Keras)
- Google Colab for training
- Flask for deployment
- Optional: Grid Search or Bayesian Optimization for hyperparameter tuning

## 📊 Results

- InceptionV3 outperformed InceptionV2 and standard CNN
- Stable validation accuracy with minimal overfitting
- Validation on external datasets confirmed generalizability

## 🧭 Future Enhancements

- 🔍 Integrate EfficientNet/MobileNet for mobile/edge deployment
- ⚡ Federated learning for secure distributed training
- 🧠 Add glaucoma & AMD detection
- ☁️ Cloud-based EHR integration
- 🔓 Open-source + low-cost deployment kits

## 📁 Repository Structure


