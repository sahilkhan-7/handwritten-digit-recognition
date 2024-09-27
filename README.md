# 🖋️ Handwritten Digit Recognition with CNN
This project showcases a Convolutional Neural Network (CNN) model built for recognizing handwritten digits using the MNIST dataset. With an accuracy of over 99.2%, this model can identify digits (0-9) from grayscale images and provides real-time predictions using an interactive interface powered by Gradio.

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)

## 📖 About the Project

This project was developed as part of my internship at **Zidio Development**. The aim was to build a neural network model that recognizes handwritten digits from the **MNIST dataset** with over 97.5% accuracy. A Gradio interface was implemented to allow users to interact with the model by drawing digits on a canvas and receiving real-time predictions.

## 🚀 Technologies Used

- **Python 3.11.8**
- **TensorFlow/Keras** for building and training the deep learning model
- **OpenCV** for image preprocessing
- **Gradio (v2.3.5)** for creating the user interface
- **NumPy** for handling arrays
- **Pandas** for data manipulation

## 🧠 Model Architecture

The CNN model consists of three convolutional layers followed by a dense layer and an output layer with softmax activation. Below is a detailed breakdown:

- **Input Layer:** Accepts 28x28 grayscale images with one channel.
- **Conv2D Layer 1:** 32 filters, (3x3) kernel size, ReLU activation, MaxPooling.
- **Conv2D Layer 2:** 64 filters, (3x3) kernel size, ReLU activation, MaxPooling.
- **Conv2D Layer 3:** 64 filters, (3x3) kernel size, ReLU activation.
- **Fully Connected Dense Layer:** 64 units, ReLU activation.
- **Output Layer:** 10 units, softmax activation for digit classification.

The model was compiled using **categorical cross-entropy** loss and the **Adam optimizer**, achieving a training accuracy of over 99.2%.


## ▶️ Usage
Once the app is running, you'll be able to:

- Draw a digit (0-9) using the sketchpad in the Gradio interface.
Click "Submit" to see the predicted digit displayed.


## 📊 Results

The model achieved an impressive **99.2% accuracy** on the MNIST test dataset. Below are some sample results from the model:

https://github.com/user-attachments/assets/35f43654-c931-405b-b7a4-2f1a9c532185




## 🔧 Future Improvements
Add additional data augmentation techniques for improved model generalization.
Extend the model for multi-digit recognition.
Implement a web deployment with services like Flask or Streamlit.

## 🙏 Acknowledgments
Special thanks to Zidio Development for the opportunity to develop this project during my internship.
The MNIST dataset is provided by Yann LeCun and collaborators.
