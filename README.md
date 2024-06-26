# Mental Health Data Analysis Project (CSC-40048)

## Project Description
This project, titled "Exploring Mental Health Trends: Insights from Visual Analysis and Big Data Techniques," is conducted as part of the Visualization for Data Analytics module. It aims to explore the intricate relationships within a large mental health dataset, focusing on treatment-seeking behavior, work interest, and the impact of family history on mental health. Through a combination of Python for data cleaning and exploratory data analysis and PySpark for big data handling, this research provides robust visualizations and big data analysis to inform better mental health strategies.


## Table of Contents
- [Installation](#installation)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Big Data Analysis](#big-data-analysis)
- [Usage](#usage)
- [Credits](#credits)
  

## Installation
To run this project locally, clone the repository and install the necessary packages:
```
git clone https://github.com/TechAriel/mental-health-data-analysis.git
```
```
cd mental-health-data-analysis
```
```
pip install -r requirements.txt
```


## Dataset Description
The dataset encompasses responses from 292,364 individuals across 35 countries, with a significant number of responses from the United States and the United Kingdom. It includes demographic information and mental health indicators, facilitating an in-depth analysis of mental health trends. 
Note: Due to the large size of the dataset, it has been uploaded under “Releases” as; Release tag: “Mental Health Dataset” Dataset: “Mental.Health.Dataset.csv”



## Data Preprocessing
A series of preprocessing steps were applied to optimize the data for analysis, including duplicate removal, missing value imputation, data transformation, and categorical encoding.

### 1. Cleaned Mental Health Dataset
![Cleaned Mental Health Dataset](images/CleanedMentalHealthDataset.png)

### 2. Cleaned Mental Health Dataset(Encoded Values)
![Cleaned Mental Health Dataset(Encoded Values)](images/CleanedMentalHealthDataset(EncodedValues).png)



## Data Visualization
The project features numerous visualizations that explore various aspects of mental health, such as the effects of work interest and family history on treatment seeking. These visualizations aid in understanding the dynamics affecting mental health outcomes across different demographics.

### *1. Impact of Work Interest & Family History on Seeking Treatment*
![Impact of Work Interest & Family History on Seeking Treatment](images/ImpactofWorkInterest&FamilyHistoryonSeekingTreatment.png)

### *2. Impact of Family History on Mental Health Outcomes*
![Impact of Family History on Mental Health Outcomes](images/ImpactofFamilyHistoryonMentalHealthOutcomes.png)

### *3. Gender Differences in Seeking Treatment*
![Gender Differences in Seeking Treatment](images/GenderDifferencesinSeekingTreatment.png)

### *4. Days Indoors vs Mental Health Outcomes*
![Days Indoors vs Mental Health Outcomes](images/DaysIndoorsvsMentalHealthOutcomes.png)

### *5. Days Indoors vs Mental Health Outcomes*
![Days Indoors vs Mental Health Outcomes](images/DaysIndoorsvsMentalHealthOutcomes1.png)

### *6. Percentage of Respondents by Mental Health History Category*
![Percentage of Respondents by Mental Health History Category](images/PercentageofRespondentsbyMentalHealthHistoryCategory.png)

### *7. Seasonal Variation in Mental Health Treatment*
![Seasonal Variation in Mental Health Treatment](images/SeasonalVariationinMentalHealthTreatment.png)

### *8. Time Spent Indoors per Season*
![Time Spent Indoors per Season.png](images/TimeSpentIndoorsperSeason.png)

### *9. Gender Distribution Per Occupation*
![Gender Distribution Per Occupation](images/GenderDistributionPerOccupation.png)

### *10. Employee's Job Interest per Sector*
![Employee's Job Interest per Sector](images/Employee'sJobInterestperSector.png)

### *11. Percentage of Treatments by Country*
![Percentage of Treatments by Country](images/PercentageofTreatmentsbyCountry.png)

### *12. Growing Stress with Self Employment*
![Growing Stress with Self Employment](images/GrowingStresswithSelfEmployment.png)

### *13. Percentage of Treatments by Mood Swings & Social Weakness*
![Percentage of Treatments by Mood Swings & Social Weakness](images/PercentageofTreatmentsbyMoodSwings&SocialWeakness.png)

### *14. Percentage of Treatments by Coping Struggles*
![Percentage of Treatments by Coping Struggles](images/PercentageofTreatmentsbyCopingStruggles.png)



## Big Data Analysis Techniques
This section details the use of big data technologies like PySpark, which provided the infrastructure for handling and analyzing the large-scale dataset. The experience and insights gained from using these technologies are documented here.

### *Gender Distribution Analysis by Occupation using PySpark*
![Gender Distribution Analysis by Occupation using PySpark](images/GenderDistributionAnalysisbyOccupationusingPySpark.png)


## Usage
After installation, execute the script to process the data and generate visualizations:
```
python MentalHealthDatasetAnalysis.py
```

## Credits
This project was developed by the following students, as part of the Visualization for Data Analytics module under the guidance of Dr. Sangeeta Sangeeta:

### Gabriel (@TechAriel)

### Thomas (@TomGoold)

### Muhammad (@Eddy118)

Utilizing Python for data analysis and Apache Spark (PySpark) for big data tasks, this project showcases the integration of these technologies in analyzing real-world datasets.
