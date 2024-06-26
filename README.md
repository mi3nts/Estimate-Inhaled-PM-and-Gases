# Overview
This repository consists of data and code for estimating inhaled Particulate matter: PM<sub>1</sub>, PM<sub>2.5</sub> and gases: Carbon dioxide (CO2), Nitrogen dioxide (NO2) and Nitric Oxide (NO). Hyperparameters have been optimized in each of them.

The estimation of the pollutants using all the features is named as follows: 
For PM<sub>1</sub>: "PM1-all features.ipynb"\
For PM<sub>2.5</sub>: "PM2_5 new-all features.ipynb"\
For CO2: "CO2 new-all features.ipynb"\
For NO2 "NO2 new-all features.ipynb"\
For NO: "NO new-all features.ipynb"

The estimation of the pollutants using reduced number of features is named as follows: 
For PM<sub>1</sub>: "PM1-few features.ipynb"\
For PM<sub>2.5</sub>: "PM2_5-few features.ipynb"\
For CO2: "CO2-few features.ipynb"\
For NO2 "NO2-few features.ipynb"\
For NO: "NO-few features.ipynb"

The original dataset of CO2 is in: https://github.com/mi3nts/Estimate-CO2 \
The original dataset of NO2 is in: https://github.com/mi3nts/Estimate-inhaled-NO2 \
The original dataset of PM<sub>2.5</sub> is in : https://github.com/mi3nts/DUEDARE_multiple_participants 

The dataset used here are:\
For PM<sub>1</sub>: "full_df_static_2-18-23.pkl"\
For PM<sub>2.5</sub>: "static_bike_ride_pm.pkl"\
For CO2: "full_df_2021_CO2.pkl"\
For NO2 and NO "full_df_2021_NOX.pkl". Note that the data for NO2 and NO needs to be cleaned. The cleaning is done in the corresponding notebook.

The citation of the dataset or the code can be done using the following
Bibtex:
```
@misc{estimatePMandGases,
author={Ruwali,S. and Talebi, S. and Fernando, B.A.,  Lakhita W. and Waczak J. and Hathurusinghe P. and Lary D. and Sadler J. and Lary T. and Lary M. and Aker A.},
title={Quantifying Inhaled Concentrations of Particulate Matter, Carbon Dioxide, Nitrogen Dioxide, and Nitric Oxide Using Observed Biometric Responses with Machine Learning},
howpublished={https://github.com/mi3nts/Estimate-Inhaled-PM-and-Gases},
year={2024},
}
```
The PM<sub>1</sub> and NO dataset is also in Zenodo:[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10639498.svg)](https://doi.org/10.5281/zenodo.10639498)
