# Python-Beginner-Project
This is a simple Python project about "Sleeping &amp; Occupations".

### Table of Contents
1. [Project Description](#project-description)
2. [Usage](#usage)
3. [Technical Details](#technical-details)
4. [Contributors](#contributors)
5. [Contact](#contact)

### Project Descriptions
I'll be using the "Google Play Store Apps" dataset. These two datasets are made available as .csv files and will be transformed throughout the code before being loaded into a SQLite database.

### Usage
This ETL pipeline processes app data from the Google Play Store dataset and loads it into an SQLite database. Here’s how to run and use the pipeline:

1. **Data Extraction**: The script reads data from the `data/google_play_store.csv` file.
2. **Data Transformation**: It cleans, filters, and processes the raw data for analysis.
3. **Data Loading**: The processed data is saved to a database (`database/google_play_store.db`).

### Technical Details
This project uses several technologies and libraries:

- **Python 3.8+** for programming
- **Pandas** for data manipulation and transformation
- **SQLAlchemy** to interact with the SQLite database
- **SQLite** as the database to store cleaned data

**ETL Steps:**
1. **Extract**: Load CSV files as DataFrames using Pandas.
2. **Transform**: Clean data by handling missing values, normalizing columns, and applying data types.
3. **Load**: Insert transformed data into an SQLite database for further analysis.

### Contributors
To contribute to this project, you can fix the repository and submit a pull request.

### Contact
For questions, feedback, or suggestions, feel free to reach out:
- **Email**: chuncy0331@gmail.com
