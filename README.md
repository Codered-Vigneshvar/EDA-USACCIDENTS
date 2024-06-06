# US Accidents Exploratory Data Analysis

This project involves an in-depth Exploratory Data Analysis (EDA) of the US-Accidents dataset, focusing on uncovering patterns and insights related to traffic accidents in the United States.
[click here](Us_accidents.ipynb)
------------------------------------
[Download Dataset]([Us_accidents.ipynb](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents))


## Table of Contents

- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Analysis](#exploratory-analysis)
- [Results and Insights](#results-and-insights)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)

## Introduction

In this project, we perform an exploratory data analysis on the US-Accidents dataset. The primary goal is to answer key questions and identify trends related to the frequency, timing, and geographical distribution of traffic accidents.

## Data Overview

The dataset contains information on over 7.7 million accidents in the US, with 46 columns including:

- ID
- Source
- Severity
- Start_Time
- End_Time
- Start_Lat
- Start_Lng
- End_Lat
- End_Lng
- Distance(mi)
- Description
- Street
- City
- County
- State
- Zipcode
- Country
- Timezone
- Airport_Code
- Weather_Timestamp
- Temperature(F)
- Wind_Chill(F)
- Humidity(%)
- Pressure(in)
- Visibility(mi)
- Wind_Direction
- Wind_Speed(mph)
- Precipitation(in)
- Weather_Condition
- Amenity
- Bump
- Crossing
- Give_Way
- Junction
- No_Exit
- Railway
- Roundabout
- Station
- Stop
- Traffic_Calming
- Traffic_Signal
- Turning_Loop
- Sunrise_Sunset
- Civil_Twilight
- Nautical_Twilight
- Astronomical_Twilight

## Data Cleaning and Preparation

Steps involved in data cleaning and preparation:

1. Importing necessary libraries (Pandas, NumPy, Matplotlib)
2. Reading the dataset using Pandas
3. Inspecting the dataset for missing values and data types
4. Filtering and saving specific data types in separate DataFrames
5. Handling missing values and correcting data types as needed

## Exploratory Analysis

Key columns analyzed:

1. City
2. Start Time
3. Start Latitude and Longitude
4. Temperature
5. Weather Condition

### Analysis Steps:

1. **City Analysis:**
   - Count of accidents by city
   - Identifying cities with the highest number of accidents
   - Plotting the top 20 cities by number of accidents

2. **Time Analysis:**
   - Distribution of accidents over different times of the day
   - Identifying peak hours for accidents

3. **Geographical Analysis:**
   - Mapping accidents based on latitude and longitude

4. **Weather Analysis:**
   - Correlation between weather conditions and accident severity
   - Analyzing temperature and visibility during accidents

## Results and Insights

1. **City Distribution:**
   - Miami, Houston, and Los Angeles have the highest number of accidents.
   - The top 20 cities by accident count are visualized using bar charts.

2. **Time Distribution:**
   - Peak accident times are identified, indicating rush hours as high-risk periods.

3. **Geographical Insights:**
   - Visualization of accident locations on a map to identify high-risk areas.

4. **Weather Conditions:**
   - Analysis shows significant correlations between certain weather conditions and accident severity.

## Conclusion

The exploratory data analysis of the US-Accidents dataset provides valuable insights into traffic accident patterns in the US. These insights can help in developing strategies for accident prevention and improving road safety.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run

```bash
# 1. Clone the repository:
git clone https://github.com/yourusername/us-accidents-eda.git

# 2. Navigate to the project directory:
cd us-accidents-eda

# 3. Install the required dependencies:
pip install -r requirements.txt

# 4. Run the Jupyter Notebook:
jupyter notebook Us-accidents.ipynb

