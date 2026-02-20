# Expected Goals (xG) Model – Serie A 2015/16

## Overview
This project builds an Expected Goals (xG) model from scratch using StatsBomb open data.

The objective is to estimate the probability that a shot results in a goal and use it to evaluate offensive shot quality and team performance.

## Model
Logistic Regression using:
- Shot distance
- Shooting angle
- Body part
- Shot type
- Under pressure
- First time shot

Validation:
- Time-based split
- ROC-AUC ≈ 0.80

## Applications
- Team shot quality analysis
- Over/underperformance detection

## Data
StatsBomb Open Data:
https://github.com/statsbomb/open-data

## Tech Stack
Python, Pandas, Scikit-learn
