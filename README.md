# GMIT Programming for Data Analysis
## PFDA Project 2021 - Simulation of Type 2 Diabetes Risk Factors in Ireland

This Repository was created for the project submisssion for GMIT Programming for Data Analysis Project - 2021.

### Overview
This notebook is intended to produce a sythesised dataset of risk factors for developing Type2 Diabetes across a simulated population ranging in ages from 15 to 74. The primary focus is on Ireland with much of the data used sourced from an Ireland perspective. Diabetes is a very significant, serious and costly public health issue with a number of risk factors all contributing to the current rising trends of the condition across all age groups. 

The population dataset is split into 6 age groups, 15-24, 25-34, 35-44, 45-54, 55-64, 65-74 across a simulated data set based on 1000 individuals generated from a unifrom random distribution. 4 Risk factors, Age, Physical Activity, Weight and Smoking are then applied to each individual in the dataset based on incidence levels across the age categories and associated risk factors for each. 

The final dataset produced by the program totals and summarises all of these. 

The program uses the following Python Libraries:

- Numpy
- Random functions from Numpy
- Pandas
- Matplotlib Pyplot. 
- Seaborn

If not already installed these can be easily installed for any Python instance using pip - install or preferably by installing [Anaconda](https://www.anaconda.com/products/individual) which contains all of the standard Python libraries. 

### Running the notebook. 
To run the notebook download the complete repository as a zip file and save to a local folder. All of the files needed to run are contained in the repository. A folder named Datasets holds a population file for Ireland and a number of image files used in the program. The program completes by writing the file ***RiskDataFinal.csv** to the Datasets folder. 