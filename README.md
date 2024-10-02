# Navigating Climate Change with Machine Learning

Applying both unsupervised (dendrograms) and supervised machine learning algorithms (CNN, RNN, Random Forest) alongside principal component analysis (PCA) and hyperparameter optimization to develop a comprehensive forecasting strategy for ClimateWins.

## Context

ClimateWins is a nonprofit organization interested in addressing the challenges posed by climate change, particularly the increase in extreme weather events across mainland Europe in the last 10 to 20 years.
ClimateWins believes that advanced tools, such as machine learning, could be pivotal in predicting and preparing for such weather extremes.
By leveraging weather data from the past century, ClimateWins hopes to develop a predictive model that could offer insights into future weather patterns.

Key objectives:
- Identify weather patterns outside the regional norm in Europe.
- Determine if unusual weather patterns are increasing.
- Generate possibilities for future weather conditions over the next 25 to 50 years based on current trends.
- Determine the safest places for people to live in Europe over the next 25 to 50 years.

## Data Source

The [data set](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv) is based on 
weather observations from 18 different weather stations across Europe, which contain data ranging from 1960 to 2022.
Recordings exist almost daily with values such as temperature, wind speed, snow, global radiation, and more.
This data is collected by the [European Climate Assessment & Data Set project](https://www.ecad.eu/).
An [additional data set](https://images.careerfoundry.com/public/courses/da-spec-ml/Scripts/A1/Dataset-Answers-Weather_Prediction_Pleasant_Weather.csv) was employed
to train the ML models. This data set categorizes each day as either 1 or 0, indicating whether the weather was considered pleasant or not.
Moreover, a dataset consisting of images representing four weather categories—cloudy, rain, sunshine, and sunrise—was used to train a visual weather recognition model. 

## Approach

The task involved developing three thought experiments using a combination of different ML algorithms to devise a model that ClimateWins could implement to reach its goals.

## Project Folder Structure

The project files are organized into the following folders:
- **01 Project Management:** includes the Project Brief.
- **02 Data:** divided into two subfolders:
  1. Original Data: unscaled weather data + pleasant weather prediction data
  2. Prepared Data: scaled weather data
  ------ OMITTED FROM THE REPOSITORY FOR SPACE-SAVING PURPOSES ------
- **03 Scripts #1:** contains Jupyter notebooks documenting the first phase of the project (predicting "pleasant" weather conditions on a specific day).
- **03 Scripts #2:** contains Jupyter notebooks documenting the current phase of the project.
- **04 Analysis/Visualizations:** holds relevant visuals.
- **05 Sent to Client:** contains pdf presentations to ClimateWins stakeholders.
