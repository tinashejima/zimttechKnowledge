# DHIS2 Data Preparation and Integration Notebooks

This repository contains Jupyter Notebooks that support data preparation, transformation, and pushing of aggregate data to DHIS2. These scripts are designed for health data teams working on data integration and reporting, particularly in the context of DATIM and DHIS2 platforms.

## Included Files

### 1. DATIM FILE Data manupulation and mapping.ipynb

This notebook focuses on:
- Reading completed DATIM files obtained from the MOBILE backup manipulation process
- Cleaning and formatting raw data
- Mapping data values to appropriate DHIS2 codes
- Transforming the data into a structure suitable for DHIS2 import
- Generating output files ready for upload into DHIS2

*Note: Once the DATIM file is marked as completed from the mobile backup process, it is imported into this notebook. The script then handles all data transformation automatically.*

### 2. pushing aggregate data to DHIS2.ipynb

This notebook demonstrates:
- Formatting aggregate data into the required DHIS2 format
- Constructing payloads for DHIS2 API
- Pushing data to DHIS2 using Python (via HTTP POST requests)
- Handling authentication and basic error responses

## Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required Python libraries:
  - `pandas`
  - `requests`
  - `json`
  - `os`

Install them using pip:

```bash
pip install pandas requests

## How to Use

    Clone or download this repository.

    Open the notebooks using Jupyter Notebook or Jupyter Lab.

    Modify any configuration (e.g. file paths, API URLs, credentials) as needed.

    Run each cell step by step to manipulate, map, and push data to DHIS2.

Notes

    Ensure DHIS2 credentials and API access are correctly configured.

    Test on a demo or staging server before pushing to production DHIS2.

Author

Developed by: Zim-TTECH DHIS2 Specialist
