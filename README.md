# Part 2: CNN Computer Vision

 Problem Statement

This project uses a Convolutional Neural Network (CNN) to classify product surface conditions into four categories:

1.dent
2.normal
3.scratch
4.stain

The goal is to automatically identify defects from images.



Task 1: Problem Identification

This dataset represents an Image Classification problem.

Reason:
Each image belongs to one category only, and the CNN model predicts which class the image belongs to.



Task 2: Dataset Exploration

Number of Classes

The dataset contains 4 classes:

1.dent
2.normal
3.scratch
4.stain

Dataset Analysis

1.Images are organized into separate folders
2.Each folder represents one class
3.Images contain product surface conditions
4.Some classes may contain more images than others



Task 3: Image Preprocessing

The following preprocessing techniques were applied:

- Resizing images to 128x128
- Normalizing pixel values
- Splitting training and validation data
- Data augmentation:
  - rotation
  - zoom
  - horizontal flip


 Task 4: CNN Model Creation

The CNN model contains:

- Convolution layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layers
- Dropout layer
- Softmax output layer


Task 5: Model Training and Evaluation

The model was trained using TensorFlow/Keras.

Evaluation methods:
- Accuracy graph
- Loss graph
- Confusion matrix
- Sample predictions


Task 6: CNN Concept Explanation

 What is Convolution?

Convolution is a process where the CNN scans small parts of an image to detect features such as edges, textures, and shapes.

Why is Pooling Used?

Pooling reduces image size and helps the model focus on important features while reducing computation.

 Why is ReLU Used?

ReLU helps the network learn faster and allows the model to learn complex patterns.

 Why are CNNs Better Than Regular Neural Networks for Images?

CNNs automatically learn image features and preserve spatial relationships between pixels, making them highly effective for image data.



Task 7: Business Use Case Mapping

This computer vision solution can be used in Manufacturing industries.

Example:
The CNN model can automatically detect dents, scratches, and stains during product quality inspection, reducing manual work and improving accuracy.



 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
