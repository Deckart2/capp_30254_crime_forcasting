# Model Drift and Crime Forecasting

Repo for ML Final Project CAPP 30254 Mariel Wiechers, Domingo Carbone, Gabe Morrison

Spring 2021

### Overview 

For this project, we sought to explore predictive policing and its challenges from both machine learning and public policy perspectives. While widely used, many predictive policing algorithms are flawed and racist. Through this project, we hoped to explore these dynamics and specifically consider the extent to which some algorithms could suffer from model drift as a consequence of the 2020 pandemic changing crime dynamics. 

This README is organized as follows. We first share the Executive Summary of our final research project and link to our report. We subsequently describe repo organization and general mechanics of the code. 

### Executive Summary

Predictive policing with machine learning algorithms is widely used by police departments throughout the U.S., in an attempt to determine deployment of police resources. Because of  the popularity of such approaches, it’s relevant to understand their limitations and possible negative consequences, particularly with respect to handling model drift. This paper builds models to predict the police beats with highest crime incidence in the city of Chicago for the year 2020, based on previous years’ data. It then measures model drift by comparing the chosen models’ 2020 precision and recall to those figures in earlier years.  When optimizing for precision, the models remain extremely precise, but there are substantial declines in recall, suggesting model drift occurs in the 2020 data.

### Link to Project Report: 
You can access our final report [here](https://docs.google.com/document/d/1zT_j5JFn-bzO95at9PQfqy0UbNwk49TTTVi-SU7H_qI/edit?usp=sharing). Alternatively, it is here: https://docs.google.com/document/d/1zT_j5JFn-bzO95at9PQfqy0UbNwk49TTTVi-SU7H_qI/edit?usp=sharing. 

### Repo Organization:

We organize data for the project into ```raw_data```, ```intermediate_data```, and ```final_data``` folders. ```raw_data``` contains unprocessed data that was downloaded and analyzed. ```intermediate_data``` contain processed data upon which we performed machine learning. ```final_data``` contains results from models. 


