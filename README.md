# Foundation Setup & Exploratory Data Analysis (EDA)

## Project Overview
This project is the first task of the ApexPlanet AI Internship. The objective is to set up the Python environment, load the dataset, explore its structure, identify missing values, and perform basic Exploratory Data Analysis (EDA).

## Dataset
- Dataset Name: Amazon Sale Report.csv
- File Type: CSV
- Domain: E-commerce Sales

## Objectives
- Set up the Python environment.
- Import required libraries.
- Load the dataset using Pandas.
- Understand the dataset structure.
- Check missing values and duplicate records.
- Generate descriptive statistics.
- Visualize important insights using charts.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
```

## Steps Performed

1. Imported required libraries.
2. Loaded the CSV dataset.
3. Displayed the first five rows.
4. Checked dataset dimensions.
5. Displayed dataset information.
6. Generated summary statistics.
7. Identified missing values.
8. Checked duplicate records.
9. Visualized important features using graphs.

## Sample Code

```python
import pandas as pd

df = pd.read_csv("Amazon Sale Report.csv", low_memory=False)

df.head()
df.info()
df.shape
df.describe()
df.isnull().sum()
```

## Outputs
- Dataset loaded successfully.
- Basic information of the dataset displayed.
- Missing values identified.
- Summary statistics generated.
- Data visualizations created for analysis.

## Conclusion
The dataset was successfully imported and explored using Pandas. Initial EDA helped understand the dataset structure, identify missing values, detect duplicate records, and generate statistical summaries. This analysis provides a strong foundation for further preprocessing and machine learning tasks.

## Author
Sai Dheeraj

## Internship
ApexPlanet AI Internship
