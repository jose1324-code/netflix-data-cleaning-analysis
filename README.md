Netflix Data Cleaning and Analysis
This project focuses on cleaning and preparing a Netflix Movies and TV Shows dataset using Python and Pandas.

📌 Dataset Overview
- Source: Netflix titles dataset
- Columns include: title, director, cast, country, date_added, release_year, rating, duration, genres, etc.

 🧼 Data Cleaning Steps Performed

 - Removed duplicate records
 -  Converted `date_added` column to datetime format
 -  Filled missing values:
   - 'director', 'cast', 'country' → "Unknown"
 -  unique values in each column
 -  Typecasting 'duration' from string to integer
 -  Typecasting 'date_added' from string to datetime

  📁 Files Included

- `Netflix_cleaned_dataset.csv`: Dataset
- `netflix_data_cleaning.ipynb`: Colab notebook with code
- `README.md`: Project documentation
- `Netflix_cleaned_dataset.csv`: Cleaned dataset

 🚀 How to Use

1. Clone this repo
2. Open `netflix_data_cleaning.ipynb` in Google Colab or Jupyter
3. Run all cells to view and understand the cleaning steps
4. Use the cleaned dataset for further analysis or modeling


