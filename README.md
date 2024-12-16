# Module-1-Capstone-EDA-Sleep-and-Lifestyle
This repository contains a Notebook created at the end of the 1st Module Of Data Science Bootcam.


# Sleep Health and Lifestyle Analysis

## I. Goal

This notebook analyzes a dataset on sleep health and lifestyle to explore factors that influence sleep quality and duration. The aim is to identify correlations between lifestyle habits such as **physical activity**, **stress levels**, **sleep duration** and **sleep quality**, and provide insights into improving sleep health. The following questions are addressed in this analysis:

- Is there a correlation between **physical activity level** and **quality of sleep**?
- How does **stress level** impact **sleep quality** and **sleep duration**?
- Are there certain **occupations** that have better or worse sleep quality?
- Does **sleep duration** vary across **different BMI categories**?
- What are the relationships between **heart rate** and **sleep duration**?
- How does **activity level** influence the **duration of sleep**?

## II. Data

The dataset used in this analysis was collected from various participants to examine factors related to **sleep health**. It includes the following variables:

1. **Personal Information**  
   - **Person ID**  
   - **Gender**  
   - **Age**  
   - **Occupation**  
   - **BMI Category**  

2. **Sleep Health**  
   - **Sleep Duration** (hours)  
   - **Quality of Sleep** (scale from 1 to 10)  
   - **Sleep Disorder** (Nan/Sleep Apnea/Insomnia)

3. **Lifestyle Factors**  
   - **Physical Activity Level** (scale from 1 to 10)  
   - **Stress Level** (scale from 1 to 10)  
   - **Heart Rate** 
   - **Daily Steps**

## III. Summary of Analysis

Data preparation involved cleaning the dataset by handling missing values and ensuring consistency across variables. Although the Data set was mostly clean and ready to use, there was some 
modifiction (duplicate in certain categorical columns) to be added for better analysis.

The analysis used statistical methods such as:

- **Correlation analysis** to explore relationships between variables.
- **Visualizations** including heatmaps, boxplots, bar plots, and scatter plots to depict patterns and insights.
- **Statistical tests**, such as t-tests, to assess the significance of observed relationships.

Key findings were visualized using Python libraries like Seaborn and Matplotlib.

## IV. Conclusion and Recommendations

The analysis reveals the following insights:

- **Stress level** has a strong negative correlation with **sleep quality** and **duration**. Higher stress levels are associated with poorer sleep quality.
- **Physical activity** has a moderate positive correlation with sleep quality, indicating that more active individuals tend to sleep better.
- **BMI categories** influence sleep duration, with those in the "normal" BMI category reporting better sleep quality and duration compared to other categories.
- **Occupations** like **engineers** and **lawyers** tend to have better sleep, while individuals in high-stress jobs may experience worse sleep.
- The relationship between **heart rate** and **sleep duration** also suggests that higher heart rates may be linked to shorter sleep durations.

**Recommendations**:
- Further studies could focus on **sleep disorders** and their impact on these relationships.
- **Time-related factors**, such as seasonal changes in sleep patterns, should be explored to understand their influence on sleep health.

## V. Further Exploration

Future work could incorporate the following variables for a more comprehensive analysis:
- **Time factors** such as the time of day, week, or year.
- **Sleep disorders** and their impact on sleep quality and duration.
