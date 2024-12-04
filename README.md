# User Authentication Using Motion Data

This repository contains the implementation of a user authentication system using motion data. The project leverages the **HMOG dataset** and includes tools for data preprocessing, oversampling, ETL (Extract, Transform, Load), and data slicing, alongside model training to build and evaluate authentication systems.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Usage](#usage)
5. [Installation](#installation)
6. [Future Work](#future-work)
7. [License](#license)

---

## Overview

The project focuses on developing a **biometric user authentication system** using motion and touch data from mobile devices. The HMOG dataset serves as the foundation for this work, capturing human motion and gesture patterns during interactions with mobile devices. 

Key highlights of this repository include:
- A suite of Python utilities for handling and processing the HMOG dataset.
- Data preprocessing and augmentation to handle challenges like imbalanced samples.
- A Jupyter Notebook for splitting data into training and testing sets, and training machine learning models.

---

## Features

### Python Utilities
This repository provides several utility functions for data preprocessing and transformation:
1. **`overSampling()`**: 
   - Balances touch gesture samples by replicating logs through oversampling.
   - Handles inconsistencies in the length of motion and touch data across sessions and users.

2. **`ETLHelper()`**: 
   - A helper function to facilitate the Extract-Transform-Load (ETL) pipeline for preprocessing raw HMOG data.

3. **`ETL()`**: 
   - A complete ETL implementation for extracting, cleaning, and loading the data for further analysis.

4. **`dataGenerator()`**: 
   - Automates data batching and generation for training machine learning models.

5. **`slice()`**: 
   - Splits data into overlapping slices for efficient feature extraction and model training.

### Jupyter Notebook
- **Data Splitting and Model Training**:
  - Includes procedures to split the HMOG dataset into training and test sets.
  - Implements machine learning models for user authentication.
  - Provides model evaluation metrics to assess performance.

---

## Project Structure

