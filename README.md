# Flight Price Predictor

Welcome to the Flight Price Predictor project! This project is aimed at estimating flight fares using Machine Learning Time Series Analysis techniques. The goal is to provide users with an estimated fare for their journey based on historical flight fare data.



https://github.com/Himanshgit5458/Flight-Fare-Predictor/assets/96855684/5af413e5-9bb6-4375-8790-f72b6420002d




## Table of Contents

- [Introduction](#introduction)
- [Project Steps](#project-steps)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Model Building](#model-building)
- [UI Creation and Deployment](#ui-creation-and-deployment)

## Introduction

This Flight Price Predictor project utilizes various Machine Learning and Time Series Analysis techniques to estimate flight fares. The project covers steps from data collection to model building, resulting in a functional UI where users can input their journey details and get an estimated fare.

## Project Steps

The project can be broken down into the following major steps:

1. **Data Collection**: Over 10,000 data points for fare details from 8+ airlines were collected from multiple sources.

2. **Data Cleaning**: Multiple data cleaning pipelines were created using libraries like Pandas and others to preprocess the collected data.

3. **Model Building**: Several Time Series models were tried and tested on unseen data to identify the best model for fare prediction.

4. **UI Creation and Deployment**: A user-friendly interface was created to allow users to input journey details and receive an estimated fare. The UI was deployed for easy access.

## Data Collection

The collected data includes historical fare information for various airlines, allowing the model to learn from past trends and patterns.

## Data Cleaning

Data cleaning was a crucial step to ensure the quality and accuracy of the data used for training the models. Cleaning pipelines were designed to handle missing values, outliers, and other data inconsistencies.

## Model Building

Different Time Series models were experimented with, and the most suitable model was selected based on its performance on unseen data. The selected model provides accurate fare predictions for user journeys.

## UI Creation and Deployment

The user interface was created to allow users to input their journey details, such as departure and arrival times, source, destination, number of stops, and preferred airline. The UI communicates with the trained model to provide users with an estimated fare for their journey.

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the UI using `python app.py`.
4. Access the UI in your web browser at the provided URL.
