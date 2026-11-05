# Netflix Data Cleaning and Preparation

## Project Overview
This project focuses on cleaning and preparing the Netflix Movies and TV Shows dataset for analysis using Microsoft Excel.

## Dataset
The dataset contains information about Netflix movies and TV shows, including titles, directors, cast members, countries, release years, ratings, durations, and categories.

## Data Cleaning Performed

### 1. Missing Values
Missing values were identified and handled in the following columns:

- Director: Missing values were replaced with "Not Available".
- Cast: Missing values were replaced with "Not Available".
- Country: Missing values were replaced with "Not Available".
- Rating: Missing values were replaced with "Not Rated".
- Duration: Missing values were replaced with "Not Available".

### 2. Duplicate Records
The dataset was checked for duplicate records using Excel's Remove Duplicates feature.

Result: No duplicate records were found.

### 3. Incorrect or Inconsistent Values
Some duration values were found incorrectly placed in the Rating column. These values were corrected by moving the duration values to the Duration column and updating the Rating column to "Not Rated" where appropriate.

## Tools Used
- Microsoft Excel

## Final Result
The dataset was cleaned and prepared for further data analysis.

## Files
- cleaned_netflix_titles.xlsx - Cleaned dataset
- README.md - Project documentation