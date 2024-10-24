# Assignment 1: Exploratory Data Analysis (EDA)

## Overview

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) of the Global Terrorism Database (GTD). The objective is to uncover underlying patterns, anomalies, trends, and insights from the data, using advanced visualization techniques implemented with D3.js in a Google Colab environment.

## Dataset

The analysis is based on the **Global Terrorism Database (GTD)**, which is an open-source database including information on terrorist events around the world from 1970 through 2019 (excluding 1993 due to data loss), maintained by the National Consortium for the Study of Terrorism and Responses to Terrorism (START) at the University of Maryland. It covers over 180,000 cases of terrorism, making it one of the most comprehensive datasets on terrorist activity globally.

### Data Attributes

The dataset includes various attributes such as:

- Year of the attack
- Month of the attack
- Day of the attack
- Country
- Region
- City
- Latitude/Longitude
- Attack type
- Target type
- Weapon type
- Number of fatalities
- Number of injuries
- and more...

## Objectives

The main objectives of this assignment are to:

- Perform data cleaning and preprocessing to facilitate effective analysis.
- Generate a series of advanced visualizations to explore the dataset from various angles using D3.js.
- Identify trends over the years concerning different types of terrorist attacks and their impacts.
- Examine the geographical distribution of attacks and explore regional differences and similarities.

## Analysis Performed

### Data Cleaning and Preprocessing

Initial data cleaning steps included handling missing values, correcting data types, and filtering the dataset for relevant analysis. This preprocessing stage was crucial for ensuring accurate and efficient analysis downstream.

### Visualizations

Several types of visualizations were implemented to explore the data deeply:

1. **Time Series Analysis**: Examining the trends in terrorism over the years.
2. **Geo-spatial Analysis**: Mapping the distribution of attacks globally to identify hotspots of terrorism.
3. **Categorical Analysis**: Using bar charts and pie charts to understand the distribution of attack types, weapons used, and target types.
4. **Interactive Scatter Plots**: To explore relationships between different quantitative attributes, such as the number of kills versus the number of wounded in different regions.

Each visualization was accompanied by a brief analysis, highlighting key insights derived from the data.

## Tools Used

- **Google Colab**: For executing Python notebooks and integrating D3.js visualizations.
- **D3.js**: For creating interactive data visualizations.
- **Pandas and NumPy**: For data manipulation and analysis.

## Conclusion

The exploratory data analysis provided significant insights into the patterns and trends of terrorist activities globally. The visualizations helped in understanding the complexity and the dynamics of terrorist events over the years. This analysis can serve as a foundation for further, more detailed studies on terrorism data.

## How to Run

1. Open the Google Colab notebook.
2. Ensure all required libraries mentioned in `requirements.txt` are installed.
3. Run each cell sequentially
