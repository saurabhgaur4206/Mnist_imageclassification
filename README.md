# AI Based Image Classification

## Objective
The objective of this assignment is to create a simple AI-based image classification program.
This project helps in understanding basic image processing and machine learning concepts.

## Description
In this project, I have built a simple image classification system using Python.
The program classifies handwritten digit images using a basic Convolutional Neural Network (CNN).
For this, the MNIST dataset is used, which contains images of digits from 0 to 9.

## Tools & Technologies Used
- Python
- NumPy
- TensorFlow
- Matplotlib
- Google Colab

## What the Program Does
- Loads images from the MNIST dataset
- Normalizes the image pixel values
- Trains a simple CNN model
- Predicts the digit of a sample image
- Displays the image with the predicted result

## How to Run the Program
1. Open the project in Google Colab or any Python editor.
2. Install the required libraries using `requirements.txt`.
3. Run the `main.py` file.
4. The model will train and show the prediction output.

## Short Explanation 
In this project, I created a simple AI-based image classification program using Python.
The main goal of this assignment is to understand how images can be processed and classified using machine learning.

I used the MNIST dataset, which contains grayscale images of handwritten digits from 0 to 9.
Each image is of size 28x28 pixels. First, the dataset is loaded and the images are normalized by dividing the pixel values by 255.
This step helps the model to train faster and improves performance.

After preprocessing the data, I built a simple Convolutional Neural Network (CNN) using TensorFlow.
CNN is used because it works well with image data and can automatically learn important features such as edges and shapes.
The model is trained using training data for a few epochs.

After training, the model is tested on sample images.
The program predicts the digit of a test image and displays the image along with its predicted label using Matplotlib.

This project helped me understand basic image preprocessing, CNN working, and image classification in a simple and practical way.

## Conclusion
This assignment gave me practical knowledge of image processing and basic AI concepts.
