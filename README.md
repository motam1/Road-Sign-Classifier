# Road Sign Classifier Using Convolutional Neural Networks

## Project Overview
This project aims to develop a convolutional neural network (CNN) to accurately classify images of road signs. The model is implemented using TensorFlow and leverages various neural network parameters for optimization.

## Objectives
- Create a CNN model for traffic sign classification.
- Achieve high accuracy on the testing dataset.

## Methodology
The project involved extensive experimentation with the following neural network parameters:

- **Convolutional and Pooling Layers**: Adjusting the number and arrangement of layers to optimize feature extraction.
- **Filters**:
  - **Number of Filters**: Varying the count of filters in the convolutional layers.
  - **Filter Sizes**: Modifying the dimensions of filters to capture different levels of detail.
- **Pooling**: 
  - **Pooling Sizes**: Exploring various pooling strategies to reduce dimensionality while retaining essential features.
- **Hidden Layers**:
  - **Configuration**: Modifying the number and sizes of hidden layers to improve the model's capacity and learning ability.
- **Dropout Rates**: Implementing dropout to prevent overfitting and enhance the model's generalization.

## Training and Evaluation
The CNN was trained on a labeled dataset of traffic signs. After training, the model was evaluated on a separate testing dataset, achieving an accuracy of **93%**.

## Challenges
A significant hurdle encountered during the project was overfitting, where the model performed exceptionally well on the training data but poorly on the testing data. To mitigate this issue, I increased the dropout rates, which effectively improved the model’s generalization capabilities.

## Conclusion
This project demonstrates the effectiveness of CNNs in image classification tasks, specifically in the context of traffic sign recognition. The adjustments made throughout the process highlight the importance of hyperparameter tuning in achieving a robust model
