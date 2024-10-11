# MongoDB Data Analysis

## Overview

This project uses MongoDB for data manipulation and analysis. It involves importing data, conducting exploratory analysis, and using aggregation pipelines to extract insights. Leveraging PyMongo and Pandas, this project showcases the capabilities of NoSQL databases for handling complex queries and operations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Part 1: Database and Jupyter Notebook Set Up](#part-1-database-and-jupyter-notebook-set-up)
- [Part 2: Update the Database](#part-2-update-the-database)
- [Part 3: Exploratory Analysis](#part-3-exploratory-analysis)
- [Part 4: Aggregation Pipeline](#part-4-aggregation-pipeline)

## Installation

To set up the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/noSQL-challenge.git
   cd noSQL-challenge
2. Install the required packages: pip install -r requirements.txt
3. Ensure MongoDB is installed and running. Follow the official MongoDB installation guide if you haven't set it up yet.

## Usage 


1: **Database and Jupyter Notebook Set Up**
Import the dataset:

mongoimport --db uk_food --collection establishments --file /path/to/establishments.json --jsonArray

2: **Run Jupyter Notebook**
-Navigate to the NoSQL_setup_starter.ipynb file and run the cells to set up the database and verify the data.

## Part 2: Update the database

1. **Run Jupyter notebook** 
Navigate to the NoSQL_analysis_starter.ipynb file and run the cells to update the database with new data.

## Part 3: Exploratory Analysis

1. **Run Jupyter notebook**
   -Navigate to the NoSQL_analysis_starter.ipynb file and run the cells to perform exploratory data analysis, such as finding establishments with a specific hygiene score or located in a specific area.


## Part 4: Aggregation Pipeline

1. **Run Jupyter notebook**
   -Navigate to the NoSQL_analysis_starter.ipynb file and run the cells to create and execute aggregation pipelines. For example, find the top 5 establishments with a rating value of 5, sorted by the lowest hygiene score, nearest to a specific location.


## Project Structure: 
noSQL-challenge/
│
├── Resources/
│   └── establishments.json
├── NoSQL_setup_starter.ipynb
├── NoSQL_analysis_starter.ipynb
├── README.md
└── requirements.txt

-Resources/establishments.json: The dataset used for the project.
-NoSQL_setup_starter.ipynb: Jupyter Notebook for setting up the database and importing data.
-NoSQL_analysis_starter.ipynb: Jupyter Notebook for performing data analysis and aggregation.






