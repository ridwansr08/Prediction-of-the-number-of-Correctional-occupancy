# Prediction-of-the-number-of-Correctional-occupancy
Prediction of the Number of Occupancy of Prisons in Indonesia from 2012 to 2021 Using Time Series and Forecast Algorithms

## Introduction
This is the Repository about Prediction of the number of Correctional occupancy in Indonesia. To illustrate how much is the number of correctional occupancy for the next 6 months without any policy

## Disclaimer
Data on JUMLAH HUNIAN.xlsx can be retrieved on the website http://sdppublik.ditjenpas.go.id/analisis/public/grl/bulanan. by taking the total data on prisoners and convicts every month from the beginning of 2012 to the end of 2021

## Technical
Language: R (code is written in Rmd file)
Libraries:
* dplyr
* forecast
* echarts4r
* readxl

## Dataset
The dataset columns is in Indonesian, and I'm not changing column names. So here's the translation:
- BULAN = Month
- TAHANAN = Prisoners
- NAPI = Convicts
- JUMLAH HUNIAN = Total

Data on the Capacity of Prisons and Detention Centers in Indonesia as of December 31, 2021 is 132,107

## Steps
1. Take data on the number of prisoner and make a line graph
2. Make predictions of prisoner data, calculate accuracy and enter into line graphs
3. Make prediction data on the number of prisoners into a dataframe
4. Take data on the number of Convict and make a line graph
5. Make predictions of Convict data, calculate accuracy and enter into line graphs
6. Make prediction data on the number of prisoners into a dataframe
7. Create Month Dataframe
8. Merge Data Using cbind & rbind
9. Create interactive charts using echart

## Insight
The Indonesian government, especially the Ministry of Law and Human Rights : 
1. must immediately make new policies, or change existing policies to reduce the number of convicts and detainees.
2. Creating a new prison. but very expensive, Estimated around 100 billion rupiah for 1000 people

Because, as of December 31, 2021, the total capacity of prisons/detention centers in Indonesia is 132,107
with data December 31, 2021, Overcapacity is 107,74%
with data Predict June 2022, Overcapacity is 114.67%

What will happen if an overcapacity prison occurs?
1. It is difficult to carry out coaching in prisons
2. Worried about infectious diseases
3. It is easy to disturb order in prisons
