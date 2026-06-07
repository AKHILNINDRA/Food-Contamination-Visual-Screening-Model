# Fruit Freshness Classification

A deep learning project for classifying fruits as **Fresh** or **Rotten** using image classification techniques.

##  Project Overview

This project uses a Convolutional Neural Network (CNN) to classify fruit images into six categories:

- Fresh Apples
- Fresh Bananas
- Fresh Oranges
- Rotten Apples
- Rotten Bananas
- Rotten Oranges

The goal is to automate fruit quality assessment, which can be useful in agriculture, food processing, inventory management, and retail industries.

---

## Dataset

Dataset: Fruits Fresh and Rotten for Classification

The dataset contains approximately 13,599 images of fruits categorized into six classes.

LINK:https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification

### Dataset Structure

```
dataset/
├── train/
│   ├── freshapples/
│   ├── freshbanana/
│   ├── freshoranges/
│   ├── rottenapples/
│   ├── rottenbanana/
│   └── rottenoranges/
│
└── test/
    ├── freshapples/
    ├── freshbanana/
    ├── freshoranges/
    ├── rottenapples/
    ├── rottenbanana/
    └── rottenoranges/
```

---

## Features

- Image classification using Deep Learning
- Data augmentation for improved generalization
- Model evaluation using test data
- Prediction on custom fruit images
- Performance visualization using accuracy and loss curves

---

## MODELS USED

A CNN model built using:

- Conv2D
- MaxPooling2D
- Dense Layers
- Dropout

MobileNetV2
- Transfer learning model pretrained on ImageNet.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## Dataset Statistics

| Class | Training Images | Testing Images |
|---------|---------:|---------:|
| Fresh Apples | 1693 | 395 |
| Fresh Bananas | 1581 | 381 |
| Fresh Oranges | 1466 | 388 |
| Rotten Apples | 2342 | 601 |
| Rotten Bananas | 2224 | 530 |
| Rotten Oranges | 1595 | 403 |

---

## Results

The trained CNN model achieves high classification accuracy on the test dataset and effectively distinguishes between fresh and rotten fruits.

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Future Improvements

- Deploy as a web application using Flask or Streamlit
- Mobile application integration
- Real-time fruit freshness detection
- Support for additional fruit categories


---

## License

This project is intended for educational and research purposes.

---

##  Acknowledgements

- Kaggle Dataset: Fruits Fresh and Rotten for Classification
- TensorFlow & Keras Community
- Open Source Contributors
