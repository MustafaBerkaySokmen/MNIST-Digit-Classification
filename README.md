# MNIST Digit Classification

## Overview
The **MNIST Digit Classification** project is a deep learning model built using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The model is a Convolutional Neural Network (CNN) designed for high accuracy and efficient training.

## Features
- **Uses CNN Architecture:** Includes convolutional layers, max pooling, dropout, and fully connected layers.
- **Data Preprocessing:** Normalizes pixel values and converts labels to categorical format.
- **Training & Evaluation:** Trains the model on the MNIST dataset and evaluates accuracy.
- **TensorBoard Integration:** Enables logging for visualization and performance monitoring.

## Installation
To run this project, ensure you have **Python 3.x** installed on your system.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/mnist-digit-classification.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd mnist-digit-classification
   ```
3. **Install dependencies:**
   ```bash
   pip install tensorflow numpy
   ```
4. **Run the script:**
   ```bash
   python yapaykafa.py
   ```

## Usage
1. The script automatically downloads the **MNIST dataset** and preprocesses the images.
2. The model is trained on **60,000 training images** and tested on **10,000 test images**.
3. Training results, including loss and accuracy, are printed to the console.
4. TensorBoard logs are saved in the `logs/` directory for further analysis.

## Example Output
```
Epoch 1/10
Loss: 0.2654 - Accuracy: 92.5%
Epoch 10/10
Loss: 0.0243 - Accuracy: 99.1%
Test loss: 0.0325
Test accuracy: 98.7%
```

## Model Architecture
The CNN model consists of:
- **Convolutional Layers:** Extract spatial features.
- **Max Pooling Layers:** Reduce dimensionality.
- **Dropout Layers:** Prevent overfitting.
- **Fully Connected Layers:** Perform classification.
- **Softmax Activation:** Outputs class probabilities.

## TensorBoard Visualization
To visualize training progress:
```bash
tensorboard --logdir=logs
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.

