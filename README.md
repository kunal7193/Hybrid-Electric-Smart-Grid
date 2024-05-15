# Hybrid-Electric-Smart-Grid
Electricity as we know is the world’s most valuable energy which plays a crucial role in the way we live and travel. With the current demand for electricity and scarcity of resources, it is essential to generate electricity according to its demand and implement methods to reduce the cost of generation and emissions associated with it. This research collected and used California’s hourly electric generation data to accurately forecast demand and reduce the cost and emissions by redirecting the overproduced electricity back into the non-renewable generation methods.

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to conduct a Load forecast using Statistical and Machine Learning models to reduce the cost of electricity generation by using the overproduced electricity back in the methods of generation. 

### Methods Used
* Data transformation
* Machine Learning
* Data Visualization
* Cost Minimization


## Project Description
The electric power generation and the demand for electricity are collected from the California Independent System Operator (ISO) through their annual reports. There are a total of 5 annual reports which have data spanning from 2018 to 2022. Each Excel report has data that consists of electricity generation in 5-minute increments daily for a year from solar, wind, other renewables, nuclear, large hydro, natural gas, imports, and demand. The cost data is collected from the International Energy Agency (IEA), Energy Information Administration (EIA), California Energy Commission (CEC), and National Renewable Energy Laboratory (NREL). The generation data is aggregated to transform the 5-minute increments into hourly incremented data points. The outliers are removed using the IQR method and the valid outliers are kept in the dataset. Missing values are also removed from the dataset before conducting the ML model.

## Files

Jupyter notebook file containing the Random Forest model and the Cost minimization calculations for the transformed dataset.




