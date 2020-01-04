# February-2015-Airline-Delays-Tweets-ETL

The purpose of this project was to perform an Extract-Transform-Load (ETL) process on airline flight performance data and customer tweet data from February 2015. The approach was to use the SQLAlchemy and Pandas modules in Python to extract and transform the data. SQLAlchemy was then used to load the transformed data into a PostgreSQL database.

## Questions

1. Identify the appropriate method(s) and perform the data extraction process.
2. Identify the appropriate method(s) and perform the data transformation process.
3. Identify the appropriate storage medium and perform the data loading process.

## Datasets

1. https://www.kaggle.com/usdot/flight-delays
2. https://www.kaggle.com/crowdflower/twitter-airline-sentiment

## Tasks

### Data Extraction

1. Import the flight performance data CSV files as Pandas data frames.
2. Import the customer tweet data SQLite database file as a Pandas data frame.
3. Inspect the data frames, and identify issues and inconsistencies.

### Data Transformation

1. Clean all data frames with flight performance data.
2. Clean the data frame with customer tweet data.
3. Perform transformations on all cleaned data frames.
4. Split select processed data frames into appropriate groups.

### Data Loading

1. Establish relationships between processed data frames and create a Entity Relationship Diagram (ERD).
2. Create a PostgreSQL database, and generate tables with the appropriate primary and foreign keys.
3. Populate the tables with information from the appropriate data frames.

## Results/Conclusions

1. https://github.com/mjknj18/February-2015-Airline-Delays-Tweets-ETL/blob/master/February_2015_Airline_Delays-Tweets_ETL_Main.ipynb