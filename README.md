# 🐱🐶 Cats vs Dogs Image Classification

This project is an image classifier that distinguishes between cats and dogs using Convolutional Neural Networks (CNNs) with TensorFlow/Keras.

## 📁 Dataset

The dataset contains images of cats and dogs:
- **train/**: Training images labeled as 'cat' or 'dog'.
- **test/**: Testing images.

The original dataset is from the [Kaggle Dogs vs. Cats competition](https://www.kaggle.com/c/dogs-vs-cats).

> **Note**: Full dataset is large and not uploaded here due to GitHub size restrictions.

## 🛠️ Project Structure

├── Image_Classification.ipynb # Jupyter Notebook containing code
├── train/ # Training images (excluded in GitHub)
├── test/ # Test images (excluded in GitHub)
├── README.md # Project description


## 🚀 Model Architecture

The model uses:
- Convolutional Layers (Conv2D)
- Pooling Layers (MaxPooling2D)
- Fully Connected Layers (Dense)
- Activation: ReLU and Softmax

### Training
- Optimizer: Adam
- Loss Function: `categorical_crossentropy`
- Validation Split: 20%
- Early Stopping used to prevent overfitting.

## 📊 Results

- Achieved high training accuracy.
- Visualization of Loss and Accuracy over epochs provided.

## ⚙️ Requirements

Install the required packages:

```bash
pip install tensorflow opencv-python matplotlib scikit-learn numpy
