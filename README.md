# Investigate-a-Dataset
Udacity Data Analyst Degree - Project III

## Overview
The goal of this project is to investigate a dataset of appointment records for Brasil public hospitals. The data includes some attributes of patients and states if the patients showed up to appointments. The analysis should be focused on finding trends influencing patients to show or not show up to appointments.

The original problem description and data set can be found here: https://www.kaggle.com/joniarroba/noshowappointments/home

## What Software Do I Need?

To complete this project, I will be using Python plus the following libraries:

- Pandas and NumPy (speeds up data analysis code)
- Matplotlib (produce plots)

## Asking Questions

I chose to investigate the following questions from the dataset:

1 - What is the rating for No-Show gender patients?

2 - What is age rating of Alcoholism for the patient they show?

## Data Wrangling

In this part, I fine-tuned the existing dataset by:

1) Deleting unnecessary columns
2) Dropping duplicated rows
3) Tweaking illogical values

## Conclusions


Conclusions I have looked into the dataset and managed a few problems like unifying names, removing wrong data. 


- There are many very young people in the dataset (most of them of age 0) but in general the patients age is distributed evenly and the number of patients goes drastricly down for patients older than 60 years.

- The patients are 37 years on average.

- Most of the patients are not alcoholics.

- On average, 20% of appointments were missed.

- Out of 71831 appointments made by females, 14588 were missed with the ratio of 20%.
- Out of 38685 appointments made by males, 7723 were missed with the ratio of 20%.
- The charts confirm about 20% no-show rate for most categories.
-the gender or alcoholic is not a factor to decide if the person would come to his appointment 
