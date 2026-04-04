# Data Analysis of Police Related Fatalities
This repository contains a Jupyter Notebook that cleans and explores various trends regarding
police fatality data collected by the Washington Post.

---

## Project Overview
The goal of this project is to:
- Understand the structure and contents of the dataset
- Perform data cleaning and exploratory analysis
- Visualize key trends and relationships

---

## Structure
```
|-Data
| |-csv_format/ # Original csv files
| |_db_format/ #Databases for SQLite querying
|-.gitignore # Files to be ignored
|-Fatal_Force.ipynb # Jupyter Notebook File 
|-README.md # Current File
|_requirements.txt # Python packages used
```

## Running the Notebook
1. Clone this repository
```
git clone https://github.com/JustinWoo20/fatal-force.git
cd fatal-force
```
2. Launch Jupyter
```
jupyter notebook
```
3. Open ```Fatal_Force.ipynb``` and run the cells

---

## Technologies Used
-Python

-Pandas

-Plotly, Matplotlib, Seaborn

---
## Requirements
This project uses Python 3.9+ and the following libraries:
 
- numpy  
- pandas  
- plotly  
- matplotlib  
- seaborn

Install them with:

```
pip install -r requirements.txt
```

---
## Future Improvements
Currently, the data analysis does not account for population differences across the various regions represented in the dataset. 
This can skew comparisons and insights.

To address this, I plan to:
1. Collect population data for each region 
2. Calculate a population-weighted average to better understand proportional trends and make the analysis more accurate.

---
# Portfolio Project  
This project was completed as part of a professional Python course. 

It demonstrates my ability to work with real-world data using Python and Jupyter Notebook, including data cleaning, 
analysis, and visualization. The notebook is designed to showcase the skills I’ve developed throughout the course.