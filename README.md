# Plant_Diseases_Prediction
This repository contains a machine learning model for detecting plant diseases using Convolutional Neural Networks (CNN) implemented with TensorFlow and Keras libraries. The model is designed to classify images of plants into different disease categories.
Introduction:-
This project aims to develop a machine learning model capable of detecting plant diseases from images. Convolutional Neural Networks (CNN) are utilized for their effectiveness in image classification tasks. The model is implemented using TensorFlow and Keras libraries, offering a scalable and efficient solution.
Dataset:-
The dataset consists of images of plants affected by various diseases. These images are converted into their equivalent numpy arrays and normalized before being used for training, validation, and testing.
Model Architecture:-
The CNN model architecture comprises different layers tailored for image classification tasks. The specific configuration of layers and hyperparameters used in the model construction are detailed within the source code.
Training:-
The dataset is divided into training, validation, and test sets to ensure proper model evaluation. The model is trained using the training set for a specified number of epochs (e.g., 50 epochs). During training, the model's performance is monitored using the validation set to prevent overfitting.
Evaluation:-
After training, the model's accuracy is assessed using the test set. Additionally, random predictions can be generated to evaluate the model's performance on unseen data.
License:-
This project is licensed under the MIT License.
