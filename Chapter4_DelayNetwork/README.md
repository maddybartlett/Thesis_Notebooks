# Delay Network. <br>
This repository contains the scripts needed for reproducing the experiment and analysis of the Delay Network reported in Chapter 4 of my Thesis.

Note: the clips used in the experiment as well as the output data files are not made available in this repository. Instructions for generating the input data yourself are provided below.  

## Experiment. <br>
Contains:
  - The 10 html experiment scripts - 2 for each participant
  
## Analysis. <br>
Contains:
  - The analysis script (written in R)
  
## Constructing Input Data <br>
In this repository the scripts required for constructing the data sets used as input to the classifier are provided. <br> 
To construct the data sets, follow these steps:
  - First download the anonymous version of the PInSoRo data set (https://freeplay-sandbox.github.io/get-dataset)
  - Collate the individual csv files into a single csv file and delete the columns with the "yellow-child"'s coordinates
  - This new file is the equivalent of "multidata.csv" as used in these scripts
  - Use the "Create_Data" notebook in the "Experiment" folder (changing the location of multidata.csv to the location of your file on your machine) and run the script to create three new numpy files "higheng.npy", "mideng.npy" and "loweng.npy"
  - These new files are your high, intermediate and low engagement data sets respectively

# Conceptor-based Network. <br>
The Conceptor-based Network was the work of Dr. D. Hernandez-Garcia and is available in their repository at .
