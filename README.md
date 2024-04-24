# Predicting-Breast-Cancer-Diagnoses
This is a group project with https://github.com/michelle-manfrini. The goal is to develop a model that can accurately predict an individual’s diagnosis based on the quantitative attributes.

## Project approach:
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem definition
In a statement:

> Based on a model trained on synthetic data, how well can said model predict whether or not a clinical patient have breast cancer?
> Can the model accurately predict whether an individual has breast cancer based on the provided predictors?
> Which attributes are significant in distinguishing between healthy and affected individuals?
> How well does the model perform in terms of accuracy and reliability?
> How clinically relevant and applicable is the model? Can it be used by healthcare professionals for early-stage breast cancer detection?

## 2. Data
The original data came from the Coimbra data of the UCI Machine Learning Repository. https://archive.ics.uci.edu/dataset/451/breast+cancer+coimbra

It will be used alongside a synthetic data found in Kaggle.
https://www.kaggle.com/datasets/atom1991/breast-cancer-coimbra

## 3. Evaluation
> The model will be evaluated on various metrics: accuracy, precision, recall, f1-score, confusion matrix.

## 4. Features
A list of important information regarding the features of the data.
**Create data dictionary**
Quantitative Attributes:
1. Age (years): Represents the age of individuals in the dataset.
2. BMI (kg/m²): Body Mass Index, a measure of body fat based on weight and height.
3. Glucose (mg/dL): Reflects blood glucose levels, a vital metabolic indicator.
4. Insulin (µU/mL): Indicates insulin levels, a hormone associated with glucose regulation.
5. HOMA: Homeostatic Model Assessment, a method assessing insulin resistance and beta-cell function.
6. Leptin (ng/mL): Represents leptin levels, a hormone involved in appetite and energy balance regulation.
7. Adiponectin (µg/mL): Reflects adiponectin levels, a protein associated with metabolic regulation.
8. Resistin (ng/mL): Indicates resistin levels, a protein implicated in insulin resistance.
9. MCP-1 (pg/dL): Reflects Monocyte Chemoattractant Protein-1 levels, a cytokine involved in inflammation.
10. Labels: 
    - 1: Healthy controls
    - 2: Patients with breast cancer
