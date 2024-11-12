# imerg-data-categorization
Climatedataanalysis
# IMERG Rainfall Data Categorization

This project processes and categorizes IMERG rainfall data (from the Integrated Multi-satellite Retrievals for Global Precipitation Measurement) into different event categories. The data is processed from .nc files and saved as CSV files containing accumulated rainfall and categorized rain event types.

## Features

- Processes daily IMERG rainfall data from March to October 2022.
- Categorizes rain events into four types:
  - Background Rain: 0 to 7.8 mm
  - Moderate Rain Events: 7.8 to 39.4 mm
  - Intense Rain Events: 39.4 to 136.6 mm
  - Extreme Rain Events: 136.6 mm and above
- Saves processed data as both `.nc` and `.csv` files.
- Generates a log file of the processing steps.

## Setup Instructions

Follow the instructions below to set up and run this project.

### Prerequisites

Ensure that you have Python 3.7 or above installed. The following libraries are required:
- `xarray`
- `pandas`
- `numpy`
- `cftime`
- `glob`

You can install the dependencies using:

```bash
pip install -r requirements.txt
