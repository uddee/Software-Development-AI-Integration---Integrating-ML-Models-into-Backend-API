# Software Development & AI Integration - Integrating ML Models into Backend API

## Overview

This project demonstrates how to integrate a machine learning (ML) model into a backend **Flask API**. The goal is to build a simple **API** that takes user input, processes it with a **trained machine learning model**, and returns a prediction. The **Linear Regression** model is trained using sample data, saved using **pickle**, and used in the API to make real-time predictions.

## Features

- **Flask API**: Provides a `POST` endpoint to make predictions using the trained ML model.
- **Machine Learning Integration**: The project includes the training of a simple Linear Regression model, which is then serialized and used to make predictions.
- **Model Serialization**: The trained model is saved to disk using **pickle** for later use.
- **Prediction Handling**: The API accepts input features, processes them through the trained model, and returns the predicted result.

## Technologies Used

- **Flask**: Web framework to build the API.
- **scikit-learn**: Library used for building and training the machine learning model.
- **pandas**: Data manipulation library to prepare the training data.
- **pickle**: A Python module used to serialize the machine learning model.
- **numpy**: Library used to handle numerical data.

## Setup and Installation

### Requirements

- Python 3.7 or higher
- Pip (for installing dependencies)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/integrating-ml-model-into-api.git
cd integrating-ml-model-into-api
