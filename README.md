# Analysis of User Preferences in IBM SkillsBuild Chatbot using Analytic Hierarchy Process (AHP)

This repository contains both Python and R implementations of the Analytic Hierarchy Process (AHP) for understanding user preferences of social characteristics features in the IBM SkillsBuild Chatbot.

## Background
The Analytic Hierarchy Process (AHP) is a structured technique for organizing and analyzing complex decisions, based on mathematics and psychology. It was developed by Thomas L. Saaty in the 1970s and has been extensively studied and refined since then.

## Project Overview
The goal of this project is to understand the relative importance of various social characteristics features of the IBM SkillsBuild Chatbot from user feedback. These features include:

* Proactivity
* Conscientiousness
* Damage control
* Thoroughness
* Emotional intelligence
* Identity
* Personality

**As the project was initially conducted in python, and then finished in R, it is advised to read the "AHP.ipynb" file first, then read "IBM_AHP.Rmd file." to understand the researcher's intend**

## Python Implementation
The initial plan was to implement the AHP in Python. The code is included in the repository. However, an issue was encountered with the Python AHP package, which prevented us from successfully conducting the analysis in Python. Details regarding this issue can be found in the Python code comments. 
As a result, data transformation is conducted in Python. 

## R Implementation
Due to issues with the Python package, the analysis was successfully carried out using R. The R implementation provides:

1. A deliberate AHP analysis of the entire dataset.
2. Visualization tools like heatmaps and boxplots to understand user preferences across various user profile categories such as age, gender, education background, familiarity with emerging technologies, frequency of chatbot usage, and overall satisfaction with the IBM Chatbot.

### Data
The data for this analysis consists of two CSV files:
1. extents.csv: Contains the main dataset.
2. user_profiles.csv: Contains the user profiles.

### Running the Code
R: To run the R code, you'll need to install the required packages (ahpsurvey, magrittr, and pheatmap). Then, run the provided R script.

## Contributions and Feedback
This code is produced by Yuqi Lou. 
