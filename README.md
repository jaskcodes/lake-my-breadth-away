# Lake Evaporation Dynamics Analysis

## Collaborators

Grey Xu,
Setu Loomba,
Ethan Arsht

## Project Overview

This project explores the dynamics of weather, lake evaporation and its implications on water bodies, particularly focusing on the effects of weather variables. We utilize the processed Global Lake Evaporation (GLEV) dataset to uncover various aspects including lake open areas, evaporation rates, and weather data to understand and predict the behavior of lake water bodies under different environmental conditions.

## Dataset

The GLEV dataset comprises monthly data capturing the surface areas and evaporation rates from 1.42 million lakes, including the weather data from the National Center of Environmental Information (NCEI). 
## Key Findings

- **Case Study on Lake Tahoe:** An extensive analysis of Lake Tahoe revealed significant seasonal patterns in water evaporation rates and temperature, with a notable correlation between temperature and water evaporation volume (0.846055).
- **Predictive Modeling:** The ARIMAX model, incorporating temperature and precipitation as regressors, emerged as the best model for predicting water evaporation rates, showcasing the complex interplay between weather variables and evaporation.
- **Water Body Loss and Evaporation:** A broad analysis across 100 lakes in the U.S. identified general patterns in lake size changes and evaporation rates, highlighting the utility of predictive models in understanding water body dynamics.
- **Lake Classification:** Employing hierarchical clustering, the project classifies lakes globally, offering insights into the diverse behaviors and characteristics of lakes under varying climatic conditions.

## Web Application

A web application is developed to facilitate the prediction of lake water bodies into the future, accessible at: [Lake Predictor](https://ethanapps.shinyapps.io/lake_predictor/). This tool leverages the best predictive models to offer users actionable insights into lake evaporation dynamics.
