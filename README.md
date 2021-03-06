# SIR-model
This is a model for forecasting new confirmed covid-19 cases in Thailand by public data.
## Overview
This study was inspired by a paper named A Time-dependent SIR model for COVID-19 with Undetectable Infected Persons.
I chose this model instead of using the SEIR model or other models related to vaccinated cases because people in Thailand are vaccinated only 15.5% (10/08/2021). I also consider the vaccinated as Susceptible because the vaccine can't cover the infection. That's why we consider as the only a 3-state deterministic model (SIR model)
<br>
## dataset and scope
my dataset was fetched from https://covid19.th-stat.com/ 's api <br>
I use the model to predict new confirmed cases on 17, 24 and 31 August 2021
## for further reading
<a href='https://arxiv.org/abs/2003.00122'>A Time-dependent SIR model for COVID-19 with Undetectable Infected Persons</a>
