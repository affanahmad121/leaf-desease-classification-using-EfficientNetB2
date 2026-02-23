# Leaf Disease Classification using EfficientNetB2
gpu- tesla p100
## Project Overview
This project focuses on automatic classification of plant leaf diseases using Deep Learning.  
A transfer learning approach is applied using the EfficientNetB2 model to accurately classify different leaf diseases.

The model achieves:
-  99% Training Accuracy
- 96% Validation Accuracy

---

## Objective
- To build an automated plant disease detection system
- To classify leaf images into healthy and diseased categories
- To assist farmers in early disease identification

---

## Dataset
- Dataset: Plant Leaf Disease Dataset
- Image Type: RGB leaf images
- Number of Classes: (mention your number here)
- Preprocessing: Resizing, Normalization, Data Augmentation

---

##  Model Architecture

### Base Model
- EfficientNetB2 (Pre-trained on ImageNet)

### Added Layers
- Global Average Pooling
- Dense Layers
- Dropout
- Softmax Output Layer

Transfer learning is used to improve performance and reduce training time.

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV

---

## Performance Metrics
- Training Accuracy: 99%
- Validation Accuracy: 96%
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

---

## How to Run
1. Clone the repository
2. Install required libraries
3. Load dataset
4. Run training notebook
5. Evaluate model

---

## Results
The EfficientNetB2 model successfully classifies leaf diseases with high accuracy and generalization capability.

---

## Future Scope
- Deploy as mobile/web application
- Improve model robustness with more diverse dataset
- Real-time disease detection using camera input
- Integrate fertilizer recommendation system

---

## Author
AFFAN AHMAD
part time Project 
