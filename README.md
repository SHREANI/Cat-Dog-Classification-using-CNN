# Cat-Dog-Classification-using-CNN
This project is a **Convolutional Neural Network (CNN) model** that classifies images of cats and dogs.   It is built in **Python** using **TensorFlow/Keras** and demonstrates image preprocessing, CNN training, and evaluation with accuracy/loss plots and a confusion matrix. 

## 1. Project Overview
- Classify images as Cat or Dog
- CNN with convolutional, pooling, and dense layers
- Microsoft Cats vs Dogs dataset (via Kaggle)

# 2. Explain how your project files are organized:
Cat-Dog-Classifier/
├── .gitignore
├── README.md
├── requirements.txt
├── cat_dog_cnn.ipynb

## 3. Dataset
- Source: Provide Kaggle link or Microsoft link.
  
- Preprocessing: Explain image resizing, train/test split, data augmentation, and cleaning corrupted images.
  
- Note: Dataset is ignored in GitHub

## 4. Installation

bash

git clone https://github.com/<username>/Cat-Dog-Classifier.git

cd Cat-Dog-Classifier

pip install -r requirements.txt


## 5. Model Architecture

Input: 128x128 RGB images

Layers: Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Dropout → Output

Activation: ReLU (hidden), Sigmoid (output)

Optimizer: Adam

Loss Function: Binary Crossentropy

Epochs: 10 (can be increased)

## 6. Training & Evaluation

Accuracy/Loss graphs

Confusion Matrix

Classification Report (precision, recall, F1-score)

## 7. Results

Training Accuracy

Validation Accuracy

Observations from confusion matrix

## 8. Usage
Run cat_dog_cnn.ipynb to train and evaluate the model

## 9. Tips & Notes

Increase epochs or modify CNN layers for higher accuracy.

Ensure Kaggle API is set up if using KaggleHub.

## 10. References

TensorFlow Keras Documentation

Microsoft Cats vs Dogs Dataset

KaggleHub
