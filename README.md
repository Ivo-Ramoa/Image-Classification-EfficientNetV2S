# Image Classification with EfficientNetV2S

Deep learning project for multi-class image classification using **TensorFlow/Keras** and **EfficientNetV2S**.

The project applies transfer learning and fine-tuning to the **Fruits-360** dataset, containing images of fruits and vegetables distributed across 206 classes.

## Project Overview

The objective of this project was to develop an image classification model capable of identifying different fruit and vegetable classes.

The project includes:

- Image preprocessing and dataset preparation
- Data augmentation
- Transfer learning using EfficientNetV2S
- Fine-tuning of the pre-trained network
- Model evaluation on unseen test data
- Training history analysis
- Confusion matrix analysis

## Dataset

The project uses the **Fruits-360** dataset.

Dataset distribution used in the project:

- 206 classes
- 83,195 training images
- 20,798 validation images
- 34,711 test images

The dataset is not included in this repository.

## Model

The classifier is based on **EfficientNetV2S**, pre-trained on ImageNet.

The training process used transfer learning followed by fine-tuning of the final layers with a lower learning rate.

Data augmentation techniques included:

- Horizontal flipping
- Rotation
- Zoom

## Results

The final model achieved approximately:

- **Validation Accuracy:** 99.96%
- **Test Accuracy:** 98.90%

## Technologies

- Python
- TensorFlow
- Keras
- EfficientNetV2S
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure

    Image-Classification-EfficientNetV2S/
    ├── notebooks/
    │   └── image_classification_efficientnetv2s.ipynb
    ├── README.md
    ├── requirements.txt
    └── .gitignore

## Running the Project

Install the required dependencies with:

    pip install -r requirements.txt

Then open:

    notebooks/image_classification_efficientnetv2s.ipynb

The Fruits-360 dataset must be downloaded separately and the dataset paths configured according to the local environment.

## Authors

Developed as part of the Artificial Intelligence course at **IPVC - Escola Superior de Tecnologia e Gestão**.

- Ivo Ramoa
- Diogo Fontes
