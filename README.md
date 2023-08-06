# Analysis of User Preferences in IBM SkillsBuild Chatbot using Analytic Hierarchy Process (AHP)

This repository contains both Python and R implementations of the Analytic Hierarchy Process (AHP) for understanding user preferences of social characteristics features in the IBM SkillsBuild Chatbot.

## Acknowledgement:  
I acknowledge the use of ChatGPT (https://chat.openai.com/) to facilitate the data transformation process, which I mainly used in [AHP.ipynb]
### Description of the use of AI:
I used ChatGPT to [create the initial data transformation code, which I later edit it myself to present a cleaner look.]

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

**As the project was initially conducted in python, and then finished in R, it is advised to read the "AHP.ipynb" file first, then read "IBM_AHP.Rmd file." to understand the researcher's intentions.**

## Python Implementation
The initial plan was to implement the AHP in Python. The code is included in the repository. However, an issue was encountered with the Python AHP package, which prevented us from successfully conducting the analysis in Python. Details regarding this issue can be found in the Python code comments. 
As a result, data transformation is conducted in Python. 

## R Implementation
Due to issues with the Python package, the analysis was successfully carried out using R. Source: https://cran.r-project.org/web/packages/ahpsurvey/vignettes/my-vignette.html 
The R implementation provides:
1. A deliberate AHP analysis of the entire dataset.
2. Visualization tools like heatmaps and boxplots to understand user preferences across various user profile categories such as age, gender, education background, familiarity with emerging technologies, frequency of chatbot usage, and overall satisfaction with the IBM Chatbot.

### Data
The data for this analysis consists of two CSV files:
1. extents.csv: Contains the main dataset.
2. user_profiles.csv: Contains the user profiles.

### Previewing R-Markdown file
**Issues have been encountered during previewing R-Markdown Document, therefore a PDF file is also uploaded to this repository, under the name of "IBM_AHP.pdf"**

## Contributions and Feedback
This code is produced by Yuqi Lou. 
