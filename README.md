# CNN Image Classification Project

## Project Overview
This project focuses on building and training a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The primary objective is to understand and implement a CNN using TensorFlow and to gain practical experience in handling image data and applying deep learning techniques.

## Environment Setup
- **Python Version**: Python 3.8 (Compatible with TensorFlow)
- **Dependencies**: TensorFlow, NumPy, Matplotlib
- **Tools Used**: Anaconda for managing virtual environments

## Installation and Running the Project
1. **Clone the Repository**:
2. **Navigate to the Project Directory**:
3. **Create and Activate Conda Environment**:
4. **Install Required Libraries**:
5. **Run the Project**:


## Project Structure
- `main.py`: The main script where the CNN model is defined, compiled, trained, and evaluated.
- `README.md`: Documentation of the project.

## Model Architecture
The CNN model for this project includes convolutional layers, pooling layers, and fully connected layers. The architecture is designed to effectively learn features from CIFAR-10 images for accurate classification.

## Dataset
The CIFAR-10 dataset, consisting of 60,000 32x32 color images in 10 classes, is used in this project. The dataset is split into training and testing sets and is directly loaded via TensorFlow.

## Results and Observations
<img width="1130" alt="Screenshot 2023-12-17 at 2 19 25 AM" src="https://github.com/ahmadsohail404/DeepLearning_CNN/assets/72069769/a9ed1bd5-91d2-4893-8c65-618030c87a2e">

- Here are the classes in the dataset, as well as 10 random images from each:
<img width="772" alt="Screenshot 2023-12-17 at 2 20 28 AM" src="https://github.com/ahmadsohail404/DeepLearning_CNN/assets/72069769/902872bd-310a-4dae-81c9-0f01622944e8">

## References
- TensorFlow Documentation: [TensorFlow](https://www.tensorflow.org/)
- CIFAR-10 Dataset Information: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)


Compared to ANN, CNN's accuracy at the conclusion of five epochs was approximately 70%, indicating a notable improvement. CNNs are the most accurate and effective at classifying images. Additionally, maxpooling preserves the features while reducing the image dimensions, requiring far less work than a simple ANN.
