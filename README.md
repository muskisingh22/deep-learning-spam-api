# Deep Learning Spam Classification API

## Project Overview
This project deploys a Deep Learning based Spam Email Classification model using Flask API and Docker.

## Technologies Used
- Python
- Flask
- TensorFlow
- Keras
- Docker

## Features
- REST API for spam prediction
- Deep Learning LSTM model
- Docker containerization
- JSON response output

## API Endpoint

POST /predict

Example Request:

{
    "message": "Congratulations! You won a free iPhone"
}

Example Response:

{
    "prediction": "spam"
}

## Run Locally

Install dependencies:

pip install -r requirements.txt

Run API:

python app.py

## Docker Run

docker build -t spam-api .

docker run -p 5000:5000 spam-api

## Author
Muskan