# GitHub Data Cleaning Project

![Alt text](https://media.thoughtspot.com/35707/1669949290-data-cleaning-social.png)


## Overview

This project focuses on collecting and cleaning data from GitHub repositories using scraping techniques. The primary goal is to ensure the quality and reliability of the extracted information. The tasks include data analysis, handling missing values, addressing outliers, removing duplicates, normalizing data, and ensuring overall data consistency.

## Project Structure
```
project-root/
│
├── data/
│ ├── raw_data/
│ │ ├── github_data.csv # Raw data collected from Github
│ │
│ ├── cleaned_data/
│ ├── cleaned_github_data.csv # Cleaned data ready for analysis
│
├── notebooks/
│ ├── data_collection.ipynb # Jupyter notebook for data collection
│ ├── data_cleaning.ipynb # Jupyter notebook for data cleaning
│
├── src/
│ ├── scraping_utils.py # Python module with functions for data scraping
│ ├── cleaning_utils.py # Python module with functions for data cleaning
│
├── reports/
│ ├── data_cleaning_report.md # Detailed report on data cleaning process and results
│
├── requirements.txt # Python dependencies for the project
├── README.md # Project documentation
```
## Project Components

- **Data Collection:** The `notebooks/data_collection.ipynb` notebook contains the code for collecting data from GitHub using scraping techniques.

- **Data Cleaning:** The `notebooks/data_cleaning.ipynb` notebook details the steps taken to clean the collected data, including handling missing values, outliers, duplicates, and ensuring data consistency.

- **Source Code:** The `src/` directory contains Python modules (`scraping_utils.py` and `cleaning_utils.py`) with functions specific to data scraping and cleaning.

- **Reports:** The `reports/data_cleaning_report.md` file provides a detailed report on the data cleaning process, problems identified, and the applied cleaning techniques.

## How to Use

1. Clone this repository: `git clone https://github.com/your-username/your-repository.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter notebooks in the `notebooks/` directory for data collection and cleaning.

## Contributing

Feel free to contribute to this project by opening issues, proposing new features, or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

