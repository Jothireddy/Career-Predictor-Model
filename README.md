# Career Path Prediction Model

## Overview

This repository contains an AI-powered career path prediction model that utilizes machine learning to predict potential future job roles based on a candidate's current role and career trajectory. The model leverages a transition matrix to analyze career paths and recommend the next possible job roles. Additionally, it incorporates skill matching to improve predictions based on user-provided skills.

## Features

- **Career Transition Prediction**: Predicts the likely next job roles based on the current position using a trained transition matrix.
- **Skill Matching**: Enhances career predictions by comparing required skills for each role with the user's skill set.
- **Missing Skills Identification**: Identifies and suggests critical missing skills for a user to acquire for the predicted roles.
- **Probability-Based Recommendations**: Provides predictions with base probabilities and skill match percentages.

## Components

- **Transition Matrix**: A data structure that captures career transitions by analyzing job roles and the typical progression paths between them.
- **Career Predictor Model**: A custom-built machine learning model that predicts future job roles based on career data.
- **Skill Matching**: A component that compares the user's provided skills with the required skills for each predicted job role.

## Getting Started

### Requirements

To run this project locally, you will need the following Python packages:

- `pandas`
- `numpy`
- `networkx`
- `matplotlib`
- `pickle`
- `scikit-learn` (if applicable)
- `joblib` (if applicable)

You can install the required packages using:

