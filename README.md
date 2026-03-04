# Handwritten Digit Detection – PieEra

## Project Overview

Handwritten Digit Detection is a machine learning project developed under **PieEra**.
The system identifies and classifies handwritten digits (0–9) using a trained deep learning model.

This project demonstrates how computer vision and neural networks can automatically recognize handwritten numbers from images.

---

## Problem Statement

Manual recognition of handwritten digits can be time-consuming and error-prone.
The goal of this project is to build a model that can **accurately detect and classify handwritten digits** using image processing and machine learning techniques.

---

## Dataset

The model is trained using the **MNIST dataset**, which is a widely used benchmark dataset in machine learning.

Dataset characteristics:

* 70,000 grayscale images
* Image size: 28 × 28 pixels
* 10 classes (digits 0–9)

Split used in the project:

* Training data: 60,000 images
* Testing data: 10,000 images

---

## Technologies Used

* Python
* Google Colab
* NumPy
* Matplotlib
* TensorFlow / Keras
* Scikit-learn

---

## Project Workflow

1. **Data Loading**

   * Load the MNIST dataset.

2. **Data Preprocessing**

   * Normalize pixel values.
   * Reshape images for model input.

3. **Exploratory Data Analysis (EDA)**

   * Visualize sample digits.
   * Understand dataset distribution.

4. **Model Building**

   * Build a Convolutional Neural Network (CNN).

5. **Model Training**

   * Train the model on the training dataset.

6. **Model Evaluation**

   * Evaluate model performance on test data.

7. **Prediction**

   * Predict handwritten digits from input images.

---

## Model Architecture

The project uses a **Convolutional Neural Network (CNN)** which is effective for image recognition tasks.

Typical layers used:

* Convolutional Layer
* Max Pooling Layer
* Flatten Layer
* Dense Layer
* Softmax Output Layer

---

## Results

The trained model achieves **high accuracy in recognizing handwritten digits** on the MNIST test dataset.

Performance metrics include:

* Accuracy Score
* Loss Curve
* Prediction Visualization

---

## Project Structure

```
PieEra-Handwritten-Digit-Detection
│
├── Project_PieEra.ipynb
├── README.md
└── dataset
```

---

## How to Run the Project

1. Clone the repository
2. Open the notebook in **Google Colab**
3. Run all cells
4. Train the model and test predictions

---

## Future Improvements

* Deploy the model as a web application
* Add real-time handwritten digit detection
* Improve accuracy using advanced CNN architectures

---

## Conclusion

This project demonstrates how deep learning can be applied to computer vision tasks such as handwritten digit recognition.
The system provides an efficient and accurate way to classify handwritten numbers.

---

## Developed By

**Team PieEra**

CV Raman Global University,Bhubaneswar

