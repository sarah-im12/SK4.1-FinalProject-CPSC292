# SK4.1-Final Project

## Overview 
Skillcheck 4.1 includes the final project and written report. The project is based on Project 1 and includes data analysis, visualizations, and a full report including a background, analysis, results, and conclusions with a full reference. 
This project utlizes data from a CSV file and demonstrates the approval ratings from polls of the democratic party in congress overtime from 11/21/20 to 11/05/2022. The data was cleaned and transformed to demonstrate the general trends overtime. 


## Final Project RMarkdown File 
- 'FinalProject.RMD': Contains all code and data processing to produce the visualizations of the project, the full report on the project, and a full reference of all citations. 
    - To reproduce the report: Open the 'FinalProject.RMD' file       with Rstudio and knit it to the HTML format
    -Outputs (visualizations) are included in the 'results/'         folder in the directory 

## Project Structure
The SK4.1Project Repository is organized such that: 
-'SK4.1Project.Rproj' 
-'FinalProject.Rmd' 
-'data/'
-'results/'
-'doc/'


## Data 
The 'data/' folder contains datasets used in this project:
- 'generic_polllist(1).csv' "Contains raw data of public generic congressional ballot results "

## Data Sources 
- 'generic_polllist(1).csv': Contains raw data of public generic congressional ballot results provided by FiveThirtyEight. For full citation detials, refer to the References section in the final project RMD. 

## How to Reproduce the Report
1. **Clone Repository**
-Clone the repository
2. **Environment set up**
-R studio is required to run the project. 
-Open 'SK4.1Project.Rproj file' (make sure working directory is set to the main project folder) 
3. **Project set up**
-Install necessary packages of "dplyr", "tidyr", "ggplot2", "janitor". 
4. **Double check data files**
-Make sure that the CSV file is located in     data/generic_polllist(1).csv
4. **Run the Project** 
-Open 'FinalProject.RMD' file in Rstudio
-Generate the report by knitting the file in HTML or DOC format
  
