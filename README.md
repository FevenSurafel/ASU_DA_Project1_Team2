# Top 3 Causes of Death and the Correlation between Race, Age, and Sex

This project aims to explore the relationship between the top causes of death and various demographic factors such as race, age, and sex. By analyzing relevant data, we seek to uncover patterns and insights that can contribute to a better understanding of health disparities.

## Introduction
Health disparities, defined as differences in health outcomes between different groups of people. Understanding the factors that contribute to these disparities is essential for developing effective public health strategies. In this project, we focus on exploring the top causes of death and their relationship with race, age, and sex in order to shed light on potential disparities and their underlying causes. 

## Data Sources and Instructions
We gathered data from reputable sources such as Kaggle and the US Census. Below are the links to the original data files and instructions on how to download and process them:

### Data Sources
Mortality Data:

Original source datasets on deaths in the US were downloaded from Kaggle and saved locally. Due to size restrictions, these files could not be uploaded to GitHub.

Download the dataset from Kaggle: https://www.kaggle.com/datasets/cdc/mortality

Population Data:

2005-2010: Population data for these years can be found on the US Census website: https://www.census.gov/data/tables/time-series/demo/popest/intercensal-2000-2010-state.html
2010-2019: Population data for these years can be found on the US Census website: https://www.census.gov/data/datasets/time-series/demo/popest/2010s-state-detail.html

### Instructions for Downloading and Cleaning Data

Step 1: Download the Data

Mortality Data:
1. Go to the Kaggle Mortality Dataset page.
2. Sign in to your Kaggle account.
3. Click the "Download" button to download the dataset to your local machine.

Population Data:
1. Navigate to the 2005-2010 Population Data and 2010-2019 Population Data pages.
2. Download the relevant CSV files for each time period.

Step 2: Clean the Data

Cleaning Mortality Data:
1. Open the 2005_US_Death_DataCleaning.ipynb Jupyter Notebook file in your local environment.
2. Follow the steps outlined in the notebook to clean the 2005 mortality data.
3. Apply the same cleaning process to the data for each subsequent year.

Step 3: Output Cleaned Data

After cleaning the data using the code in the 2005_US_Death_DataCleaning.ipynb notebook, you will obtain output CSV files containing the cleaned data.
These cleaned CSV files will be used for this project and should be saved in an appropriate directory for further analysis.

## Cleaning Code
The cleaning code provided in the 2005_US_Death_DataCleaning.ipynb notebook includes steps for:

Filtering data based on relevant criteria such as demographic variables (race, age, and sex).
Ensure you adjust any year-specific details when applying the cleaning process to different years.

By following these steps, you can replicate our data cleaning process and prepare the datasets for analysis.

## Analysis
Our analysis involves several steps:

Data preprocessing: Cleaning and organizing the datasets for analysis.
Exploratory data analysis: Examining the distribution of causes of death across different demographic groups.
Statistical analysis: Conducting inferential statistics to identify significant associations between variables.
Visualization: Creating visual representations (e.g., charts, graphs) to illustrate key findings.

## Results
Our analysis revealed several interesting findings:

## Gender Distribution in Disease Deaths:

Heart Disease: Males (52.1%), Females (47.9%).
Lung Disease: Males (53.3%), Females (46.7%).

## Marital Status Distribution:

Heart Disease:
Men: Married (53.0%), Widowed (22.7%).
Women: Widowed (65.2%), Married (18.4%).

Lung Disease:
Men: Married (58.7%), Widowed (19.4%).
Women: Widowed (49.8%), Married (29.8%).

## Number of Deaths by Race:

Heart Disease: Predominantly White individuals.
Lung Disease: Predominantly White individuals.

## Age Distribution of Affected Individuals:

Heart Disease: Predominantly aged 60-80 years.
Lung Disease: Predominantly aged 60-80 years.

## Death Rates by Age Group:

Heart Disease: Death rates increase significantly with age.
Lung Disease: Similar trend with increasing death rates with age.

## Regression Analysis:

Both linear and curvilinear regression analyses highlight the exponential increase in death rates among older age groups for heart and lung diseases.

## Trends in Disease Deaths Over Time:

Heart, lung, and diabetes deaths fluctuate over the years, with heart disease consistently having the highest number of deaths.

## Age Distribution Comparison by Gender:

For heart, lung, and diabetes diseases, both genders are predominantly affected in older age groups, with a median age around 80.

## Contributors
Jessica Borbon 
Stephanie Souza
Elizabeth Dutton
Feven Surafel
