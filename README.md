1. Overview of the Project
Goal:
Detect the language of a given text input using a trained machine learning model.

Technologies Used:

Scikit-learn: For training the machine learning model.

FastAPI: For building a REST API to serve predictions.

Pickle: For saving and loading the trained machine learning model.

Docker: For containerizing the FastAPI app.

Heroku: For deploying the API to the cloud.


2. Workflow Overview
Build and Train the Model:

Use scikit-learn to preprocess the text data and train a Naive Bayes classifier for language detection.
Save the trained pipeline to a file using pickle.
Create the FastAPI Backend:

Develop a REST API that accepts a text input and returns the predicted language.
Deploy the API:

Use Docker to containerize the FastAPI app.
Deploy the containerized app to Heroku for public access.


Screenshots:
![Language detection GET](https://github.com/user-attachments/assets/9a33ddcd-0053-4a11-b846-8073e14c0e79)

![ML language detection POST](https://github.com/user-attachments/assets/f4c59901-a0d9-4714-8073-2dac53df93fc)



