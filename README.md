# Neural-Network-Classificaiton-Project
Tomato Leaf Disease Detection using Convolutional Neural Network with Data Augmentation

Link to the IEEE paper 
https://ieeexplore.ieee.org/document/9138030


This project briefs the detection of diseases present in a tomato leaf using Convolutional Neural Networks (CNNs) which is a class under a deep neural network. As an initial step, the dataset is segregated before the detection of tomato leaves. The concept of transfer learning is used where a pre-trained model (ResNet-50) is imported and adjusted according to our classification problem. To increase the quality of the ResNet model and to enhance the result as close to the actual prevailing disease, data augmentation has been implemented. Taking all these into consideration, a tomato leaf disease detection model has been developed using PyTorch that uses deep - CNNs. Finally, the testing dataset is processed for validation based on the learned parameters from the ResNet 50 model. Six most prevailing diseases in tomato crops have been taken for classification. Data augmentation has been introduced to increase the data set to 4 times the actual data and the model has shown an accuracy of 97%.
