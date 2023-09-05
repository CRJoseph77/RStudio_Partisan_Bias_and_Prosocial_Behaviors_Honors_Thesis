# Analyzing How Attitudes Affect the Relationship Between Partisan Bias and Prosocial Behavior
Do attitudes toward helping others or attitudes toward charitable organizations influence partisan bias in prosocial behaviors?

# Project Overview
This project features segments of my Honors Thesis project completed in the spring of 2019 at the University of Colorado, Boulder. This study examines the relationship between partisan bias and prosocial behaviors. 

Partisan bias is the tendency for people to be biased toward their own political party, and prosocial behaviors are behaviors that help others. A previous study had discovered that partisan bias did not influence prosocial behavior, which is surprising considering the pervasive effects of partisan bias. This study hypothesized that attitudes toward helping others (AHO) and attitudes toward charitable organizations (ACO) influence the relationship between partisan bias and prosocial behavior. People with different attitudes about helping others or charitable organizations might exhibit different levels of partisan bias in prosocial behaviors. 

The two primary dependent variables were how long participants persisted on an intentionally tedious task that they were instructed was for a charitable cause, and how much of the task they completed. 

The independent variables included whether a fictional sponsor organization for the task was from the same political party (co-partisan), a different political party (counter-partisan), or a control organization. AHO and ACO scores were also measured, along with other demographic information.

Data was collected from undergraduates at the University of Colorado, Boulder and analyzed in R Studio. Data was filtered into data frames with only the relevant data and then analyzed. Two-way ANOVAs were conducted to assess whether or not there were significant differences in time spent on the task or the amount of the task completed between participants in different groups of the independent variables. Linear regressions were conducted to further examine these relationships and assess to what extent independent variable conditions as well as demographic factors influenced scores on the outcome variables. T-tests were also conducted to evaluate if there was a difference in the dependent variables between the co-partisan and counter-partisan conditions.

# Installation and Setup
## Codes and Resources Used
Editor Used: Data analysis for this project was performed in R Studio.

R packages used: Psych, knitr, tidyverse.

# Data
The data used for this project was collected through the Emotion, Decision, Judgement, and Identity lab at the University of Colorado, Boulder. Unfortunately, the data belongs to the university and I no longer have access to it.

Source data: The data used for this project was collected from undergraduates at the University of Colorado, Boulder. 

Preprocessing: The data was cleaned by another member of the lab before it was uploaded to R Studio for analysis. 

# Code Structure
1. Uploading data and preparing data frames - The cleaned data was uploaded to R Studio and filtered to create data frames containing only data relevant to this project.
   
2. Data transformation - ACO and AHO scores were split into ‘high’ and ‘low’ categories based on whether they were above or below the median.
   
3. Calculating descriptive statistics - Descriptive statistics were calculated for the main dependent variables and groups of independent variables. Descriptive statistics about participant demographics were also calculated. Lastly, descriptive statistics were calculated for the dependent variables by groups of the independent variables. 

4. Creating tables - Mean tables were created for each group of independent variables (co-partisan, counter-partisan, or control and high or low ACO and AHO) on the different dependent variables. 

5. ANOVAs - Multiple two-way ANOVAs were conducted on both dependent variables (time spent on the task and amount of the task completed) to see if there were differences based on partisan condition and low/high ACO and AHO. The interaction between partisan condition and ACO/AHO level was also explored. 

6. Linear regressions - First, categorical variables were encoded to be represented numerically. Linear regression models were created to assess the effects of the different conditions as well as demographic features (such as gender) on the outcome variables. 

7. Chronbach’s alpha - Data from the ACO/AHO scales was encoded numerically and Chronbach’s alpha was calculated to evaluate the internal consistency of the ACO/AHO scales. 

8. T-tests - Data was filtered to exclude participants in the control condition. Then scores on the dependent variables were compared between participants in the co-partisan and counter-partisan condition using two-sample independent t-tests.

# Results and Evaluation
My analysis revealed that ACO and AHO scores did relate to prosocial behaviors. Furthermore, I discovered that ACO and AHO did, in fact, moderate the relationship between partisan bias and prosocial behavior. People with lower ACO/AHO scores exhibited more prosocial behavior toward counter-partisans and people with higher ACO/AHO scores exhibited similar amounts of prosocial behavior toward co-partisans as counter-partisans.

# References
A list of references for this project can be viewed [here](4._References.pdf).

