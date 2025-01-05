# Loan Data Analysis with Google Cloud Platform

## Project Overview

This personal project demonstrates my proficiency in leveraging Google Cloud Platform(GCP) tools, including BigQuery and Google Cloud Storage, to analyze and derive insights from loan data. I combined multiple data sources, including public datasets and simulated loan applications, to conduct a comprehensive analysis.

## Objectives

- Utilize BigQuery for data querying and manipulation.
- Integrate data from various sources like Google Sheets and BigQuery datasets.
- Develop a linear regression model to understand the relationships in the data.
- Explore geographic data handling capabilities in BigQuery.

## Technical Setup
**Virtual Environment**
Setup a Python virtual environment to manage project dependencies.

```python
python3 -m venv venv
source venv/bin/activate
```

**Dependencies**
Install the necessary Python packages within the virtual environment.

```python
pip install jupyterlab google-cloud-bigquery google-cloud-bigquery-storage pyarrow tqdm ipywidgets
pandas matplotlib db-dtypes pandas-gbq
```
**Google Cloud Configuration**
Configure Google Cloud CLI and authenticate to access BigQuery and Google Drive.

```python
gcloud auth application-default login --scopes=openid,https://www.googleapis.com/auth/cloud-platform,https://www.googleapis.com/auth/drive.readonly
```
**Note**: Ensure the security of your Google Cloud credentials.

## Data Analysis Notebook
Developed a Jupyter Notebook (p8.ipynb) to conduct the analysis, addressing several analytical questions using SQL queries and Python code in BigQuery.

## Insights and Outputs
- **Geographic Analysis**: Utilized public geographic data to analyze county-level loan data.
- **Data Integration**: Demonstrated the ability to merge data from different sources seamlessly.
- **Predictive Modeling**: Developed a linear regression model to predict loan amounts based on applicant income.

##  Reflections
This project highlights my ability to integrate complex datasets and utilize cloud technologies effectively. It has improved my data manipulation skills and familiarized me with geographic data analysis in BigQuery.
