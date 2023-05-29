# FYP-Suha-Teachingster

This project contains the server file DPR(weights-link) and chatbot weights and document files and flask server file(link).
## pytorrch-flask-api
- Conatins the weights for models like face recognition, eyes detection, age and gender.
- Also it have the cascades in it.
- You can downlaod it from [GDRIVE](https://drive.google.com/drive/folders/1k2yaZdli4rtmhlFhYI9R4POnUyKju2vk?usp=sharing)

## DPR-Weights
- For Fine tune QA Model you can downlaod the following link [GDRIVE](https://drive.google.com/drive/folders/1P5LxpJz7YIS4aXQFzY-rzyL8-Ph5xvuU?usp=share_link)

## ChatBot Weights
- ChatBot Weights along with the intents file are provided in seprate folder ChatBotWeights.

## Prerequisites

Before running this project, ensure you have the following prerequisites:

- Python 3.x installed
- Installed all dependencies
- Enable GPU in colab


## Configuration

To successfully run this project, you need to provide the following configuration:

1. OpenWeather API Key: Obtain an API key from [OpenWeather](https://openweathermap.org/api) and add it to the project. 
```
api_key ="put-your-own-open-weather-key"
```
2. Ngrok Token: Get a token from [Ngrok](https://ngrok.com/) and add it to the project.
```
!ngrok authtoken <get-your-token>
```

3. MongoDB Atlas URI: If you are using MongoDB Atlas for your project, obtain the connection URI and add it to the project.
- Replace <connection_string> with your modified MongoDB Atlas connection string

```
client = MongoClient("mongodb+srv://<user-name>:<password>@cluster0.fz59ulb.mongodb.net/studentDb?retryWrites=true&w=majority")
```
