# Loan Status Prediction Project

![Project Image](Loan_status_prediction.gif)

## Table of Contents

- [Overview](#overview)
- [Project Description](#project-description)
- [Features](#features)
- [Data](#data)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Overview

This project is a Loan Status Prediction system that uses a Support Vector Machine (SVM) classifier (SVC) to predict whether a loan application will be approved or denied. The project achieved an 82% accuracy rate on the test data.

## Project Description

In this project, we have implemented a loan status prediction model using the Support Vector Machine (SVM) classifier. The project involves data cleaning, exploratory data analysis (EDA), and both bivariate and multivariate analysis to prepare the data for training the model. The trained SVM model can predict the loan status of new loan applications.

## Features

- Loan status prediction using SVM classifier.
- Data cleaning and preprocessing.
- Exploratory data analysis (EDA).
- Bivariate and multivariate analysis.
- Achieved 82% accuracy on test data.

## Data

The data used for this project can be found in the `data` directory. The dataset includes information on loan applicants, such as income, credit score, loan amount, and loan status (approved or denied).

## Dependencies

The project uses the following Python libraries and packages:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

You can install these dependencies using the instructions provided in the [Installation](#installation) section.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/najirh/loan_aproval_status/tree/main


   loan-status-prediction/
│
├── data/                   # Dataset files
│
├── notebooks/              # Jupyter notebooks for data analysis
│
├── src/                    # Source code
│   ├── train_model.py      # Script to train the SVM model
│   ├── evaluate_model.py   # Script to evaluate model performance
│   ├── utils.py            # Utility functions
│
├── requirements.txt        # List of Python dependencies
│
├── README.md               # This README file

