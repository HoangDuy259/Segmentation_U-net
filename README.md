# Segmentation U-net
Image Classification: The task involves predicting the class or label of a new image based on its content and features. The goal is to determine which of the predefined classes an image belongs to. The proposed methods for this classification task include using neural networks such as Multilayer Perceptron (MLP), Convolutional Neural Network (CNN), Visual Geometry Group 16 (VGG16), Transfer Learning with VGG16, and various image preprocessing techniques for data augmentation. After training the model and evaluating it on a test dataset, the model's accuracy on the test dataset will be reported as a percentage.

Image Segmentation: This task involves dividing the pixels of an image into groups or regions based on features such as color, intensity, or boundaries. The objective is to identify and distinguish different objects or regions within the image. The proposed method for this segmentation task is to use the U-Net convolutional neural network, which is trained on labeled image datasets known as masks. After training, the model is applied to segment the test dataset, and various image preprocessing techniques are also used to enhance the model's performance. The results include predictions for real images and the percentage accuracy of the model.

Web Application: Running a web application using the Streamlit library with the U-Net convolutional neural network model built for image segmentation.

# Result


# Run
```plaintext
streamlit run app.py

