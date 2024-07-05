# India 2024 Election Results: Streamlit Visualization

This repository contains a Streamlit application for visualizing the cleaned dataset of the 2024 Indian election results. The data is scraped from the Election Commission of India and presents a concise summary of the election outcomes by state and political party.

## Repository Structure

- `app.py` - The main Streamlit application code.
- `Statewise_Partywise_Election_Results.csv` - The cleaned dataset containing election results.
- `README.md` - This readme file.
- `EDA.ipynb` - Jupyter Notebook Containing EDA on the dataset.
- 'Election Results Scraping.ipynb' - Jupyter Notebook Containing the codes for scraping the data and some transformations applied
- `screenshots/` - Directory containing screenshots of the application (if available).

## Streamlit Application

The Streamlit application provides an interactive interface for exploring the election results by state and party.

### Features

- **State-wise Election Results:** Visualizes the number of seats won by different political parties in each state.
- **Party-wise Summary:** Summarizes the total seats won by each political party across all states.
- **Interactive Filters:** Allows users to filter results by state or party for focused analysis.


## Dataset

The dataset includes the following columns:

| Column Name | Description                              |
|-------------|------------------------------------------|
| **State**   | Name of the state or union territory     |
| **Party**   | Name of the political party              |
| **Won**     | Seats officially won by the party        |

### Data Source

The dataset was scraped using **Beautiful Soup** and **Selenium** from the [Election Commission of India results website](https://results.eci.gov.in/PcResultGenJune2024/index.htm).

### Author

Gajendra Sharma - [LinkedIn](https://www.linkedin.com/in/gajendra-sharma) | [GitHub](https://github.com/gajendrasharma-github)
