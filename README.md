<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# "Crimes in Chicago" statistically significant insights and Linear Regression
**Leonardo Cavalcante Araújo, [Vinamrata Yadav](https://github.com/vinamrata-git), [Natalia Calderón](https://github.com/NataliaRocks)**

*Data Analytics Full-Time FEB2021, Paris & March 12nd 2021*

## Content
- [Project Description](#project-description)
- [Objective](#objective)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<div style="text-align:center"><a href="https://docs.google.com/presentation/d/1HYy2y0r9RYXBZdHB-rna44OOrrhpHJox2JOGuDq41V8/edit?usp=sharing"><img src="Chicago Crimes Cover.png" alt="Chicago crimes" height="300" align="center"/></a></div>

<br>

## Project Description
Group project developed in trio, during a weekend and 2 weekdays (totalising 4 days).

## Objective
The project had **2 distinct objectives**:
1. Derive **statistically significant insights** from a database.
2. Model a **regression analysis** for a variable (in this project, we have chosen to do use the linear regression to predict the probability of a crime to happen in a given date with some given circunstances.)

## Workflow
1. **Database search and download**, finally deciding on a open source database from the [Chicago Data Portal - Crimes from 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g). The resulting database had 20 years of observations, totalising 7.5 million rows.
2. **Data Cleaning** and filtering for the past 5 years (2015-2020), resulting in a database of around 1.5 million observations.
3. **Data Analysis & Visualisations**: Using `Python`, `Matplotlib` and `Seaborn`.
4. **Hypothesis Testing**: to test statistically significant events.
5. **Linear Regression using OLS (Ordinary Least Squares)**: to predict crimes happening in a given date with known circonstances.
6. **Assumptions testing**: verification of the assumptions for the OLS model.
7. **Presentation**: slides construction and oral presentation to our Ironhack Cohort.


## Organization
- Repository "https://github.com/leo-cavalcante/crimes-in-chicago": you may find the main Python Notebooks produced by the team members to realize the analysis, visualisations and predictive models.
- *Group project.*

### Group members responsibilities
- **Leonardo**: full Data Cleaning, some data visualisations, 1 Hypothesis Test, the whole Linear Regression (using OLS), plus a big part of the Google Slides presentation.
- **Vina**: some data analysis, some data visualisations, 2 hypothesis tests and some slides in the Google Slides presentation.
- **Natalia**: research of database and some interesting insights, some data analysis and a few slides of the final presentation.

## Links
Here you may find the relevant links for the main documents produced during this project:

[Chicago Crimes - Google Slides Final Presentation](https://docs.google.com/presentation/d/1HYy2y0r9RYXBZdHB-rna44OOrrhpHJox2JOGuDq41V8/edit?usp=sharing)

[GitHub Repository: crimes-in-chicago](https://github.com/leo-cavalcante/crimes-in-chicago)

[Crimes in Chicago - Cleaning](https://github.com/leo-cavalcante/crimes-in-chicago/blob/main/Crimes%20in%20Chicago%20-%20Cleaning.ipynb)

[Crimes in Chicago - Geographical Analysis](https://github.com/leo-cavalcante/crimes-in-chicago/blob/main/Geographical%20Analysis.ipynb)

[Crimes in Chicago - Typology of Crimes and Arrests](https://github.com/leo-cavalcante/crimes-in-chicago/blob/main/Typology%20of%20crimes%20and%20arrests.ipynb)

[Crimes in Chicago - Crimes per Communities](https://github.com/leo-cavalcante/crimes-in-chicago/blob/main/Crimes%20per%20community.ipynb)

[Crimes in Chicago - Time Analysis](https://github.com/leo-cavalcante/crimes-in-chicago/blob/main/Time%20Analysis.ipynb)