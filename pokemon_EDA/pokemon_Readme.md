# Pokémon EDA and Feature Engineering

## Overview

This project performs Exploratory Data Analysis (EDA) on a Pokémon dataset and prepares the data for Machine Learning.

The notebook includes:

- Data Cleaning
- Handling inconsistent values
- Feature Engineering
- One-Hot Encoding of Pokémon Types
- Statistical Analysis
- Correlation Analysis
- Visualization
- ML-ready Dataset Preparation

---

## Dataset

The dataset contains Pokémon attributes including:

- HP
- Attack
- Defense
- Special Attack
- Special Defense
- Speed
- Type1
- Type2
- Legendary Status

---

## Data Cleaning

Performed:

- Removed unnecessary columns
- Fixed incorrect values
- Standardized Pokémon types
- Converted categorical values into machine-learning friendly features

---

## Feature Engineering

Created binary type columns:

- Grass
- Fire
- Water
- Electric
- Dragon
- Fairy
- Steel
- etc.

Example:

| Pokemon | Fire | Water | Dragon |
|----------|----------|----------|----------|
| Charizard | 1 | 0 | 0 |
| Gyarados | 0 | 1 | 0 |

---

## Key Findings

### Legendary Pokémon

- Legendary Pokémon have significantly higher Total Stats.
- Median Total Stats are substantially larger than non-legendary Pokémon.

### Strongest Types

- Dragon type shows the highest median Total Stats.
- Steel and Psychic types also perform strongly.

### Weakest Types

- Bug and Normal Pokémon generally have lower Total Stats.

### Correlations

- Attack, Defense, Speed and Special Stats positively correlate with Total Stats.
- Total Stats increase consistently across stronger Pokémon.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Future Work

- Build classification model for Legendary prediction
- Predict Total Stats using Regression
- Perform clustering of Pokémon based on battle attributes
