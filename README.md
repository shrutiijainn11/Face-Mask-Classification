# Face-Mask-Classification

Title: Face Mask Classification

Problem Statement: To predict whether a person is wearing a mask or not so that it can be helpful for further actions to be taken.

Explanation: Developed a deep learning model using Convolutional Neural Network which includes the following steps:-
1. Importing dataset using kaggle json api key
2. Importing necessary libraries
3. Creating two separate directories for 'with mask' and 'without mask' classes
4. Creating lables for two classes of images
5. Image processing including:-
    1. Resizing images
    2. Converting to numpy array (for easy processing)
6. Splitting the dataset into training data and testing data (ratio= 80:20)
7. Scaling training and testing data individually
8. Building Convolutional Neural Network Model:-
    1. 2 Convlutional layers added along with Max pooling layer
    2. Followed by 2 Dense layers along with Dropout layer (to avoid overfitting)
    3. Final layer is output layer with 2 number of classes
9. Model compilation:-
    1. Optimizer = Adam
    2. Loss function = Sparse Categorical Crossentropy
    3. Evaluation metric = Accuracy
10. Model Fitting:-
    1. Validation split = 0.1
    2. Number of Epochs = 5
    3. Accuracy = 93.42%  Validation accuracy= 94.40%
    4. Loss = 1.73%  Validation loss = 2.10%
11. Model Evaluation:-
    1. Test accuracy = 92.52%
12. Plotting graphs:-
    1. Loss vs Validation loss
    2. Accuracy vs Validation accuracy
13. Building a predictive system for single imag prediction

Dataset Link: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset
