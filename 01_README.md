# Star Type Prediction & Analysis

This project explores the relationship between various stellar characteristics and their classifications. By leveraging machine learning and data visualization, the project aims to identify the defining physical qualities of different star groups and prove the predictability of stellar evolution patterns.

## Project Overview
The goal of this study was to decipher the intrinsic characteristics that determine the classification of stars. Using a dataset of stellar attributes, I performed data cleaning, feature encoding, and predictive modeling to achieve a high-accuracy classification system.

## Dataset
The dataset includes the following features for various stars:
- **Absolute Temperature** (in K)
- **Relative Luminosity** (L/Lo)
- **Relative Radius** (R/Ro)
- **Absolute Magnitude** (Mv)
- **Star Color** (White, Red, Blue, etc.)
- **Spectral Class** (O, B, A, F, G, K, M)
- **Star Type** (Target: Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence, SuperGiants, HyperGiants)

*Source: [Kaggle Star Dataset](https://www.kaggle.com/datasets/deepu1109/star-dataset)*

## Methodology
1. **Data Cleaning & Encoding**: Non-numerical values (Star Color and Spectral Class) were mapped to numerical codes. Colors were simplified to follow the standard ROYGBIV spectrum.
2. **Machine Learning**: An **XGBoost classification model** was trained using temperature, luminosity, radius, magnitude, and encoded color as features.
3. **Visualization**: Visualizations were created using **Tableau** and **Google Colab** to explore relationships such as luminosity vs. radius and magnitude vs. temperature.


## Results
- **Model Accuracy**: The XGBoost model achieved **100% accuracy** in predicting star types.
- **Key Insights**: The analysis confirmed significant correlations between physical attributes and evolutionary stages, reinforcing the predictability of celestial dynamics.

## Technologies Used
- **Python**: Data processing and Machine Learning.
- **XGBoost**: Gradient boosting framework for classification.
- **Tableau**: For advanced data visualization.
- **Google Colab**: Environment for analysis and development.
