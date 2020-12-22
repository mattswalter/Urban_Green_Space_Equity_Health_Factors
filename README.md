# Equity and Health Effects of Urban Green Space in the United States

## Author: Matthew Walter

## This project was completed at the University of Delaware for the class Principles of Urban Science, instructed by Dr. Federica Bianco.


The Notebook Data_Preparation cleans and combines socioeconomic, NDVI, environemntal, and health data

The Notebook Urban_Green_Space_Equity_Health_Factors runs all the random forest regression models.

Model 1: Predict NDVI in each census tract with socioeconomic variables, latitude and longitude, and environenmental variables

Model 2: Predict each health factor with socioeconomic variables and NDVI

Model 3: Predict each health factor with socioeconomic variables and NDVI with four models, each with a different income level. First with income <= 25%, second with income 26-50%, third with income 51-75%, fourth with income >= 76%

Abstract: Urban green spaces (UGS) are areas of vegetation within city centers that have been shown to have many health benefits and be essential to public health within cities. This project will use a normalized difference vegetation index (NDVI) to represent UGS and socioeconomic variables with a random forest regression model to understand how equitably UGS are spread across the United States. Socioeconomic variables and NDVI will also be used to predict health factors in cities such as diabetes, blood pressure, and heart disease.


Data Dictionary:

pdensity = population density

a_dens = density of asian americans

b_dens = density of black americans

w_dens = density of white americans

income = average household income

age = average age

temp = average temperature (K)

precip = total yearly precipitation (m)

Arthritis: Percentage of population with arthritis

Binge_Drinking: Percentage of population who binge drinks

Blood_Pressure: Percentage of population with high blood pressure

Cancer: Percentage of the population with cancer

Heart_Disease: Percentage of the population with coronary heart disease

Pulmonary_Disease: Percentage of the population with chronic pulmonary diease

Diabetes: Percentage of the population with diabetes

Sleep: Percentage of the population getting less than 7 hours of sleep

Stroke: Percentage of the population experiencing strokes

Obesity: Percentage of the population with obesity

Smoking: Percentage of the population who smokes cigarettes


