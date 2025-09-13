# flower-classification-api
This project demonstrates how to build, save, and deploy a simple machine learning model using Logistic Regression trained on the famous Iris dataset. The trained model is exposed through a Flask API, which allows users to send flower measurements as JSON input and receive the predicted Iris species as output.
--------------------------------------------------------------------------------------------------------------------

🔑 Key Features

Train a Logistic Regression model on the Iris dataset.

Save and load the model using joblib.

Serve predictions through a REST API built with Flask.

Test the API using Postman or any HTTP client.
------------------------------------------------------------------------------------------------------------------------

Example input:

{ "features": [5.1, 3.5, 1.4, 0.2] }

Example output:

{ "prediction": 0 }

---------------------------------------------------------------------------------------------------------

📂 Project Structure

iris-classifier-api/

│── train_model.py      # Train and save the model

│── iris_model.pkl      # Saved model

│── app.py              # Flask API

│── requirements.txt    # Dependencies
