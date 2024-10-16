# Multiple Disease Prediction Streamlit App

This repository contains the codebase for the **Multiple Disease Prediction Streamlit App**, which predicts multiple diseases based on user inputs. The app is built using the Streamlit framework, providing an easy-to-use web interface for disease prediction models. The models are trained using datasets provided in the repository.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Model Training](#model-training)

## Overview

The **Multiple Disease Prediction App** is a machine learning-based web application that allows users to input health parameters and receive predictions for different diseases, such as diabetes, heart disease, and more. The app is developed with **Streamlit**, providing a simple and interactive web-based user interface.

The models used for prediction are trained using publicly available medical datasets, which are included in the repository. Training notebooks are provided to show the process of data preparation, model training, and evaluation.

## Features

- **Disease Prediction:** Predicts multiple diseases such as diabetes, heart disease, etc.
- **User Input Form:** Accepts input parameters from the user for prediction.
- **Interactive Web Interface:** Built with Streamlit for a seamless user experience.
- **Pre-Trained Models:** Uses machine learning models trained on medical datasets.

## Installation

To run this app locally, follow the steps below:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/multiple-disease-prediction-streamlit-app.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd multiple-disease-prediction-streamlit-app
    ```

3. **Install the required dependencies**:
    Run the command below to install all necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:
    Start the app by running the following command:
    ```bash
    streamlit run app.py
    ```

5. **Open the app**:
    The app will be hosted locally, and you can view it by opening your browser and navigating to:
    ```
    http://localhost:8501
    ```

## Usage

1. Enter the required health parameters into the input form in the app.
2. Click the **Predict** button.
3. The app will display the disease prediction results based on the input.

## Datasets

The datasets used for training the models are included in the `dataset/` folder. These datasets cover various medical conditions and contain relevant health parameters needed for prediction.

## Model Training

Training notebooks are provided in the `colab_files_to_train_models/` folder. These notebooks demonstrate the steps to preprocess the datasets, train the machine learning models, and evaluate their performance.

To train a model:
1. Open the Google Colab notebooks in the `colab_files_to_train_models/` folder.
2. Follow the instructions to run the cells and train the model.
3. After training, save the model to use in the Streamlit app.

### You can also run the app using this link : 
https://f574-35-185-3-124.ngrok-free.app/#diabetes-prediction-using-ml
