GettingAndCleaningData
======================

This repo focuses on using data collected from accelerometers form the Samsung Galaxy S smartphone and analysis performed by Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto at the Smartlab - Non Linear Complex Systems Laboratory in order to practice the theories of tiny data. 

====================================================
The raw data can be found here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

==================================================

This repo contains the following:

- Codebook.md - Description of variables, data, and transformations performed to clean up the data
- Tiny data set - the output of the run_analysis.R script which is a deliverable in the course project  asssignment from the Getting and Cleaning Data course
- run_analysis.R - a script which reads the files in the UCI HAR Dataset and creates a tiny data set which combines the test and train data and only includes the measurements on mean and standard deviation.