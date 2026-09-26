# Smart Manufacturing Productivity Prediction

Machine learning project for predicting the actual productivity of garment manufacturing teams using operational and workforce-related data.

## Project Overview

Manufacturing companies need to monitor team productivity and understand the operational factors that can affect performance.

This project uses the **Productivity Prediction of Garment Employees** dataset to analyze manufacturing team performance and build a machine learning model that predicts the team's **actual productivity**.

The project focuses on operational and workforce-related factors such as the number of workers, overtime, incentives, idle time, style changes, targeted productivity, work in progress, department, and team information.

## Business Problem

Productivity in manufacturing environments can be influenced by several operational factors.

Managers may know the production target assigned to a team, but the actual productivity achieved by that team can differ due to workforce conditions, overtime, incentives, production interruptions, and other factors.

The purpose of this project is to analyze these factors and build a machine learning model that can estimate actual team productivity.

The results can also help identify which operational factors are most strongly associated with productivity.

## Project Objectives

The main objectives of this project are:

- Understand the dataset and its features
- Explore manufacturing productivity patterns
- Analyze operational and workforce-related variables
- Identify missing, unusual, or inconsistent values
- Study relationships between the input features and productivity
- Prepare the data for machine learning
- Build regression models
- Evaluate model performance
- Compare predicted productivity with actual productivity
- Identify important features affecting productivity

## Machine Learning Problem

This project is a **Regression** problem.

The model will use manufacturing and workforce-related features to predict a numerical productivity value.

### Target Variable

`actual_productivity`

The target represents the actual productivity achieved by a manufacturing team.

## Dataset

The project uses the:

**Productivity Prediction of Garment Employees Dataset**

Source: **UCI Machine Learning Repository**

The dataset contains approximately **1,197 records** collected from garment manufacturing teams.

It includes information about production targets, workforce conditions, overtime, incentives, idle time, work in progress, and actual productivity.

## Main Features

Some of the main variables included in the dataset are:

| Feature | Description |
|---|---|
| `date` | Date of the observation |
| `quarter` | Quarter of the month |
| `department` | Manufacturing department |
| `day` | Day of the week |
| `team` | Team number |
| `targeted_productivity` | Productivity target assigned to the team |
| `smv` | Standard Minute Value |
| `wip` | Work in progress |
| `over_time` | Overtime worked |
| `incentive` | Financial incentive |
| `idle_time` | Time during which production was idle |
| `idle_men` | Number of idle workers |
| `no_of_style_change` | Number of style changes |
| `no_of_workers` | Number of workers |
| `actual_productivity` | Actual productivity achieved |

## Project Workflow

The project will be developed through the following stages:

1. Problem definition
2. Dataset understanding
3. Exploratory data analysis
4. Data cleaning
5. Data preprocessing
6. Feature analysis
7. Model development
8. Model evaluation
9. Model comparison
10. Results interpretation

## Project Structure

```text
smart-manufacturing-productivity/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_preprocessing.ipynb
│   └── 04_modeling.ipynb
│
├── src/
│   ├── data/
│   ├── features/
│   └── models/
│
├── reports/
│   └── proposal.md
│
├── README.md
├── requirements.txt
└── .gitignore

## Technologies

The project will mainly use:

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub

Additional libraries may be added later as the project develops.

## Dataset Source

The dataset is available from the **UCI Machine Learning Repository**:

https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees
