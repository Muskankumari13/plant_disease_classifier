# Plant Disease Classification using Deep Learning

A deep learning-based image classification project for identifying and classifying plant diseases using Convolutional Neural Networks (CNNs) and Transfer Learning techniques. This project utilizes the **New Plant Diseases Dataset** from Kaggle and aims to assist in early disease detection for healthier crop production.

---

## Project Overview

Plant diseases significantly affect agricultural productivity and food quality. Manual disease detection is time-consuming and requires expert knowledge. This project automates the process using AI and Computer Vision.

The model is trained on thousands of labeled plant leaf images to classify healthy and diseased plants accurately.

---

## Dataset

Dataset Used:
**New Plant Diseases Dataset (Augmented)**

Dataset Link:
[Kaggle Dataset - New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset?utm_source=chatgpt.com)

### Dataset Features

* 38 different plant disease classes
* Healthy and diseased leaf images
* Augmented dataset for better generalization
* RGB plant leaf images

### Example Classes

* Tomato Early Blight
* Potato Late Blight
* Apple Scab
* Corn Rust
* Healthy Leaves

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```bash
Plant-Disease-Classification/
│
├── dataset/
│   ├── train/
│   ├── valid/
│   └── test/
│
├── models/
│   └── trained_model.h5
│
├── outputs/
│   ├── accuracy_graph.png
│   ├── confusion_matrix.png
│   └── predictions/
│
├── Plant_Disease_classification_project.ipynb
│
├── requirements.txt
│
└── README.md
```

---

## Features

* Plant disease detection using Deep Learning
* Image preprocessing and augmentation
* CNN-based classification
* Transfer Learning support
* Model evaluation with accuracy/loss graphs
* Confusion matrix visualization
* Predict disease from custom leaf images

---

## Installation

### 1. Clone Repository

```bash
git clone https://github.com/your-username/Plant-Disease-Classification.git
cd Plant-Disease-Classification
```

---

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Project

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Plant_Disease_classification_project.ipynb
```

---

## Model Training

The project includes:

* Data preprocessing
* Image resizing
* Data augmentation
* CNN model building
* Training & validation
* Performance evaluation

---

## Model Evaluation

Evaluation metrics used:

* Accuracy
* Loss
* Confusion Matrix
* Precision
* Recall
* F1-Score

---

## Results

The trained model achieves high classification accuracy on validation data and can successfully predict multiple plant diseases from leaf images.


## Contribution

Contributions are welcome.

```bash
Fork the repository
Create a new branch
Commit your changes
Push to your branch
Create a Pull Request
```

---

## License

This project is licensed under the MIT License.

