# RMB Monthly Mini Challenge #3: Nowcast June

## Overview
The goal of this challenge is to nowcast the next CPI value as well as CPI sub-categories for the month of June.

## Project Structure
All files and the notebook are saved together in a sigle folder `RMB Monthly Mini Challenge #3 Nowcast June`.

## Datasets Used
In this project, I've used the following datasets:

1. `CPI_Historic_Values_Zindi_May_23.csv`: The CPI hitoric value of each category from `31-01-2022` to `31-05-2023`
    download from [here](https://zindi.africa/competitions/rmb-monthly-mini-challenge-3-nowcast-june/data)

2. `historical-data-sabor-June2023.csv`: Historical Data: South African Benchmark Overnight Rate (SABOR) and Overnight Foreign Exchange (FX) Rate, this file contains the overnight benchmark rates, as published by the South African Reserve Bank, updated at the end of each month. Please note that there is generally no overnight foreign exchange data on public holidays in the US
    download from [here](https://www.resbank.co.za/en/home/publications/publication-detail-pages/Financial-Markets/markets-data/SABOR-Historical-Data/Sabor)


### Hardware Requirements
In this project I've used my local machine.
The device specifications are:

- Device name:   `DESKTOP-BGDK0NV`
- Processor:     `11th Gen Intel(R) Core(TM) i5-1135G7 @ 2.40GHz   2.40 GHz`
- Installed RAM: `8.00 GB (7.65 GB usable)`
- Device ID:     `B6810134-C45B-4027-883E-F7A6CF21BABC`
- Product ID:    `00330-81492-34910-AA027`
- System type:   `64-bit operating system, x64-based processor`

## Running the Code
The notebook in this project is already chronologically ordered from the first cell to the last cell. To execute the notebook and reproduce the results, follow these steps:

1. Open the notebook file `CPI Prediction June` in your preferred Jupyter environment.
2. Start running the notebook from the very first cell and proceed sequentially, executing each subsequent cell in order.
3. Ensure that you have all the necessary dependencies and data files available as specified in the README.

Running the notebook in the correct chronological order is essential to maintain the flow of data processing, analysis, and modeling. 


## Expected Run Time
The expected run time for this notebook: 25s to 30s

## Results
The result of this notebook are the predicted values for sumbmission stored in the `Zindi_CPI_Predictions_June.csv` file.
After submitting this file we get the following scores:

- PUBLIC SCORE:  `0.897808164`

- PRIVATE SCORE: `0.281401815`


