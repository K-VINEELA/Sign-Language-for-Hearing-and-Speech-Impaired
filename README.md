# Sign-Language-for-Hearing-and-Speech-Impaired



## Overview

This project presents a real-time hand gesture recognition system developed to assist individuals with hearing and speech impairments. It uses image processing and machine learning to recognize and classify American Sign Language (ASL) alphabets and gestures. The system integrates a Node.js web app with a trained deep learning model to enable real-time webcam-based gesture detection.

## Problem Statement

Communication is a basic human need, and for individuals who are deaf or mute, expressing thoughts can be challenging. While sign language bridges part of the gap, it is not universally understood. This project aims to solve that problem through a system that captures and interprets sign language in real time.

## Key Features

Real-time gesture recognition using webcam input.

Classification of ASL alphabets and common gestures.

Web-based deployment using Node.js.

High model accuracy using CNN, ANN, LSTM, Random Forest, and XGBoost.

## Technologies Used

Programming: Python, JavaScript.

Libraries/Frameworks: OpenCV, TensorFlow, Keras, Pandas, Power Query.

Machine Learning Models: CNN, ANN, LSTM, Random Forest, XGBoost.

Deployment: Node.js web application.

## Methodology

Image Processing,

Captured hand gesture images using webcam.

Applied HSV masking and grayscale conversion.

Resized to 28x28 and normalized before storing in CSV format.

## Model Creation

CNN used as the core model for image classification.

Compared performance with Random Forest, XGBoost, LSTM, and ANN.

Used Keras for model building; trained on 85% of data, tested on 15%.

Real-Time Application.

Hand landmarks detected via webcam feed.

Recognized gestures converted to text and displayed in real-time.

Node.js web interface for user interaction.

## Results

Alphabet recognition accuracy: 99.3%.

Gesture classification accuracy: 99.2%.

Lower false positives than traditional approaches.

## Sample Output

Displays recognized gesture text on screen through a real-time webcam feed.

## Dataset

Self-collected dataset using webcam.

Includes ASL alphabets A-Z and common gestures like "Hello", "Thank you", "Eat", "Goodbye".

Preprocessed images saved as grayscale CSV data.

## Future Enhancements

Extend model to continuous sign language recognition (CSLR).

Integrate text-to-speech support for better accessibility.

Add support for digits and more regional sign languages.


## Clone the repository

Install dependencies using requirements.txt.

Train model or load pretrained weights.

Launch Node.js web app.

Use webcam to test gesture recognition.

## Authors

Vineela Kunisetti – vineelakunisetti9@gmail.com

Mounika Lingala

Sathya Bama Krishna R (Advisor)

Prince Mary S (Advisor)
