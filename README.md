# ECE 225A Project: Exploratory Data Analysis of World Happiness Index and its Correlation with Possibly Relevant Factors

## Project Overview

The Britannica Encyclopedia defines happiness as, "the state of emotional well-being that a person experiences either in a narrow sense, when good things happen in a specific moment, or more broadly, as a positive evaluation of one’s life and accomplishments overall—that is, subjective well-being." Therefore in a general sense, happiness broadly comes from personal experiences, and its definition is subjective to things people give priority to.

For example, a person working in a stressful high-income job may be just as content with his/her life, as another person working in a stress-free low-income job, if the former weighs happiness mainly on wealth and exuberance, while the latter gives more  - ance to the time he/she gets to spend with his/her family.

Through this exploratory data analysis, we seek to answer the following question: "Is there a particular set of factors, which has a strong correlation when it comes to determining individual happiness?"

Discounting the highly personal and subjective factors, for which obtaining data is an intractable task, we narrow our focus down to factors which can be quantified and for which one can easily acquire reliable numerical data on their hands.

## Project file structure

### Datasets

The datasets have been taken from Kaggle, and are available along with the code in the repository. The following datasets are used:

 - World Happiness Report: This dataset is an aggregation of Gallup World Poll Data from 2007 till 2021, which has been made publicly available in Kaggle. Link: [World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)
 - Human Development Index: This dataset, originally sourced from UNDP's Human Development Reports and publicly made available in Kaggle, contains more than 30 years of Human Development Index (HDI) data of 195 countries (superset of countries in World Happiness Data), and the the different factors that influence HDI. Link: [Human Development Index](https://www.kaggle.com/datasets/iamsouravbanerjee/human-development-index-dataset/code)
 - Global Suicide Data: This dataset contains suicide data across nations from 2000 to 2019. It was originally scraped from WHO mortality statistics and ICD10 death classification codes, and made available for open use in Kaggle. Link: [Global Suicide Data](https://www.kaggle.com/datasets/fernandoretamales/health-expenditure-and-suicide-rates)
- COVID-19 Global Data: List of countries most impacted by Covid as per the World Health Organization (WHO), based on the number of cases. Link: [COVID-19 Global Data](https://covid19.who.int/WHO-COVID-19-global-table-data.csv)

### Jupyter Notebook

The [Jupyter Notebook](ECE225A_Project.ipynb) has the entire code which can be run to generate the visualizations.

## Third Party Modules

The third party modules used are as listed below:

- numpy
- pandas
- plotly.express
- pycountry
- pycountry_convert
- scipy.stats
- matplotlib
- pylab
- seaborn

## How to run the code

- Install all required third party modules

- Download and import all the datasets

- Run complete notebook or particular cells of [`ECE225A_Project.ipynb`](ECE225A_Project.ipynb) for viewing the plots.
