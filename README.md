# Fashion-MNIST-Data-Classification

Classification of Fashion MNIST Dataset

# Introduction

Fashion MNIST is a dataset of images consisting of clothing items, such as T-shirts, shoes, and dresses, among others. The dataset is intended for image classification tasks. It contains 60,000 training images and 10,000 testing images, each of 28x28 pixels. The task is to classify each image into one of the ten categories of clothing items.

# Approach:

The code provided above implements a Convolutional Neural Network (CNN) for image classification on the Fashion MNIST dataset. The code loads the dataset using the TensorFlow library, splits it into training, validation, and testing sets, and preprocesses the data by scaling the pixel values to the range [0,1] and expanding the dimensions of the input images to match the expected input shape of the CNN. The CNN consists of two convolutional layers with max pooling, followed by two fully connected layers, and uses the softmax activation function for multi-class classification. The model is trained for 10 epochs with a batch size of 512, using the Adam optimizer and the sparse categorical cross-entropy loss function.

# Result:

The model achieves an accuracy of approximately 90% on the testing set, indicating that it can correctly classify the majority of the images. The confusion matrix and classification report provide more detailed information about the model's performance on each category of clothing item. The classification report shows precision, recall, and F1 scores for each class, as well as overall metrics such as accuracy and macro-average F1 score. The confusion matrix provides a visual representation of the number of correct and incorrect predictions for each class.

# Heatmap:

![Classification Heatmap](https://user-images.githubusercontent.com/76581388/226109812-92e23f5b-190e-4a6d-942f-29ccc864dc29.png)
