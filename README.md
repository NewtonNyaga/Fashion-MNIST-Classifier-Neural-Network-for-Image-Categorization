# Fashion MNIST Classifier

This repository contains a convolutional neural network (CNN) model trained to classify images from the Fashion MNIST dataset into their respective categories.

## Modules Required
- Python 3
- TensorFlow
- NumPy
- Matplotlib

## How to Run
1. Clone this repository to your local machine:
   ```
   git clone https://github.com/NewtonNyaga/fashion-mnist-classifier.git
   ```
2. Navigate to the project directory:
   ```
   cd fashion-mnist-classifier
   ```
3. Run the `fashion_mnist_classifier.py` script to train and evaluate the model:
   ```
   python fashion_mnist_classifier.py
   ```
4. After training, the script will generate visualizations of training and validation accuracy and loss curves, as well as sample images with their predicted and actual labels.

## Model Architecture
The CNN model architecture consists of convolutional layers, pooling layers, and fully connected layers. The specific architecture can be found in the `fashion_mnist_classifier.py` script.

## Dataset
The Fashion MNIST dataset is used for training and evaluation. It consists of 60,000 training images and 10,000 test images, categorized into 10 types of fashion products.

## Performance
The model achieves a test accuracy of 0.9033 on the Fashion MNIST dataset.

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README with additional information or instructions specific to your project.

