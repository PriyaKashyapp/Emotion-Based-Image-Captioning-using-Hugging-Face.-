# Emotion-Based-Image-Captioning-using-Hugging-Face

Leveraging Open Source Models from HuggingFace and Langchain for Generative AI

## Introduction :
The "Emotion-Based Image Captioning using Hugging Face" project aims to create an application that generates descriptive and emotion-oriented captions for images. This project leverages advanced deep learning models from Hugging Face and integrates them with a Flask-based backend to provide a web interface for users to upload images and receive captions.The system will generate captions that not only describe the content of the image but also convey the emotional context.


## Objectives : 

Develop a machine learning model to generate captions that describe the content and emotional context of images.
Create a RESTful API using Flask to handle image uploads and serve generated captions.
Build a user-friendly web interface for uploading images and displaying captions.

## Prerequisites : 

## Software Requirements:
Python 3.7+ , Flask , Hugging Face Transformers , Torch , Flask-CORS : For Security enable CORS using Flask-CORS to allow cross-origin requests

## Hardware Requirements :
Standard development machine with a good GPU for model training.

## Hugging Face Models and Libraries :

Image Captioning Model :
Salesforce/blip-image-captioning-base
( This model generates initial captions for images. ) 

Emotion Detection Model :
microsoft/resnet-50 
( This vision transformer model is used for detecting emotions in images. )


## Summary : 
model.py: Contains the logic for generating emotionally descriptive captions.
app.py: Flask application that handles image uploads and uses the function from model.py.
index.html: Vue.js frontend for uploading images and displaying the generated captions.

## Future Work : 
Enhancements: Improve the captioning model to handle more complex emotions.
Features: Add user authentication to track user history and preferences.

## References :

Flask Documentation

Hugging Face Documentation

Moesif Blog on Building RESTful API with Flask

NOTE: For reference, please check the attached integrated file which includes both the model code and Flask code under the name Module.py



