# chatbot-model
Course project for Metis' Intro to Data Science by analyzing how to make chatbots smarter

## Background
The purpose of this model is to measure how effective a chatbot is in answering users' questions. I intend to use this project as a first pass in analyzing the chatbot that my company is developing.

## Data
<a href="https://www.infoq.com/news/2017/04/microsoft-dataset-chatbots">Press release from InfoQ:</a>

*<a href="https://datasets.maluuba.com/">Maluuba</a>, a Microsoft company working towards general artificial intelligence, recently released a new open dialogue dataset based on booking a vacation - specifically, finding flights and a hotel.*

The <a href="https://datasets.maluuba.com/Frames/dl">dataset</a> contains 1,369 dialogues around travel planning. Each dialogue also contains two labels:
* userSurveyRating:	A value that represents the user's satisfaction with the Wizard's service, ranging from 1 - complete dissatisfaction to 5 - complete satisfaction.
* wizardSurveyTaskSuccessful:	A boolean which is true if the wizard thinks at the end of the dialogue that the user's goal was achieved.
