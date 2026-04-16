# Deepfake Detection using EfficientNetB4 and VGG19

## 1. Project Overview
This project focuses on detecting deepfake human face images using deep learning models.  
A comparative analysis is conducted between EfficientNetB4 and VGG19 to evaluate their effectiveness in identifying manipulated images.

---

## 2. Problem Statement
With the rapid advancement of deep learning, deepfake images have become increasingly realistic and difficult to distinguish from real images.  
These manipulated images pose serious risks in areas such as misinformation, privacy, and security.

This project aims to develop a reliable deepfake detection system and compare model performance to identify the most effective architecture.

---

## 3. Dataset
The dataset used in this project consists of high-quality human face images:

- Total images: 140,000  
- Real images: 70,000  
- Fake images: 70,000 (generated using StyleGAN)  
- Image resolution: 256 × 256  

The dataset includes diverse variations in:
- lighting conditions  
- facial expressions  
- background and accessories  

It is split into:
- Training set: 100,000 images  
- Validation set: 20,000 images  
- Test set: 20,000 images  

---

## 4. Methodology

### Data Preprocessing
- Images resized to **224 × 224** to match model input requirements  
- RGB color format maintained  
- No data augmentation applied due to sufficient dataset diversity  

---

## 5. Model Architecture

### EfficientNetB4
- Optimized for performance and computational efficiency  
- Uses compound scaling (depth, width, resolution)  

### VGG19
- Deep convolutional neural network with simple architecture  
- Strong feature extraction capability for image classification  

---

## 6. Results

| Model           | Accuracy |
|----------------|----------|
| EfficientNetB4 | 98.54%   |
| VGG19          | 99.11%   |

---

## 7. Key Insights

- **VGG19 achieved higher accuracy**, indicating strong performance in capturing detailed image features  
- **EfficientNetB4 showed competitive performance with better efficiency**, making it suitable for resource-constrained environments  
- Model selection should consider both **accuracy and computational cost**

---

## 8. Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  

---

## 9. How to Run

```bash
git clone https://github.com/eunsu1012/Deepfake-Detection.git
cd Deepfake-Detection

pip install -r requirements.txt

python train.py
