# Cats and Dogs Docker Classification
This project demonstrates a simple web application that predicts whether an uploaded image contains a cat or not. It uses a pretrained machine learning model (h5 format). It is deployed using Flask and containerized using docker.

# Docker Deployment
Build the Docker image: docker image build -t flask_docker .

Run the Docker container: docker run -p 5000:5000 -d flask_docker

Access the app at http://127.0.0.1:5000/upload

# Usage
Upload an image using the web form.

The app will predict whether the image contains a cat or not.

# Demo Video
https://github.com/Shreyaas-Aditya/cats_and_dogs_docker_classification/assets/150200835/a030e729-13f0-4ae9-bf3c-c7716b5abde3
  
# Model link : https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5

# Docker hub: https://hub.docker.com/r/shreyaasaditya13/flask_docker
