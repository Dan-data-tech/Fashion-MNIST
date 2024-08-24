# Fashion MNIST Classification

## Project Overview
This project involves building and evaluating machine learning models to classify images from the Fashion MNIST dataset. The Fashion MNIST dataset is a collection of grayscale images of 28x28 pixels, each representing a different type of clothing or accessory. The goal is to create a model that can accurately classify these images into one of the ten predefined categories

## Dataset
+ **Dataset Name:** Fashion MNIST\
+ **Description:** The dataset contains 70,000 grayscale images in 10 categories, with 7,000 images per category. The training set has 60,000 images, while the test set contains 10,000 images.\
+ **Categories:**\
 1- T-shirt/top\
 2- Trouser\
 3- Pullover\
 4- Dress\
 5- Coat\
 6- Sandal\
 7- Shirt\
 8- Sneaker\
 9- Bag\
 10- Ankle boot

## Analysis Steps
**Data Exploration:**

+ Visualize sample images from the dataset to understand the categories and the grayscale intensity distribution.
+ Perform basic statistical analysis of the image data.

**Data Preprocessing:**

+ Normalize the pixel values to fall between 0 and 1.
+ Split the dataset into training, validation, and test sets.

**Modeling:**

+ Build several machine learning models including:
  + **Convolutional Neural Network (CNN):** The primary model due to its effectiveness in image classification tasks.
  + **Fully Connected Neural Networks:** For comparison with CNNs.
  + **Other Classifiers:** Such as SVMs and Random Forests, to compare performance.
+ Tune hyperparameters and optimize model architecture for best performance.

**Model Evaluation:**

+ Evaluate models on the test set using accuracy, confusion matrix, and classification report (precision, recall, F1-score).
+ Plot learning curves to analyze model performance over epochs.

**Visualization:**

+ Visualize model predictions on a subset of the test images.
+ Generate confusion matrices to identify categories that are often misclassified.

## Requirements
+ Python 3.x
+ **Libraries:** tensorflow, keras, pandas, numpy, matplotlib, seaborn, sklearn

## Conclusion
This project demonstrates the application of machine learning techniques, particularly deep learning with CNNs, to the problem of image classification. The Fashion MNIST dataset provides a modern and challenging alternative to the classic MNIST digit dataset, helping to showcase the effectiveness of neural networks in visual pattern recognition.

## License
This project is licensed under the MIT License.


