Wildfire Image Classification Using CNN and Transfer Learning
Project Overview
This project develops a wildfire image classification system using Convolutional Neural Networks (CNNs) and Transfer Learning (MobileNetV2).

The objective is to automatically classify images into:

Fire
No Fire
The project supports disaster management and emergency response applications by assisting in wildfire detection.

Dataset
The Wildfire Dataset

Dataset Link: https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset

Models Used
Custom CNN
A CNN model built using:

Conv2D
MaxPooling2D
Dense Layers
Dropout
MobileNetV2
Transfer learning model pretrained on ImageNet.

Results
Model	Accuracy
CNN	82.20%
MobileNetV2	85.85%
Output Figures
Sample Images
Accuracy Curve
Loss Curve
Confusion Matrix
ROC Curve
Error Analysis
Gradcam_Heatmap
How to Run
Install dependencies:
pip install -r requirements.txt

Open the notebook.

Run all cells in sequence.
