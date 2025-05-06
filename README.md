# A mixed-methods evaluation for a Community-Based mental health intervention for Black Queer Young Adults

## Authors: [Jacquelyn Chin](https://github.com/jchin333) and [Mia Forsline](https://www.linkedin.com/in/mia-forsline/)

## Project Advisor: [Dr. Tania Israel](https://taniaisrael.com/) 

## Project Dates: April 2024 - June 2025

# Background

This repository contains R Markdown files that perform preliminary data analysis for Jacquelyn Chin's dissertation proposal, titled "A mixed-methods evaluation for a Community-Based mental health intervention for Black Queer Young Adults." Black, queer young adults in California ages 18 - 25 participated in a 6 week online support group and completed weekly surveys as well as a pre-survey, post-survey, and follow-up 1 month after the intervention. The intervention (AKA the support group) took place from Feb - March, 2025. Each week, 1-3 individuals participated. Surveys were administered via Qualtrics. 


# Project Motivation and Goals

# Workflow 

Specifically, this repository contains a script (`power_test.Rmd`) to perform a power analysis, which was used to estimate how many participants would be needed to detect an effect size of 0.8. The power analysis was performed before the support group, during the planning phase of the project. 

This repository also contains `BQL_DATA.Rmd`, which analyzes the weekly survey data to summarize demographic data such as: 
- Race/Ethnicity
- Gender
- Sexual Orientation
- Relationship Status
- Education
- Employment
- Income
- Political Action

Next, we calculated the mean average scores and average scores for 8 psychology scales. 

1. PHQ-4 Anxiety & Depression Scale
2. Ryff Psychological Wellbeing Scale
3. Black Identity Development Scale
4. LGBT Positive Identity Measure
5. Short Critical Consciousness Scale and the Contemporary Critical Consciousness Measures I and II
6. Collective Self-Esteem Scale
7. Radical Hope
8. Individual-Community Related Empowerment Measure

For the PHQ-4 Anxiety & Depresion Scale, we compared participants' response scores at the pre-survey, Week 2, Week 4, Week 6, and the follow-up survey. For all other scales/measures, we compared participants' response scores at the pre-survey, post-survey, and follow-up survey. 

For surveys with multiple participants, we calculated the mean average score for each scale/measure. For surveys with only one participant, we calculated the average score for each scale/measure. 

# File Structure 



# Data

Data used in this project are proprietary to Jacquelyn Chin and stored in a private, online Box server used by Dr. Tania Israel's lab. For data access, please contact Jacquelyn Chin. 

Weekly survey results were exported from Qualtrics into Excel files. Each week was compiled into a single Excel spreadsheet with multiple tabs and read into `BQL_DATA.Rmd`. Jacquelyn Chin also used ChatGPT to create an Excel-based codebook to relate each numeric survey question response to its description. For example, a survey participant might answer Q36 as 1, which indicates a Race/Ethnicity response of African American. The codebook was read into `BQL_DATA.Rmd` to help analyze demographic data. 

# Tools

This project primarily uses R/RStudio for analysis. Microsoft Excel and Qua

