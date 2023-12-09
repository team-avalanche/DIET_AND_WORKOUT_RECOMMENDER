# DIET_AND_WORKOUT_RECOMMENDER
# Overview
The Diet Recommendation System is a web application built using Flask that leverages the power of language models to provide personalized diet and workout recommendations based on user input. The system uses OpenAI's language model to generate recommendations for restaurants, breakfast options, dinner choices, and workout routines based on various user-specific parameters such as age, gender, weight, height, dietary preferences, health conditions, region, allergens, and preferred food type.

# Features
Personalized Recommendations: The system tailors recommendations according to the user's individual profile, taking into account a wide range of factors that influence dietary and workout choices.

Interactive Web Interface: Users can input their details through an intuitive web interface to receive customized recommendations. The application provides a seamless experience for users to interact with the system.

Error Handling: The application includes error handling to gracefully manage issues such as empty recommendation lists, ensuring a smooth user experience.

# Prerequisites
Before running the application, make sure you have the following installed:

Python 3.x
Flask
OpenAI Python SDK

# Project Structure
app.py: The main Flask application file.
templates/: Contains HTML templates for the web interface.
langchain/: Module containing classes for handling language models, prompts, and recommendation chains.
