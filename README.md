# task1
# Netflix Titles Dataset Cleaning Project
This project focuses on cleaning and preparing the Netflix Titles dataset for analysis and visualization using Python (Pandas).

Dataset Overview
The dataset includes metadata about TV shows and movies available on Netflix as of 2021. Key columns include:

show_id, type, title, director, cast

country, date_added, release_year, rating

duration, listed_in, description



Cleaning Steps Performed
Imported data using pandas

Checked for and counted duplicate rows

Removed duplicate records

Standardized text values (e.g., country, type)

Converted date_added to datetime format

Renamed column headers to lowercase with underscores

Verified and ensured correct data types

Saved cleaned dataset as netflix_titles_cleaned.csv


 
 Files Included
netflix_titles.csv – Original dataset

netflix_titles_cleaned.csv – Cleaned output

cleaning_script.ipynb – Python notebook for data cleaning




How to Use
Open the notebook in Google Colab, Jupyter, or any Python IDE.

Upload the original CSV file.

Run each step to clean the data.

Download the cleaned dataset for further analysis.
