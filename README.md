# Arabic Handwritten Character Classification using MLP

## Project Overview

This project develops a Multi-Layer Perceptron (MLP) based system for recognizing handwritten Arabic characters.

The project uses the Arabic Handwritten Characters Dataset (AHCD), which contains handwritten images belonging to 28 Arabic character classes.

## Objectives

- Explore and preprocess handwritten Arabic character images.
- Convert images into grayscale and normalize pixel values.
- Flatten 32×32 images into feature vectors.
- Train an MLP classifier for Arabic character recognition.
- Predict unseen/test character images.
- Evaluate the model using accuracy, precision, recall and F1-score.
- Generate a confusion matrix.
- Visualize correctly and incorrectly classified characters.

## Dataset

The project uses the Arabic Handwritten Characters Dataset (AHCD).

The images are grayscale handwritten Arabic character images with 28 different character classes.

## Preprocessing

The following preprocessing steps were performed:

1. Images were converted to grayscale.
2. Pixel values were normalized to the range 0–1.
3. Each 32×32 image was flattened into a 1024-element feature vector.
4. Labels were extracted from the image filenames.

## Machine Learning Model

A Multi-Layer Perceptron (MLP) classifier was trained using:

- Hidden layers: 512 and 256 neurons
- Activation function: ReLU
- Optimizer/Solver: Adam
- Maximum iterations: 50

## Results

The trained MLP model achieved approximately:

**80% classification accuracy**

The model was further evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix
- Correctly classified image visualization
- Incorrectly classified image visualization

## Project Files

- `csiproject.ipynb` — Complete Google Colab/Jupyter Notebook
- `csiproject.py` — Python source code
- `README.md` — Project documentation

## Conclusion

The results demonstrate that an MLP classifier can effectively recognize handwritten Arabic characters. Some classification errors occur because several Arabic characters have similar shapes and handwritten variations.

More advanced deep learning approaches, such as Convolutional Neural Networks (CNNs), could be used in future work to improve recognition performance.
