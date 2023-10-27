# Cloud Hosted Notebooks


## Getting Started

To get started with the project, you will need to have Python and the following Python libraries installed:

- pandas
- numpy
- matplotlib

You can install these libraries using pip or conda. You will also need to have software installed to run and execute a Jupyter Notebook.

## Running the Code

To run the code, open the `exercise_merging.ipynb` notebook in Jupyter Notebook and follow the instructions for each exercise. The code is designed to be run in order, as each exercise builds on the previous one.

## Data Processing Steps

This project involves processing data using Python and the Pandas library. The data processing steps are as follows:


- Ingest county-level data on arrests from California `ca`, county population data `ncp` into the cloud notebook (Ingest stage)

- Perform basic data inspection such as checking the number of rows and columns, data types, summary statistics, etc. for dataset `ca`. (EDA stage) 

- Group the `ncp` data by one or more columns and aggregate metrics like mean, max etc (EDA)

- Identify and handle missing or erroneous data in the dataset `ncp` (EDA) 

- Filter the data based on year and state, create new filtered dataset `ncp_ca_2009` (EDA)

- Join the arrest dataset `ca` with population dataset `ncp_ca_2009`, creating new dataset `data_2009` (EDA) 

- Generate new columns `violent_arrest_rate_2009` and `drug_arrest_rate_2009` with calculation in the dataset `data_2009` (EDA)

- Follow similar steps for year 2018, creating new dataset `data_2018` (EDA)

- Create various data visualizations like histograms, scatter plots, box plots etc (EDA)
