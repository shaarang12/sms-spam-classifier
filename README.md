# SMS Spam Classifier

## Table of Contents
- [Overview](#overview)
- [Demo](#demo)
- [Dataset](#dataset)
- [Machine Learning Model](#machine-learning-model)
- [Frontend](#frontend)

## Overview
This project is an SMS (text message) spam classifier built using machine learning techniques. It can help identify whether a given SMS is spam or not. In addition to the machine learning model, it also includes a frontend for easy interaction.

## Demo
(https://sms-spam-classifier-shaarangpd.streamlit.app/)(#)

![Demo GIF](demo.gif) (You can include a GIF or screenshot of the project in action)

## Dataset
The SMS spam classifier model was trained on a publicly available dataset. You can find more information and download the dataset from the following link:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset(#)

## Machine Learning Model
The machine learning model used for this project is ETC, SVC, xgb, RF, AdaBoost, NB, BgC, LR, GBDT, DT and KN. The model was trained on the provided dataset and achieved an accuracy of ~98% on the test set.

To reproduce the model, you can use the provided Jupyter Notebook in the `model` directory.

## Frontend
The frontend of the SMS spam classifier was built using Streamlit. The frontend allows users to input a text message and receive a classification result. It communicates with the machine learning model to provide real-time spam detection.

