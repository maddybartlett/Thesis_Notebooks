This repository contains the scripts needed for reproducing the experiment and analysis reported in Chapter 5 of my Thesis.

Note: The data sets used as input to the classifiers is not available from this repository but can be obtained by contacting the experimenter, or by obtaining the PInSoRo data set (https://freeplay-sandbox.github.io/application) and using the create data set files available in the Chapter 4 folder of this repository. 

# Experiment. <br>
Contains:
  - A script for creating the LMU pre-processed data sets and the random data set
  - The script for running the Logistic Regression
  - The script for running the MLP
  - The script for running the Nengo Deep Learning Network
  
# Analysis. <br>
Contains:
  - A script for converting the output files from each approach into a single data file for analysis
  - The script for analysing the results of gridsearches
  - The analysis script 
  
# Constructing Input Data <br>
In order to construct the raw engagement data files please follow the instructions provided in the "Chapter4_DelayNetwork" README file. 

Once you have the higheng, mideng and loweng numpy files, to create the LMU pre-processed and random data sets follow these steps:
  - Use the "Create_LMU+Random_Datasets" Notebook 
  - Make sure to change the file locations to the relevant file on your machine
  - Run the cells under the heading "Create Random Data" in order to create the random data set
  - When running the "Create LMU Pre-processed Data" cells, make sure to change the values of "q" and "theta" to the values you want
  - For replication purposes, the values used in this study were q = 2, 3 or 4, and theta = 1, 3, 5 or 7
