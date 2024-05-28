# My Python App

## Overview

This project demonstrates a simple machine learning application using Flask and Docker. The application trains a decision tree classifier on the Iris dataset, saves the trained model, and provides an endpoint to make predictions based on this model.

## Project Structure

- `Dockerfile`: Contains the instructions to build the Docker image.
- `requirements.txt`: Lists the Python dependencies needed for the project.
- `train_model.py`: Script to train the decision tree classifier and save the model.
- `app.py`: Flask application that loads the trained model and provides an endpoint for predictions.
- `model.pkl`: The trained model saved as a pickle file (generated after running `train_model.py`).

## Instructions to Build and Run the Docker Container

1. **Build the Docker image**:

   ```sh
   docker build -t my-python-app .
