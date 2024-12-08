# codsofttask2
# Correct dataset path
url = '/kaggle/input/iris-flower-dataset/IRIS.csv'

# Load the dataset using pandas
data = pd.read_csv(url)

# Display the first few rows to check the data
data.head()
# Import necessary libraries
import pandas as pd
import numpy as np
# Check the first few rows of the dataset
data.head()
# Correct the column name to 'species' (lowercase)
sns.countplot(x='species', data=data)
plt.title('Distribution of Iris Species')
plt.show()
# Print column names to check
print(data.columns)
# Import necessary libraries
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load the dataset
url = '/kaggle/input/iris-flower-dataset/IRIS.csv'
data = pd.read_csv(url)

# Display the first few rows to check the dataset
print(data.head())

# Check for missing values
print(data.isnull().sum())

# Correct the column name and visualize the distribution of species
sns.countplot(x='species', data=data)
plt.title('Distribution of Iris Species')
plt.show()
