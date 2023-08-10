# Human_Activities_Detection_DL
- The code begins by capturing an image using the webcam. This can be done using the function provided by Google Colab. The image is stored in a variable.

- The captured image is then passed through a CNN model for classification. The CNN model has been trained to classify images into two categories: "human" or "wall."

- The model performs a forward pass on the captured image, applying a series of convolutional and pooling layers to extract relevant features from the image.

- The extracted features are then fed into fully connected layers, which further process the features and make a prediction about the presence of a human or a wall in the image.

- The model generates a prediction output, indicating the class label it assigns to the image. For example, if the output is "human," it means the model predicts that a human is present in the image. If the output is "wall," it means the model predicts that there is a wall in the image.

- Finally, the code can display the image along with the predicted class label, indicating whether it detected a human or a wall.
