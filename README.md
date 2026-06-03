# Handwritten Digit Classification using ANN on MNIST Dataset

A fully-connected Artificial Neural Network (ANN) built with TensorFlow/Keras
to classify handwritten digits (0–9) from the MNIST dataset.

## Results
| Metric        | Value         |
|---------------|---------------|
| Test Accuracy | ~97.5%        |
| Optimizer     | Adam          |
| Epochs        | 10            |
| Dataset Size  | 70,000 images |

## Model Architecture
Input (28×28) → Flatten → Dense(128, ReLU) → Dense(10, Softmax)

## Tech Stack
Python · TensorFlow/Keras · NumPy · Matplotlib · Scikit-learn · Google Colab

## How to Run
Open the `.ipynb` in Google Colab and run all cells.
MNIST loads automatically via `keras.datasets.mnist`.

## Concepts Demonstrated
- ANN design with Dense layers
- Softmax for multi-class classification
- Adam optimizer + sparse categorical crossentropy loss
- Training/validation loss curves for performance monitoring
- Accuracy evaluation using Scikit-learn
