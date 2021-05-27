# Example data science portfolio

## Data cleaning techniques with the Python Programming Language

*Course: Learn Data Cleaning with Python | Udemy*

Pre-requisites
>
> Importing pandas and numpy library
>
> import pandas as pd
>
> import numpy as np

## Standardisation

Example 1

>Renaming column names

> Dataset url = http://bit.ly/SampleDataset
>
> Reading our dataset from the url 

> df = pd.read_csv('http://bit.ly/SampleDataset')
df.head()

Example 1a
>
> Renaming the column names
>
>
> df.columns = ['name', 'city', 'country', 'height', 'weight', 'account_a', 'account_b', 'total_account']
df.head()

Example 1b
>
>Renaming our columns, if we have many column names.
>
> df1 = pd.read_csv('http://bit.ly/SampleDataset')
> df1.head()
