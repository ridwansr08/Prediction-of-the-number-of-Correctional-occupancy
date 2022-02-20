# Prediction-of-the-number-of-Correctional-occupancy
Prediction of the number of Correctional occupancy in Indonesia from 2012 to 2021

## Introduction
This is the Repository about Prediction of the number of Correctional occupancy in Indonesia. To illustrate how much is the number of correctional occupancy for the next 6 months without any policy

## Technicak
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
