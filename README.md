import pandas as pd

# Load the dataset
df = pd.read_csv('food_ordering_behavior_dataset.csv')

# Inspect the first few rows
print(df.head())

# Basic summary statistics
print(df.info())
print(df.describe())
