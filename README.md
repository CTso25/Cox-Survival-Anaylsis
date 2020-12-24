# Classifying High Risk Patients and Projecting Hospital Length of Stay

The MIMIC-III relational database involves 40,000 patients from the critical care ward of Beth Israel Deaconess Medical Center from 2001 to 2012. Patient demographics, as well as time dependent information such as status of diseases or medical tests were used to better understand patients in ICU (Intensive Care Unit) wards. For this project, the main tables focused on included: Patients, Admissions, ICU Stays, and ChartEvents. The purpose of this project was to perform survival analysis through Cox Regression and classify patients that are at high-risk of passing away, as well as developing a model to predict a patient's length of stay in the hospital.
The results of these models are communicated through an R-Shiny application that informs hospital staff of high-risk patients, as well as potential staffing needs from projected lengths of stay.

# File Directory

* The `Big Query` folder contains Google Big Query scripts that pull data and features for EDA and feature engineering.
* The `Feature Engineering` folder contains the pre-processor to handle the data, as well as the files to create static and time-dependent features for Cox Regression and Length of Stay models respectively.
* The `Predict Length of Stay` directory holds scripts for predicting a patient's length of stay.
* `Survival Analysis` has the scripts for Cox Regression, Grid Search, and other optimizations.
* `R Shiny App` contains the R files that create the R Shiny Dashboard for hospital staff and administration.

# R-Shiny App Screenshots

![Screenshot 1](https://github.com/CTso25/Cox-Survival-Anaylsis/blob/master/R%20Shiny%20App/Screenshots/Page%201.PNG?raw=true)

![Screenshot 2](https://github.com/CTso25/Cox-Survival-Anaylsis/blob/master/R%20Shiny%20App/Screenshots/Page%202.PNG?raw=true)

![Screenshot 3](https://github.com/CTso25/Cox-Survival-Anaylsis/blob/master/R%20Shiny%20App/Screenshots/Page%203.PNG?raw=true)
