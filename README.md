# Vaccine_Efficacy
This project presents the program and data used in the article: "Time-Dependent Vaccine Efficacy Estimation Quantified by a Mathematical Model".

Program in Python associated with the generation of vaccination scenarios in the study of estimated vaccine efficacy.

The project members are Eduardo Massad, Jorge P. Zubelli, Vinicius Albani, Francisco A. B. Coutinho, Dimas T. Covas, Claudio J. Struchiner and Jennifer Loria.

## Repository contents
There are two folders: Data and Program. 

In the Data folder we have two excels with the data used in the program: Santos and Coronavac. Santos contains the data on deaths and cases of Covid-19 from February 26, 2020 to October 16, 2020 in the city of Santos, São Paulo. These data were obtained from https://www.seade.gov.br/coronavirus/ . Coronavac contains daily numbers of individuals inoculated with the vaccine and the placebo during the CORONAVAC® trial in Brazil from August 6, 2020 to December 10, 2020. These data were provided by the Instituto Butantan for the preparation of the paper: "Time-Dependent Vaccine Efficacy Estimation Quantified by a Mathematical Model" and we have their respective authorization letter, which is also in the folder.

In the Program folder we have three programs developed in Python: Vaccine_Efficacy, Sensitivity and Graphics.


## How to use this repository

The objectives of this program are:

1. Calculate the variation of the estimated vaccine efficacy (VE) in different scenarios, using the mathematical model presented in the paper:"Time-Dependent Vaccine Efficacy Estimation Quantified by a Mathematical Model".

2. Calculate the sensitivity of the parameters involved in the mathematical model presented in the paper associated with the project, with respect to the estimated vaccine efficacy.

3. Produce the corresponding graphs that reflect the data found in Santos and Coronavac.

To meet the first objective, we use program Vaccine_Efficacy. For this, it is essential to run the first cells where the packages to be used and the description of the model are stored.The other sections of the program (Incidencia, Efficacy Graphs and Efficiency of several simulations at the same time) are independent of each other.

For the second objective we use program Sensitivity. All the cells must be run in order before the Sensitivity calculations section.

For the third objective we use program Graphics. We must have program Graphics and the Excel Coronavac and Santos documents in the same folder. The cells must be run in order.

## Contacts

* Vinicius Albani: v.albani@ufsc.br

* Jennifer Loría: jennyls@impa.br
