This repository contains the scripts needed for reproducing the experiment and analysis reported in Chapter 2 of my Thesis.
These resources can also be found at https://github.com/severin-lemaignan/pinsoro-kinematics-study/ which is the repository written to accompany the Frontiers article "What Can You See? Identifying Cues on Internal States from the Movements of Natural Social Interactions". 

Bartlett ME, Edmunds CER, Belpaeme T, Thill S and Lemaignan S (2019) What Can You See? Identifying Cues on Internal States From the Movements of Natural Social Interactions. Front. Robot. AI 6:49. doi: 10.3389/frobt.2019.00049

# Experiment. <br>
Contains:
  - The html experiment script
  - A python script for extracting the clips from the full videos in the PInSoRo data set
  - A list of the filenames and time-stamps for the clips used in the experiment
  - A php file for saving the data at the end of the experiment
  
For replication purposes the clips used as stimuli can be obtained from the PInSoRo data set (https://freeplay-sandbox.github.io/) using the list of filenames and time-stamps provided here. The labels assigned to each clip are also listed on this document. Start times are provided and end times for each clip are a full 30 seconds after the start time. 
  
# Analysis. <br>
Contains:
  - The analysis script
  - A script for collating the individual csv files into a single file to be used in the analysis
  - Scripts for using the krippendorff's alpha analysis and other tools (utils) which are called in the Analysis script
  
# Data/Input. <br>
Contains:
  - The collated csv file containing anonymised data from all participants
  - A csv file containing just the data from the full-scene condition
  - A csv file containing just the data from the movement-alone condition

