# Task 01: Data Cleaning for ML

## 📝 Task Description
Clean and prepare raw data for Ml

## 🔧 Tools Used
- Python
- Pandas
- Matplotlib
- VScode

## 🗂️ Folder Structure
- data: Contains raw and cleaned data
- task-01-data-cleaning.ipynb: Scripts that was used for preprocessing data

## 🧪 Steps Performed
1. Dropped 'Cabin' column with >50% null values.
2. Encoded Categorical Values of 'Sex' Column to Numerical Values (male:1,female:2).
3. Replacing null age values with Median 'Age'.
4. Replaced missing 'Embarked' values with most frequent 'Embarked' Value
5. Capped 'Fare' Outliers beyond 95 percentile to 95 percentile
6. Normalised 'Age' and 'Fare' to fall under the same scale ( 0-1 )
7. Exported cleaned data back in '/data'

