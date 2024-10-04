# Sleep Health and Lifestyle Analysis

## Project Overview

This project explores the **Sleep Health and Lifestyle** dataset to analyze the relationships between various lifestyle factors and sleep health metrics. The dataset includes demographic information, lifestyle habits, and sleep health indicators, enabling insights into how different factors influence sleep quality and duration. The project employs **Exploratory Data Analysis (EDA)** to visualize trends and relationships, and **Machine Learning (ML)** techniques for clustering and classification of individuals based on their sleep health.

## Dataset Description

The dataset contains **374 rows** and **13 columns**, with the following features:

| Column Name            | Description                                                  |
|-----------------------|--------------------------------------------------------------|
| Person ID             | Unique identifier for each individual                        |
| Gender                | Gender of the individual (Male/Female)                       |
| Age                   | Age of the individual (in years)                            |
| Occupation            | Occupation of the individual                                 |
| Sleep Duration        | Average sleep duration (in hours)                           |
| Quality of Sleep      | Sleep quality rating (scale of 1-10)                        |
| Physical Activity Level| Average physical activity level (minutes per day)          |
| Stress Level          | Self-reported stress level (scale of 1-10)                  |
| BMI Category          | Body Mass Index (BMI) category (Normal, Overweight, Obese) |
| Blood Pressure        | Blood pressure reading (Systolic/Diastolic)                 |
| Heart Rate            | Resting heart rate (in beats per minute)                    |
| Daily Steps           | Average daily steps taken                                    |
| Sleep Disorder        | Any diagnosed sleep disorders (e.g., Sleep Apnea)           |

## Key Objectives

- Perform **Exploratory Data Analysis (EDA)** to uncover insights about sleep patterns and health.
- Analyze how different lifestyle factors correlate with sleep quality and duration.
- Implement clustering algorithms to identify groups of individuals with similar sleep health characteristics.
- Use classification models to predict sleep disorders based on the provided features.

## Technologies Used

- **Python**: Programming language for data analysis and machine learning
- **Pandas**: Data manipulation and analysis library
- **NumPy**: Fundamental package for numerical computations
- **Matplotlib**: Plotting library for visualizing data
- **Seaborn**: Statistical data visualization library based on Matplotlib
- **Scikit-learn**: Machine learning library for implementing clustering and classification algorithms
- **Jupyter Notebook**: Interactive environment for running the analysis and visualizations

## Installation Instructions

To run this project, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/sleep-health-lifestyle-analysis.git
    cd sleep-health-lifestyle-analysis
    ```

2. **Install the required packages**:

    It is recommended to create a virtual environment and install the required packages using `pip`. You can do this by running:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:

    Start Jupyter Notebook and open the `sleep_health_analysis.ipynb` file:

    ```bash
    jupyter notebook
    ```

## Data Exploration

The analysis begins with cleaning and preprocessing the dataset, including handling missing values and converting data types. Visualizations are created to show the distribution of sleep duration, quality of sleep, and other relevant metrics.

## Machine Learning Models

The project implements the following machine learning models:

- **Clustering**: 
  - K-Means clustering to group individuals based on their sleep health metrics and lifestyle factors.
  
- **Classification**:
  - Logistic Regression and Random Forest classifiers to predict the presence of sleep disorders based on lifestyle and health metrics.

## Results

The analysis yields insights into how various factors, such as stress levels, physical activity, and BMI, correlate with sleep health. The clustering results provide a segmentation of individuals, highlighting different sleep health profiles. The classification models help in identifying key indicators of sleep disorders.

## Conclusion

This project demonstrates the importance of understanding sleep health in relation to lifestyle factors. The findings could inform strategies for improving sleep quality through targeted lifestyle changes.
