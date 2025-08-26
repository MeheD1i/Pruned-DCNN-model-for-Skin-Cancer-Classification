# 🩺 A Lightweight Pruned DCNN Model with XAI for Skin Cancer Classification 

## 📌 Overview  
Skin cancer is one of the most aggressive cancers, where early detection can drastically improve survival rates.  
This project presents a **lightweight pruned Deep Convolutional Neural Network (DCNN)** for **skin cancer classification** using the **HAM10000 dataset**.
Our model achieves **98.07% accuracy** while being **lightweight, fast, and deployment-ready** for real-world medical applications.

## 📂 Dataset  
We used the **HAM10000 dataset (10,015 dermatoscopic images)** containing 7 classes:  
- **NV** – Melanocytic nevi  
- **MEL** – Melanoma  
- **BKL** – Benign keratosis-like lesions  
- **BCC** – Basal cell carcinoma  
- **AKIEC** – Actinic keratoses / intraepithelial carcinoma  
- **VASC** – Vascular lesions  
- **DF** – Dermatofibroma

## 🛠️ Tech Stack  
- **Language**: Python  
- **Frameworks**: TensorFlow, Keras  
- **Models**: Custom CNN + Pre-trained CNNs (VGG, ResNet, MobileNet, DenseNet, Inception, Xception, EfficientNet)  
- **Techniques**: Data Augmentation, Weight Pruning, Grad-CAM++

## ⚡ Key Features  
- ✅ **Custom Deep CNN** with 6 convolutional layers  
- ✅ **50% Weight Pruning** → reduces size from **1.31 MB → 0.45 MB**  
- ✅ **Balanced & Augmented Dataset** for fair training  
- ✅ **Compared with 11 Pre-trained Models** (VGG16, ResNet50, MobileNetV2, etc.)  
- ✅ **Explainable AI (Grad-CAM++)** to highlight decision-making regions  
- ✅ **Fast Inference**: ~0.039s per image  
- ✅ **Deployment-friendly** for mobile/embedded devices

  
