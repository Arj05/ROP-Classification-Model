# ROP Classification Model

## Overview
A deep learning model for detecting Retinopathy of Prematurity (ROP) using convolutional neural networks, developed for medical image classification.

## Features
- Direct image upload in Google Colab
- Data augmentation to enhance model performance
- VGG19-inspired CNN architecture
- Binary classification (ROP vs NON_ROP)

## Requirements
- Python 3.7+
- TensorFlow
- OpenCV
- scikit-learn
- matplotlib
- seaborn

## Installation
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Prepare your image dataset in ROP and NON_ROP folders

## Usage
1. Open the notebook in Google Colab
2. Upload ROP and NON_ROP retinal images
3. Run cells sequentially
4. Model will train and save best checkpoint

## Model Architecture
- 4 convolutional blocks
- MaxPooling layers
- Dropout for regularization
- Binary softmax output

## Outputs
- Trained model (`.hdf5`)
- Training history plot
- Confusion matrix visualization
- Classification report

## Performance Metrics
- Accuracy tracked during training
- Validation loss monitored
- Early stopping implemented

## Contributing
1. Fork repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create pull request

## License
MIT License
