# CropGuard
This repository contains code for a AI driven plant disease detection chatbot. This project mainly consists of three major phases which include: 
1. Building Machine Learning models for image classification
2. Integrating machine learning models and frontend of the chatbot, along with LangChain Integration
3. Deployment of the webapp

Dataset Used : PlantVillage Dataset

## Building Machine Learning Models for Image Classification 
In this we have built trained and tested three different models, one for each plant variety (tomato , bell pepper and potato). 
This model building process involved splitting the dataset into training and test data. Perfoming data augmentation on the dataset being used to improve the accuracy of the model. We have utilized a Convolutional Neural Network model which is specialised for working with images and image classifications 

## Integrating Machine Learning And Frontend along with LangChain
This Streamlit application combines plant disease detection and conversational interactions. It offers users the choice of three TensorFlow Lite models for detecting potato, pepper, or tomato diseases. Users can upload plant leaf images for disease detection, and the detected disease is displayed. The application also features a conversational AI using OpenAI's GPT-3.5 Turbo. Users can initiate conversations, ask questions, and receive informative responses from the AI. The AI's answers are displayed in the conversation history. The application requires API keys for OpenAI and Wolfram Alpha. A note informs users that only specified diseases can be predicted. This application provides a user-friendly interface for plant disease detection and informative conversations about plant diseases and crops.

##Deployment of the WebApp

