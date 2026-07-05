# Nike vs Adidas Image Classifier using CNN

## Overview

This project is a Convolutional Neural Network (CNN) based image classification model developed using TensorFlow and Keras. The model classifies shoe images into two categories: **Nike** and **Adidas**.

## Features

* Image classification using a CNN
* Grayscale image preprocessing
* Image resizing to **120 × 120** pixels
* Training and prediction using TensorFlow/Keras
* Predicts whether a shoe belongs to the **Nike** or **Adidas** class

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pillow (PIL)
* Matplotlib
* Google Colab

## Dataset

The dataset contains labeled images of Nike and Adidas shoes.

Labels:

* **NIKE** → `[1, 0]`
* **ADIDAS** → `[0, 1]`

> **Note:** The dataset is not included in this repository due to its size.

## Model Architecture

* Conv2D
* Conv2D
* MaxPooling2D
* Conv2D
* Conv2D
* MaxPooling2D
* Conv2D
* Conv2D
* MaxPooling2D
* Flatten
* Dense (512 neurons)
* Output Dense Layer (2 classes)

## Training

* Image Size: **120 × 120**
* Epochs: **20**
* Optimizer: **Adam**
* Loss Function: **Categorical Crossentropy**
* Final Training Accuracy: **Approximately 96%**

## Project Structure

```text
Nike-vs-Adidas-Image-Classifier/
│── Nike_vs_Adidas_CNN_Classifier.ipynb
│── requirements.txt
│── README.md
```

## How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install the required libraries.
4. Run all notebook cells.
5. Train the model or load the saved model.
6. Test the model using your own Nike or Adidas shoe images.

## Future Improvements

* Increase the dataset size.
* Apply data augmentation.
* Use transfer learning with pretrained models such as MobileNetV2 or EfficientNet.
* Improve performance on unseen images.

## Author

**Veena Chudagund**
