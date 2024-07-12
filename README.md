# Sugarcane Disease Prediction

This project aims to predict diseases in sugarcane plants using a deep learning model. The model is built using TensorFlow and Keras and is trained on a dataset containing images of sugarcane plants with different disease conditions. The trained model can be used to predict the presence of diseases in new images.

## Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Getting Started](#getting-started)
4. [Usage](#usage)
5. [Web Application](#web-application)
6. [Results](#results)
7. [References](#references)

## Introduction

Sugarcane is an essential crop, and diseases can significantly impact its yield. This project addresses the issue of disease detection in sugarcane plants by employing a deep learning model. The model is trained on a dataset of sugarcane plant images, categorized into different disease classes.

## Project Structure

- **sugarcanedisease.ipynb**: Jupyter Notebook containing the code for model training and evaluation.
- **static**: Folder containing static files for the web application.
  - **styles.css**: CSS file for styling the web application.
  - **uploads**: Folder to store uploaded images for prediction.
- **templates**: Folder containing HTML templates for the web application.
  - **index.html**: Main page of the web application.
- **sgr.h5**: Pre-trained TensorFlow/Keras model for sugarcane disease prediction.
- **app.py**: Flask application script for running the web application.
- **README.md**: Project documentation.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/chyash1110/sugarcanedisease.git
   ```

2. Navigate to the project directory:

   ```bash
   cd sugarcanedisease
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Model Training

The model is trained using the `sugarcanedisease.py` Jupyter Notebook. Follow the instructions in the notebook to train and evaluate the model on the provided dataset.

### Web Application

1. Run the Flask web application:

   ```bash
   python app.py
   ```

2. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the web application.

3. Upload an image of a sugarcane plant to get predictions for disease presence.

## Results

The trained model achieves good accuracy in predicting sugarcane diseases. The web application provides an easy-to-use interface for users to upload images and receive predictions.
<img width="468" alt="image" src="https://github.com/user-attachments/assets/4669d7a4-e463-43d0-8acd-d6211d541ff9">
![image](https://github.com/user-attachments/assets/2c9a3732-5fde-4bc1-813c-ae6f322fe3f5)
![image](https://github.com/user-attachments/assets/ee27620d-bdf9-4858-9c34-27ca13c790d9)


## References

- TensorFlow: https://www.tensorflow.org/
- Flask: https://flask.palletsprojects.com/
