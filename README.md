# Neural Network For MNIST Handwritten Digit Classification

## Objective
Build and train a neural network using TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

## Dataset
**MNIST Dataset**  
- 70,000 images of handwritten digits (0–9)  
- 28x28 pixels, grayscale  
- Training set: 60,000 images  
- Test set: 10,000 images  
- Built-in dataset in Keras: `tensorflow.keras.datasets.mnist`

## Steps
1. **Import Libraries** – Load required packages and modules.  
2. **Load Dataset** – Load MNIST dataset using Keras.  
3. **Preprocess Data** – Normalize pixel values and convert labels to one-hot encoding.  
4. **Build Neural Network** – Define a Sequential model with hidden layers, activation functions, and Dropout for regularization.  
5. **Train Model** – Fit the model with training data, optionally using EarlyStopping.  
6. **Visualize Training History** – Plot loss and accuracy curves for training and validation sets with consistent theme.  
7. **Evaluate on Test Data** – Compute test loss, accuracy, and display classification metrics.  
8. **Confusion Matrix** – Display confusion matrix for predictions.  
9. **Classification Report for Test Predictions** – Display precision, recall, F1-score, and support for each class 
10. **Visualize Misclassified Images** –  Plot examples of test images that were misclassified, showing both the true label and predicted label

## Features
- Fully connected neural network with one or more hidden layers  
- ReLU activation functions and Dropout layers  
- visualizations
- Evaluation metrics include accuracy, precision, recall, F1-score, and confusion matrix  

## How to Run
1. Clone the repository.  
2. Install dependencies:
     pip install -r requirements.txt
3. Open the Notebook and run all cells sequentially.

