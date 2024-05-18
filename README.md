<div style="font-family: Arial, sans-serif; color: #333; background-color: #f8f8f8; padding: 20px; border-radius: 10px;">
<h1 style="color: #007bff;">Employee Attrition Prediction and Analysis</h1>

## Overview

<p>This project aims to create a predictive model to forecast employee attrition in a large logistics company. By identifying employees at risk of leaving, the model will enable management to implement proactive strategies to retain key talent and mitigate the negative impact of attrition.</p>

## Problem Statement

The logistics company experiences an annual attrition rate of approximately 15%, leading to several issues:

1. Inefficiency
2. Higher recruitment costs and resource allocation
3. Lower productivity and effectiveness during the onboarding of new employees

## Goal

The main objective of this project is to develop a model that predicts the likelihood of employee attrition and assess feature importance to identify which factors contribute most to attrition. Additionally, the aim is to offer recommendations based on data insights to address attrition challenges effectively.

## Data

The data consists of three main datasets included in `src/` folder:

`general_data.csv`: General employee data

`employee_survey_data.csv`: Employee survey data

`manager_survey_data.csv`: Manager survey data

A detailed description of the variables can be found in the `data_dictionary.xlsx` sheet.

## Repo Structure

`src/`: Directory containing the datasets.

`requirements.txt`: File containing details of the ennvironment used.

`eda.ipynb`: Jupyter notebook for exploratory data analysis.

`main.ipynb`: Jupyter notebook containing the classification model for attrition prediction and analysis of predictor variable importance.

## Steps to Replicate Results

1. Clone the repository to your local machine.
2. Setup the environment by ensuring that Python and the required libraries are installed, as specified in the `requirements.txt` file.
3. Open and run `eda.ipynb` to perform exploratory data analysis and understand the dataset.
4. Open and run `main.ipynb` to train the classification models for attrition prediction and analyze the importance of predictor variables.
5. Review the results, including model performance metrics and variable importance, to gain insights into employee attrition.
</div>
