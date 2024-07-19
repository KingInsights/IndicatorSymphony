# Project Introduction: Integrating Moving Average (MA) Crossover and Average Directional Index (ADX) for Stock Analysis

## Overview

This project seeks to construct a dynamic and thought-provoking stock screening tool by integrating a chosen pair of technical indicators: the Moving Average (MA) Crossover and the Average Directional Index (ADX). By combining these indicators, we aim to enhance signal accuracy through the complementary strengths of trend identification and trend strength analysis. The project involves data collection, indicator calculation, signal generation, and result visualization for a selection of stocks, with the primary stock data sourced from Yahoo Finance and focusing on FTSE 250 companies.

## Table of Contents

- Introduction
- Setup
- Running the Project
  - Running the Notebook Locally with Jupyter Lab
  - Running the Notebook Online with Google Colab
- Acknowledgments
- License

## Introduction

Technical analysis involves using historical price and volume data to forecast future price movements. Among the myriad of technical indicators available, the MA Crossover and ADX are highly respected for their ability to assess market conditions. This project integrates these two indicators to identify potential buy and sell signals, aiming to improve signal reliability through combined trend identification and trend strength analysis. By calculating and analyzing these indicators for a selection of stocks, we seek to create a robust stock screening tool that helps traders make more informed decisions.

## Setup

### Choose Your Environment

You can run this project either locally using Jupyter Lab or online using Google Colab. Follow the appropriate setup instructions below:

### Running the Notebook Locally with Jupyter Lab

1. **Install Jupyter Lab**:
   - Open your command line (Terminal on macOS/Linux or Command Prompt on Windows).
   - Install Jupyter Lab using pip:
     ```
     pip install jupyterlab
     ```

2. **Download the Project**:
   - Download the project files from the repository. You can download it as a ZIP file from GitHub and extract it to your desired directory.
   - Alternatively, you can clone the repository using Git:
     ```
     git clone https://github.com/your-username/project-repo.git
     cd project-repo
     ```

3. **Start Jupyter Lab**:
   - Navigate to the project directory in your command line:
     ```
     cd path/to/your/project/directory
     ```
   - Start Jupyter Lab:
     ```
     jupyter lab
     ```

4. **Open Jupyter Lab**:
   - Your default web browser will open Jupyter Lab, typically at `http://localhost:8888/lab`.

5. **Upload Files (if necessary)**:
   - In the Jupyter Lab interface, you can upload files by clicking the "Upload" button in the file browser pane on the left. Select the files you need from your local machine.

6. **Open the Notebook**:
   - In the Jupyter Lab interface, navigate to the project directory.
   - Open the `[notebook file]` notebook file.

### Running the Notebook Online with Google Colab

1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on `File` > `Upload notebook` and select the `[notebook file]` file you downloaded.

## Running the Project

Once you have chosen your environment (Jupyter Lab or Google Colab) and set it up, follow these steps to run the project:

### Run the Notebook Cells

Execute each cell in the notebook sequentially to perform the following tasks:

1. **Step 1: Import Libraries and Define Helper Functions**
   - Import necessary libraries and define a function to suppress print statements.

2. **Step 2: Define Functions for Indicator Calculations**
   - Create functions to calculate moving averages and ADX indicators.

3. **Step 3: Analyze Stocks for Indicators**
   - Define a function to download stock data, calculate indicators, detect buy/sell signals, and check criteria.

4. **Step 4: Load Stock Tickers**
   - Load stock tickers from a CSV file.

5. **Step 5: Process Each Stock and Export Results**
   - Analyze each stock, store results that meet criteria in a DataFrame, and export the results to a CSV file.

6. **Step 6: Calculate and Print the Detailed Results**
   - Calculate the total number of tickers, the number of tickers meeting the criteria, and the percentage of tickers that meet the criteria.
   - Print the results and determine if the percentage of shares meeting the criteria falls within the desirable range (5-20%).

7. **Step 7: Define Functions for Plotting and Printing Financial Data**
   - `print_financial_data`: Prints basic financial data for a given ticker.
   - `plot_ma_adx`: Plots the stock price with moving averages and ADX indicators.

8. **Step 8: Display Financial Data and Plots for Selected Stocks**
   - Iterate through all stocks that meet the criteria, plot the stock price and indicators, and print detailed financial information.

## Acknowledgments

Thank you to everyone who supported and contributed to this project.

## License

This project is licensed under the MIT License.
