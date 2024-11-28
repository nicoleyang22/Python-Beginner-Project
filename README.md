# The relationship between Sleeping and Occupations
This is a simple Python project about "Sleeping &amp; Occupations".

![](Sleeping_Occupations.JPG)

### Table of Contents
1. [Project Description](#project-description)
2. [Usage](#usage)
3. [Conclusions](#conclusions)
4. [Contributors](#contributors)
5. [Contact](#contact)

### Project Descriptions
SleepInc has provided you with an anonymized sleep and lifestyle metrics dataset for 374 individuals. This dataset contains average values for each person calculated over the past six months. The data is saved as sleep_health_data.csv.
The dataset includes 13 columns covering sleep duration, quality, disorders, exercise, stress, diet, demographics, and other factors related to sleep health.

![image](https://github.com/user-attachments/assets/56a545d4-8c11-409a-a671-62e795ba2084)

### Usage
Here’s how I used to run this project:

1. **Data Extraction**: The script reads data from the `data/sleep_health_data.csv` file.
2. **Data Transformation**: It cleans, filters, and processes the raw data for analysis.
3. **Data Grouping and Aggregation** : using groupby() to calculate the mean of ('Sleep Duration','Quality of Sleep') which grouped by occupation and BMI category.
4. **Sorting and Indexing** : using sort_values() and index[0] to extracted the occupation with the lowest average sleep duration and sleep quality.
5. **Dictionary Storage** : stored the output of insomnia ratios for different categories in a dictionary, which looks more organizing and structuring.

### Conclusions

#### Occupation and Sleep:

The occupation with the lowest average sleep duration and sleep quality was both identified as "Sales Representative", which could indicate that people in sales-related roles experience more challenges with sleep, potentially due to factors like work-related stress, irregular hours, or lifestyle choices associated with this job.

#### BMI and Sleep Disorders:

The correlation between BMI categories and insomnia rates :

Individuals in the "Normal" BMI category have a lower insomnia rate (4%)

"Overweight" individuals have a slightly higher insomnia rate (43%)

"Obese" category shows the highest insomnia rate at 40%


It may indicate that higher BMI categories are more likely to experience insomnia, which could be due to factors such as poor physical health, lifestyle habits, or stress.

### Contributors
To contribute to this project, you can fix the repository and submit a pull request.

### Contact
For questions, feedback, or suggestions, feel free to reach out:
- **Email**: chuncy0331@gmail.com
