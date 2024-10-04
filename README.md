# Sleep Health and Lifestyle Analysis

## Project Overview

This project explores the **Sleep Health and Lifestyle** dataset to analyze the relationships between various lifestyle factors and sleep health metrics. The dataset includes demographic information, lifestyle habits, and sleep health indicators, enabling insights into how different factors influence sleep quality and duration. The project employs **Exploratory Data Analysis (EDA)** to visualize trends and relationships and **Machine Learning (ML)** techniques for clustering and classification of individuals based on their sleep health.

## About the Dataset

### Dataset Overview

The **Sleep Health and Lifestyle Dataset** comprises **400 rows** and **13 columns**, covering a wide range of variables related to sleep and daily habits. It includes details such as gender, age, occupation, sleep duration, quality of sleep, physical activity level, stress levels, BMI category, blood pressure, heart rate, daily steps, and the presence or absence of sleep disorders.

### Key Features of the Dataset

- **Comprehensive Sleep Metrics**: Explore sleep duration, quality, and factors influencing sleep patterns.
- **Lifestyle Factors**: Analyze physical activity levels, stress levels, and BMI categories.
- **Cardiovascular Health**: Examine blood pressure and heart rate measurements.
- **Sleep Disorder Analysis**: Identify the occurrence of sleep disorders such as Insomnia and Sleep Apnea.

### Dataset Columns

| Column Name            | Description                                                  |
|-----------------------|--------------------------------------------------------------|
| Person ID             | An identifier for each individual                            |
| Gender                | The gender of the person (Male/Female)                      |
| Age                   | The age of the person in years                              |
| Occupation            | The occupation or profession of the person                  |
| Sleep Duration (hours)| The number of hours the person sleeps per day               |
| Quality of Sleep      | A subjective rating of the quality of sleep (scale: 1-10)  |
| Physical Activity Level| The number of minutes the person engages in physical activity daily |
| Stress Level          | A subjective rating of the stress level (scale: 1-10)      |
| BMI Category          | The BMI category of the person (e.g., Underweight, Normal, Overweight) |
| Blood Pressure        | The blood pressure measurement (systolic/diastolic)        |
| Heart Rate            | The resting heart rate in beats per minute                  |
| Daily Steps           | The number of steps the person takes per day                |
| Sleep Disorder        | The presence or absence of a sleep disorder (None, Insomnia, Sleep Apnea) |

#### Details about the Sleep Disorder Column:

- **None**: The individual does not exhibit any specific sleep disorder.
- **Insomnia**: The individual experiences difficulty falling asleep or staying asleep, leading to inadequate or poor-quality sleep.
- **Sleep Apnea**: The individual suffers from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.

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
  - K-Means/HAC clustering to group individuals based on their sleep health metrics and lifestyle factors.
  
- **Classification**:
  - Decision Tree/KNN/SVM classifiers to predict the presence of sleep disorders based on lifestyle and health metrics.

## Results

The analysis yields insights into how various factors, such as stress levels, physical activity, and BMI, correlate with sleep health. The clustering results provide a segmentation of individuals, highlighting different sleep health profiles. The classification models help in identifying key indicators of sleep disorders.

## Conclusion

This project demonstrates the importance of understanding sleep health in relation to lifestyle factors. The findings could inform strategies for improving sleep quality through targeted lifestyle changes.
