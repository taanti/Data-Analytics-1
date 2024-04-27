# Learn Data Visualisation Part 1

This repository contains the first part of the Python Mastery for Data Analysts guide, focusing on foundational Python concepts essential for data analysis. This guide is designed to help you build a strong foundation in Python programming, equipping you with the necessary skills to perform data analysis tasks effectively.

In this guide, we learn something about Data Visualisation. Data visualization with Python is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

By exploring the basics of data visualization in Python, you can create compelling visualizations that help you communicate your findings and insights more effectively.

## Importing Libraries

- Importing libraries is a crucial step in data analysis as it allows you to access a wide range of functions and tools that can help you perform various tasks. In Python, you can import libraries using the `import` keyword followed by the library name.

```# Importing the NumPy and Pandas library with the alias 'np' with the alias 'pd'
import numpy as np
import pandas as pd
# Importing the pyplot module from the Matplotlib library with the alias 'plt'
import matplotlib.pyplot as plt
# Jupyter Notebook magic command to display Matplotlib plots inline
%matplotlib inline
# Importing the Seaborn library with the alias 'sns'
import seaborn as sns
```

## Basic Data

_What is Data_ ? Data is a collection of facts, such as numbers, words, measurements, observations or just descriptions of things. Data can be qualitative or quantitative. Data can be structured or unstructured. Data can be continuous or discrete. Data can be primary or secondary.

### Data Variable

Data Variable is a container that holds certain information or data. It can be a single value, such as a number or string, or a collection of values, such as a list, tuple, dictionary, or a more complex data structure like a DataFrame or NumPy array used in data analysis. The data types included are Category and Numeric.

Dataset:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/StoreTrends.png" /></div>

Data CSV Source : [Data Source](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)

**Category**

Categorical data is a type of data that can be divided into groups or categories. It represents characteristics or attributes of a data

- Nominal

  Nominal scales involve labeling variables without assigning quantitative values, essentially serving as straightforward labels.

  Example :
  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/StoreTrends%20-%20Nominal.png" /></div>

- Ordinal

  Ordinal scales prioritize the order of values, but the exact differences between them aren't precisely quantified.

  Example :
  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/StoreTrends%20-%20Ordinal.png" /></div>

---

Dataset:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Flight.png" /></div>

Data CSV Source : [Data Source](https://www.kaggle.com/datasets/sandhiyakumar/airline-passenger-satisfication-data)

**Numeric**

Numeric data is a type of data that consists of numbers and can be measured or quantified. It represents quantities or values of a data.

- Discrete
  Discrete data encompass items that are countable, assuming possible values that can be enumerated. The range of potential values may be fixed, termed finite, or extend infinitely from 0 onward.

  Example :
  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Flight%20-%20Discrite.png" /></div>

- Continuous
  Continuous data, on the other hand, represent measurements without countable values, only describable through intervals on the real number line.

  Example :
  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Flight%20-%20Continous.png" /></div>

### Data Categories

"Data categories" typically denote different classifications or types of data based on their characteristics, attributes, or properties. These classifications aid in organizing and comprehending various types of information and direct the methods employed for data collection, storage, analysis, and interpretation. Two primary categories within this context are Quantitative Data and Qualitative Data.

- Quantitative data : Quantitative data is information that is expressed in numerical form or quantities. This type of data can be measured and counted numerically.

  Example :
    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Flight%20-%20Quantitative.png" /></div>

- Qualitative data : qualitative data is information that is expressed in descriptive or qualitative form. It describes specific characteristics or qualities that cannot be measured numerically.

  Example :
    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Flight%20-%20Qualitative.png" /></div>

### Metadata

Metadata is descriptive or structural data that provides information about other data, offering context, meaning, and organization. It includes attributes like title, author, creation date, file format, and keywords. Essentially, metadata is crucial for efficiently managing, understanding, and retrieving data.

Data CSV Source : [Data Source](https://opendata.jabarprov.go.id/id/dataset/jumlah-peminatan-kelas-pelatihan-candradimuka-jabar-coding-camp-berdasarkan-batch-dan-mode-kelas-di-jawa-barat)

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Metadata.png" /></div>

### Big Data

Big data refers to extremely large and complex datasets that cannot be easily managed, processed, or analyzed using traditional data processing applications or techniques.

Examples of Big Data Sources:

- Social Media Analytics: Social media companies like Facebook, Twitter, or Instagram collect billions of user data every day, including statuses, comments, images, and more.

## Data Cleansing

Data Cleansing is the process of identifying and correcting errors or inconsistencies in data to improve its quality and reliability. It involves removing duplicate records, correcting inaccurate data, filling in missing values, and standardizing data formats.

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Lusitania.png" /></div>

 Data CSV Source : [Data Source](https://www.kaggle.com/datasets/rkkaggle2/rms-lusitania-complete-passenger-manifest/data)

- Data Imputation
  Data imputation refers to the process of filling in missing values in a dataset. This is a common task in data preprocessing, especially when dealing with real-world datasets that often have missing or incomplete information.

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Data%20Imputation.png" /></div>

- Drop Data
  Dropping data involves removing rows or columns from a dataset, typically due to reasons like missing values, outliers, redundant variables, data quality issues, or specific sample selection criteria. It should be done carefully, as it may lead to information loss or biased results.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Drop%20Data.png" /></div>

- Categorical Nominal
  Categorical nominal data refers to variables in a dataset that represent categories or groups with no inherent order or ranking. These categories are distinct and separate, and there is no natural ordering among them.

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Categorical.png" /></div>

- Data Manipulation
  Data manipulation involves the process of altering or manipulating data to prepare it for analysis. This often includes a series of operations such as merging (joining), filtering, grouping, transforming, and more. The goal is to obtain data that is more structured, relevant, and ready for further analysis.

  <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Data%20Manipulation.png" /></div>

  - Relationship between Column
    The relationship between columns in a dataset refers to how variables are related or connected to each other. This relationship can be explored through various statistical methods, such as correlation analysis, regression analysis, and more.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Relation%20Between%20Column.png" /></div>

  - Pivot Table
    A pivot table is a data summarization tool used in data processing and analysis. It allows you to reorganize and summarize selected columns and rows of data in a spreadsheet or database table to obtain a desired report or analysis.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Pivot%20%2B%20Visual.png" /></div>

  - Pivot Slice
    A pivot slice is a subset of data obtained by selecting specific rows and columns from a pivot table. It allows you to focus on a particular segment of the data for further analysis or visualization.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Pivot%20Slice.png" /></div>

  - Group By
    The groupby function in Python is used to split data into groups based on some criteria, apply a function to each group independently, and then combine the results into a data structure.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/GroupBy.png" /></div>

  - Crosstab
    A crosstab (cross-tabulation) is a table that displays the frequency distribution of variables in a dataset. It shows the relationship between two or more variables by summarizing the data in a tabular format.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Crosstab.png" /></div>

  - Get Dummies
    The get_dummies function in Python is used to convert categorical variables into dummy/indicator variables. It creates a new binary column for each unique category in the original variable, assigning a value of 1 to the corresponding category and 0 to all others.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Get%20Dummies.png" /></div>

  - Sort
    Sorting data involves arranging rows or columns in a dataset in a specific order based on the values of one or more variables. This can help organize the data for better readability, analysis, or visualization.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Sort.png" /></div>

  - Rename
    Renaming columns in a dataset involves changing the names of variables to make them more descriptive, meaningful, or consistent. This can help improve the clarity and interpretability of the data.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Rename.png" /></div>

  - Concat
    Concatenation is the process of combining two or more datasets along a common axis (row or column) to create a single dataset. This can be useful for merging data from different sources, combining data with similar structures, or creating new datasets for analysis.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Concat.png" /></div>

  - Merge
    Merging data involves combining datasets based on common columns or keys to create a single dataset. This can be useful for integrating data from multiple sources, performing relational database operations, or joining data for analysis.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics1/Marge.png" /></div>

## Lusitania - Dataset Cleansing

In this section use all what we have learned in this week. We will clean the dataset and we use the dataset from [Keggle](https://www.kaggle.com/datasets/rkkaggle2/rms-lusitania-complete-passenger-manifest/data). This dataset contains information about the passengers on the RMS Lusitania, a British ocean liner that was sunk by a German U-boat during World War I

For more details:
[Open File](https://github.com/sisatput/DataAnalytics1/blob/main/Data%20Cleansing%20Dataset%20Lusitania.ipynb)

## End Notes

This is the end of the first part of the Python Mastery for Data Analysts guide. We hope you have found this guide helpful in building a strong foundation in Python programming. In the next part of the guide, we will delve deeper into data analysis techniques and explore more advanced Python concepts. Stay tuned for more updates!
