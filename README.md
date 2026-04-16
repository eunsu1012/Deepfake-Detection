# 🎭 Deepfake Detection using EfficientNetB4 and VGG19

A deep learning-based project for detecting deepfake human face images.  
This study performs a comparative analysis between EfficientNetB4 and VGG19 to evaluate their effectiveness in identifying manipulated images.


## 📌 Overview

Deepfakes are AI-generated synthetic media that manipulate facial features to create highly realistic fake images or videos.  
They pose serious risks in digital security, misinformation, and identity fraud.

Detecting deepfakes has become a critical task in computer vision and digital forensics, as these models must identify subtle visual inconsistencies such as lighting artifacts, facial distortions, and unnatural textures. :contentReference[oaicite:0]{index=0}

This project focuses on building a robust deepfake detection system using convolutional neural networks (CNNs).


## 🎯 Objectives

- Detect deepfake images using deep learning models  
- Compare the performance of EfficientNetB4 and VGG19  
- Analyze model efficiency and generalization ability  
- Identify the most suitable architecture for deepfake detection  


## 🧠 Key Features

- CNN-based image classification for real vs fake detection  
- Comparative analysis of two state-of-the-art architectures  
- Evaluation using standard classification metrics  
- Focus on model efficiency and performance trade-offs  


## 🗂️ Dataset

The project uses face image datasets containing:

- Real human face images  
- AI-generated deepfake images  

Common datasets in deepfake research include FaceForensics++ and DeepFake Detection Challenge datasets, which are widely used for training detection models. :contentReference[oaicite:1]{index=1}


## ⚙️ Methodology

The project follows a deep learning pipeline:

1. Data preprocessing  
   - Image resizing and normalization  
   - Data augmentation  

2. Model Development  
   - EfficientNetB4  
   - VGG19  

3. Training  
   - Binary classification (Real vs Fake)  

4. Evaluation  
   - Accuracy  
   - Precision / Recall  
   - F1-score  


## 🧩 Model Architecture

### 1. EfficientNetB4
- Uses compound scaling (depth, width, resolution)  
- Achieves high accuracy with optimized efficiency  
- Suitable for capturing subtle visual patterns  

EfficientNet-based models have demonstrated strong performance in deepfake detection, achieving high accuracy and generalization. :contentReference[oaicite:2]{index=2}  


### 2. VGG19
- Deep CNN architecture with simple structure  
- Strong baseline model for image classification  

Previous studies show that VGG19 can achieve high accuracy (around 95%) in deepfake detection tasks. :contentReference[oaicite:3]{index=3}  


## 📊 Model Evaluation

Evaluation metrics include:

- **Accuracy**: Overall classification performance  
- **Precision / Recall**: Class-specific performance  
- **F1-score**: Balance between precision and recall  

Deep learning-based detectors typically achieve high performance (often above 90% accuracy) depending on dataset and model choice. :contentReference[oaicite:4]{index=4}  


## 🛠️ Tech Stack

- Python  
- TensorFlow / Keras or PyTorch  
- OpenCV  
- NumPy / Pandas  
- Matplotlib / Seaborn  


## 📁 Project Structure

```
Deepfake-Detection/
│
├── data/                # Dataset
├── notebooks/           # Training & experiments
├── src/                 # Model implementation
├── models/              # Saved models
├── results/             # Evaluation results
└── README.md
```


## 🚀 Results

- Built deepfake detection models using CNN architectures  
- Compared EfficientNetB4 and VGG19 performance  
- Identified differences in accuracy and efficiency  


## 📌 Limitations

- Performance depends heavily on dataset quality  
- Limited generalization across unseen deepfake techniques  
- Real-world deployment requires robustness testing  


## 🔧 Future Work

- Apply transformer-based models (ViT, Swin Transformer)  
- Improve generalization across datasets  
- Integrate real-time detection systems  


## 👤 Author

Park, Eunsoo
Shrestha, Sandesh
Gautam, Saumya

## ✔️ Summary

> A comparative deep learning project analyzing EfficientNetB4 and VGG19 for accurate deepfake image detection
