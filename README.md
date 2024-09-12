# IMDB Movie Dataset Analysis

## Project Overview
This project involves an in-depth analysis of the IMDB movie dataset using SQL queries and pandas in Python. The analysis is performed in a Jupyter notebook, combining the power of SQL for data querying and pandas for data manipulation and analysis. Various aspects of the movie industry are explored, including earnings, ratings, runtime, budget, and genre statistics.

## Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [File Descriptions](#file-descriptions)
4. [Usage](#usage)
5. [Analysis Overview](#analysis-overview)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Installation
To run this project, you'll need to have Python installed along with the following libraries:
- pandas
- sqlite3
- matplotlib
- numpy
- jupyter

You can install these dependencies using pip:
```
pip install pandas sqlite3 matplotlib numpy jupyter
```

## Dataset
The analysis uses the IMDB movie dataset stored in an SQLite database named 'IMDB.sqlite'. This database contains three main tables:
1. IMDB: Contains general information about movies (e.g., title, rating, runtime)
2. genre: Contains genre information for each movie
3. earning: Contains earnings data for movies (domestic and worldwide)

## File Descriptions
- `imdb_analysis.ipynb`: Jupyter notebook containing the analysis code and results
- `IMDB.sqlite`: SQLite database file containing the IMDB movie dataset

## Usage
To run the analysis:
1. Clone this repository
2. Ensure you have all required dependencies installed
3. Place the 'IMDB.sqlite' file in the same directory as the notebook
4. Open the `imdb_analysis.ipynb` file in Jupyter Notebook or JupyterLab
5. Run the cells in the notebook to perform the analysis

## Analysis Overview
This project combines SQL queries and pandas to analyze various aspects of the IMDB movie dataset. The analysis includes:

1. Highest-grossing movie identification
2. Most voted movie analysis
3. Longest-running movie identification
4. Profit analysis (including highest net profit movie)
5. Least budgeted movie identification
6. Year-wise highest-grossing movie analysis
7. Genre-wise budget percentage analysis
8. Genre-wise earning percentage analysis

## Results
Key findings from the analysis include:

1. The highest-grossing movie's rating
2. The most voted movie's name and rating
3. The longest-running movie's name and runtime
4. The movie with the highest net profit
5. The least budgeted movie with the highest net profit
6. Year-wise highest-grossing movies
7. Budget percentage distribution across genres (with pie chart)
8. Earning percentage distribution across genres (with pie chart)

Detailed results and visualizations can be found in the Jupyter notebook.

