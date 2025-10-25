# Turkish Library Documentation Chatbot With Dialogflow

## Library Documentation System Chatbot

The project allows library users to obtain information about the library, query books, and easily access details about authors.

Our goal is to provide library users with a more modern and effective experience, while also reducing the workload of library staff.

## How to Set Up the Project?

- Connect your email account to Google Cloud and create a project
- Integrate Google Dialogflow into your project file
- Download the project files
- Integrate the Dialogflow project found in the Project_dialogflow.zip file within your project folder into the Dialogflow project you created
- Open the database_api.py file in your project folder, find the "def initialize_db" function in the code, and enter your database connection in the "Connection URI" section in the uri part. Since we used MongoDB in the project, I will explain these steps through MongoDB. Log in to your MongoDB Atlas account and create a new Cluster. Create a new database user from the Database Access menu. Click on your cluster in Atlas, click the "Connect" button, select the "Connect your application" option, and copy the connection string specific to you. It will look like: uri = "mongodb+srv://YOUR_USERNAME:YOUR_PASSWORD@YOUR_CLUSTER_NAME.xxxxx.mongodb.net/?retryWrites=true&w=majority"
- You should also change the config class information in the moduler_library_bot.py file according to your own project
- After completing these steps, you can easily run the project

## Materials and Languages Used in the Project

- Dialogflow & Google Cloud
- MongoDB
- Python (google.cloud.dialogflow, pymongo, flask, os, uuid, datetime)
- HTML
- JavaScript

## Text File

- The text file contains sample question patterns that can be asked to the chatbot
- ![chatbot](https://github.com/user-attachments/assets/2477cf91-a425-4017-9529-1a9e1625edfa)
