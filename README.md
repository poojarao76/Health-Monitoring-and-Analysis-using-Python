# Health-Monitoring-and-Analysis-using-Python
Data Science Case Study on Health Monitoring and Analysis.

This repository explores health data from a dataset of 500 individuals. We'll analyze various health metrics like age, gender, heart rate, blood pressure, respiratory rate, body temperature, and oxygen saturation, recorded over a specific period.

## Introduction

This project focuses on Health Monitoring and Analysis using Python. The goal is to analyze a dataset containing various health metrics of patients to gain insights into their health status, identify patterns, and group patients based on their health standards.

## Project Overview

The project involves the following key tasks:

* **Data Preprocessing:** Cleaning the dataset by handling missing values and formatting inconsistencies.
* **Exploratory Data Analysis (EDA):** Analyzing the distribution and relationships between different health metrics.
* **Grouping Patients:** Grouping patients based on age, blood pressure, heart rate, and oxygen saturation categories.
* **Visualization:** Visualizing the distribution of patient groups and health categories.

## Libraries Used
* **Pandas:** Used for data manipulation and analysis.
* **Matplotlib:** Utilized for creating various plots and visualizations.
* **Seaborn:** Used for enhancing the aesthetics of visualizations and creating statistical plots.
* **NumPy:** Employed for mathematical operations and array manipulation.

## [Dataset](https://statso.io/healthcare-analysis-case-study/)

The dataset contains the following columns:

**PatientID:** Numerical identifier for the patient.

**Age:** Age of the patient in years.

**Gender:** Gender of the patient.

**HeartRate:** Heart rate in beats per minute.

**BloodPressure:** Blood pressure readings, formatted inconsistently.

**RespiratoryRate:** Respiratory rate in breaths per minute.

**BodyTemperature:** Body temperature in Fahrenheit.

**ActivityLevel:** Activity level at the time of the measurement.

**OxygenSaturation:** Oxygen saturation percentage.

**SleepQuality:** Quality of sleep reported by the patient.

**StressLevel:** Reported level of stress.

**Timestamp:** Date and time of the measurement.

## How to Use
  Excited to embark on your health analysis journey? Follow these steps:

1. **Clone the Repository:** Clone this repository to your local machine using git clone.
2. **Install Dependencies:** Ensure you have Python installed, along with the required libraries mentioned.
3. **Run the Notebook:** Open the Jupyter notebook health_analysis.ipynb using Jupyter Notebook or Google Colab.
4. **Execute the Code:** Run the code cells in the notebook to perform data analysis and visualization.

## Visualizations 

* **Visualizing Health Metrics Distribution:**
  * Visualize the distributions of key health metrics like Age, Heart Rate, Respiratory Rate, Body Temperature, and Oxygen Saturation to gain insights into the dataset 

    ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/e9eb5bcf-5fc9-431d-a899-1ec6a1759620)

* **Gender Distribution and Correlation:**
  *  **Gender Distribution:**
      *  Nearly equal split between male and female subjects, with males slightly more prevalent at 51.2%.
        
  *  **Correlation Analysis:**
      *  Correlation matrix reveals no strong correlations among health metrics.
      *  Variables (Age, Heart Rate, Respiratory Rate, Body Temperature, and Oxygen Saturation) show minimal linear relationship with each other.
      *  Changes in one metric are not strongly associated with changes in others within this dataset.

     ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/0c7ce796-e46f-410a-886f-40cf2eb58fe8)

* **Heart Rate by Activity Level:**
    * **Blood Pressure Distribution:**
        * Examined the distribution of blood pressure levels.
          
    * **Health Metrics by Gender:**
        * Median heart rate increases from resting to walking.
        * Median heart rate doesn't significantly increase further during running.
        * Considerable overlap in interquartile ranges between walking and running.
        * Presence of outliers in resting category indicates higher resting heart rates for some individuals.
          
      ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/8dd0127a-709f-4d74-b4d4-5be620b96d71)

* **Distribution of Blood Pressure Levels and Health Metrics by Gender:**
    * **Blood Pressure Distribution:**
      * Systolic blood pressure shows a spread-out distribution with common readings around 120 mmHg and 140 mmHg.
      * Diastolic blood pressure has a narrower distribution with a significant peak around 80 mmHg.
      * Systolic values have a broader spread than diastolic ones, typical due to varying factors like activity level and stress.
        
    * **Heart Rate and Oxygen Saturation:**
      * Both genders exhibit similar median heart rate and oxygen saturation values.
      * Interquartile ranges for heart rate and oxygen saturation are relatively similar between genders.
      * Few outliers in oxygen saturation suggest some individuals with lower-than-typical values but don't significantly affect the overall distribution. 
  
      ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/7e4a641e-ce19-4433-a02e-196da43ff18a)
  

      ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/9baf162c-13ad-4a65-a0db-380d4c9d5373)
  
* **Analysis of Heart Rate and Oxygen Saturation by Sleep Quality and Stress Levels:**
    * **Heart Rate and Sleep Quality/Stress:**
        * Heart rate remains consistent across different sleep quality and stress levels.
        * Slight increase in variation for poor sleep quality.
          
    * **Oxygen Saturation and Sleep Quality/Stress:**
        * Minimal decrease in median oxygen saturation values from excellent to poor sleep quality.
        * Some outliers indicating lower saturation for excellent and good sleep.
        * Oxygen saturation remains largely unchanged when correlated with stress levels.
  
  ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/a4a71e92-c14a-4447-98f8-1286345daa8d)


* **Analysis of Respiratory Rate and Body Temperature by Activity Levels:**
  * **Respiratory Rate:**
    * Increases with activity level.
    * Higher median rates for walking and running compared to resting.
      
  * **Body Temperature:**
    * Slight upward trend from resting to running.
    * Consistent with body heating up during physical exertion.
      
  * **Outliers:**
    * Some individuals have temperatures outside typical range for resting and running.

  ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/3386b88b-622f-4062-a367-0431feb62f37)

* **Categorized Health Metrics Distribution:**
  * The visualization categorizes key health metrics such as age, blood pressure, heart rate, and oxygen saturation into different groups and presents their distributions within the dataset. Here's a     summary of each distribution:
    
    * **Distribution of Age Groups:**
        * The count plot reveals that the ‘Senior’ category has the highest count, followed by ‘Young’ and ‘Middle-aged’ categories. This suggests that seniors represent the largest age group in the dataset.

    * **Distribution of Blood Pressure Categories:**
        * Most of the dataset falls under ‘Normal’ blood pressure, with fewer instances in the ‘Elevated’ and ‘Hypertension Stage 1’ categories. ‘Hypertension Stage 2’ has the lowest count, indicating that severe hypertension is less common among the participants.

    * **Distribution of Heart Rate Categories:**
        * The majority of individuals have a ‘Normal’ heart rate, with very few falling into the ‘Low’ or ‘High’ categories. This indicates that most individuals in the dataset have heart rates within the expected range.

    * **Distribution of Oxygen Saturation Categories:**
        * Almost everyone exhibits ‘Normal’ oxygen saturation levels, with very few instances of ‘Low’ saturation. This suggests that oxygen deprivation is not a common issue among the participants.
          
  ![image](https://github.com/poojarao76/Health-Monitoring-and-Analysis-using-Python/assets/132984172/62b29de4-5b5e-4dd8-9266-d7cfdc4a58a2)

## Acknowledgments

I extend my heartfelt gratitude to statso for providing the invaluable dataset that fuels this analysis. Special thanks to The Clever Programmer for inspiring this project with their innovative problem statement.
