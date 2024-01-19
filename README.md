# Clash-Royale-Data-Analysis
## Overview

This project aims to analyze and model Clash Royale match data to gain insights into various aspects of gameplay and predict match outcomes. 

## Data

The dataset used in this project contains information about 124 individual matches, including player decks, card choices, match outcomes, and other relevant features. The dataset is in CSV format and is named `CRDatason.csv`.

## Project Structure

The project is organized as follows:

- **data/:** Contains the dataset (`clash_royale_data.csv`).
- **notebooks/:** Jupyter notebooks for data exploration, analysis, and machine learning model development.
- **src/:** Source code for data processing, feature engineering, and machine learning model implementation.
- **visualizations/:** Visualization outputs and plots generated during the analysis.

## Important Note

The data used in this project was obtained from the Clash Royale API, which provides battle history for the last 25 battles. Due to API key sharing restrictions (prohibited by the provider), the API key used to fetch this data has been removed from the repository. If you wish to reproduce or extend this analysis using your own Clash Royale account data, follow the steps below:

1. Acquire a Clash Royale API key: Visit the [official Clash Royale API website](https://developer.clashroyale.com/) to obtain your API key. Note that sharing API keys is against the terms of service.

2. Update API key and player ID: Open the scripts or notebooks in the `src/` directory and replace the placeholder for the Clash Royale API key and player ID with your own information.

3. Data Storage: The data was stored in a CSV file after every 25 battles to manage API rate limits. You may choose to store the data differently based on your needs.

By following these steps, you can use your own API key and player ID to fetch and analyze your Clash Royale battle data.

**Note:** Be mindful of API usage policies and terms of service provided by Clash Royale when working with the API.
