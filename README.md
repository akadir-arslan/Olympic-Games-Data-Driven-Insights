# Olympic Data Analysis: Cleaning, Analysis, and Visualization

This project analyzes Olympic Games data, focusing on the years since 2012, and does NOT include 2024. The analysis includes data preparation, cleaning, merging datasets, and answering a set of exercises related to the athletes, events, and outcomes of the Olympic Games. The project is a portfolio exam, demonstrating skills in data cleaning, merging, analysis, and visualization.

## Data Sources
The datasets used in this analysis were obtained from Olympedia. Only minor renaming has been performed on the raw data to facilitate the analysis.

### Datasets Used:
- **athletes.txt**: Contains information about the athletes participating in the Olympic Games.
- **games.tsv**: Contains details about different Olympic Games events.
- **results.csv**: Includes the results of the athletes in various Olympic events.

## Data Preparation and Manipulation
The first step of this project was to read the datasets, create DataFrames, and then study and understand the data. The data preparation and manipulation process involved:

### Reading Datasets and Creating DataFrames
- Loaded the data from the text, TSV, and CSV files into Pandas DataFrames.

### Studying, Checking, and Understanding the Datasets
- A thorough overview of each dataset was performed, including checking for missing values and understanding the structure of the data.

### Consolidating and Merging DataFrames
- The athletes and results datasets were merged, followed by merging the resultant DataFrame with the games dataset to create the final consolidated DataFrame.

## Exercises
The following exercises were completed using the prepared dataset:

### Exercise 1: Athlete Analysis
- Identify the most successful athlete since 2012 by the number of gold medals.
- Calculate the total number of athletes who have participated in the Olympic Games since 2012.
- Identify the 10 countries with the lowest ratio of female participants and visualize this information using a bar chart.

### Exercise 2: Specific Queries
- Identify the three most common first names of female athletes from the Republic of Korea.
- Determine the tallest female athlete, including her name, height, country, and sport.
- Identify the 10 sports with the highest average weight of participants.
- Find the three sports with the largest number of severely underweight participants.

### Exercise 3: Age Analysis
- Identify the oldest athlete, including their name and age.
- Find the 10 sports with the highest average age of participants.

### Exercise 4: Medal Table Analysis
- Calculate the medal table for the 2016 Summer Olympic Games in Rio de Janeiro, displaying the top 10 countries.

### Exercise 5: Medal Table Per Capita Analysis
- Using population data, calculate a new medal table for the 2016 Rio Olympics, showing medals per capita for the top 10 countries.

## Visualization
Various visualizations were created throughout the project to represent the data insights. The bar chart for female participation ratios and other visual aids help in better understanding the trends and results derived from the data.

## Tools and Technologies Used
- Pandas for data manipulation.
- Matplotlib for data visualization.
- Python for data analysis and computation.
- Jupyter Notebook for executing and documenting the project.

## References
- Olympedia
- World Bank API documentation for population data..

## How to Use
To run the analysis, you need the datasets mentioned above. Simply execute the code cells in the Jupyter Notebook in the order they appear, and you will be able to reproduce the analysis and visualizations. However, I did not the datasets in the repository!
