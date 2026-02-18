# Adriatic Cloud Occlusion Detection

## Overview

This project explores a deep learning approach to detecting cloud occlusion over the Adriatic region using satellite imagery.

The objective is to train a neural network model capable of learning visual cloud patterns from image data and predicting occluded regions accurately.

This project was developed as part of a Deep Learning course.

---

## Dataset

The dataset consists of satellite images of the Adriatic region.

The data is used to:
- Identify cloud-covered areas
- Train a deep neural network
- Evaluate model performance on unseen samples

*Note:* If the dataset exceeds GitHub’s size limits, it is not included in this repository.

---

## Methodology

The notebook includes the following steps:

### 1. Data Preprocessing
- Image normalization  
- Resizing  
- Train/validation/test split  

### 2. Model Architecture
- Convolutional Neural Network (CNN)  
- Appropriate loss function  
- Optimizer (e.g., Adam)

### 3. Training
- Forward propagation  
- Backpropagation  
- Loss monitoring  

### 4. Evaluation
- Accuracy  
- Validation performance  
- Loss curves  

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/rshahri/adriatic-cloud-occlusion-dl.git
cd adriatic-cloud-occlusion-dl
```

---

## Technologies Used

- Python
- PyTorch / TensorFlow
- NumPy
- Matplotlib
- Scikit-learn
## Repository Structure

