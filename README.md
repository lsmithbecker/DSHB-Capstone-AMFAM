# DSHB---Capstone-AMFAM
## About the Project
Welcome!
We worked on investigating the relationship between storm events and insurance prices for our Capstone Project in the Data Science in Human Behavior Masters Program at UW-Madison. We wanted to work with an external partner and we had the opportunity to work with American Family Insurance.

## About the Data
We used two main datasets, a storm events dataset sourced from the US Government, and an insurance dataset that was publicly available.
Both are accessable here [Insurance Data](https://www.iii.org/table-archive/21407), [Storm Data](https://www.ncei.noaa.gov/pub/data/swdi/stormevents/csvfiles/)

## About the Files
insurance_final -- This file was created by Liam and mainly revolves around our final analysis of the insurance data, and the combined storm events and insurance data.

timeseries_final -- This file was created by Andi and mainly revolves around the analysis of the storm events data, including regressions and statistical analysis

InsuranceData.rds -- This is an RDS file that contains all the insurance data after being loaded into R. Using this code you can load it in yourself.
```
list2env(readRDS('InsuranceData.rds'), envir = environment())
```
StormData.rds - This file is unable to be uploaded to github due to the size, it is currently hosted on google drive present [here](https://drive.google.com/drive/folders/1NFDMicIcYiGKQDGQttVJpDYl3gqOM4pT?usp=sharing). Using this code you can load it in yourself
```
list2env(readRDS('StormData.rds'), envir = environment())
```
