# ETL Pipeline for GitHub Indian Users Data

This repository contains an **ETL pipeline** that extracts data from a Kaggle dataset about Indian GitHub users, transforms the data, and prepares it for analysis or storage.

## Project Setup

### Requirements

Before running the ETL pipeline, ensure that the following dependencies are installed:

- **PySpark** for distributed data processing.
- **Kaggle API** to download datasets directly from Kaggle.

Install the required dependencies using the following commands:

```bash
# Install Kaggle and PySpark
!pip install kaggle
!pip install pyspark



## Project Structure

ETL_Pipeline_Github_Indian_User_Data/
│
├── kaggle.json                  # Kaggle API credentials (upload your own)
├── github-indian-users-deep-data.zip  # Raw Kaggle dataset
├── github_indian_users.csv      # Extracted dataset
├── cleaned_github_indian_users.csv  # Transformed dataset
├── etl_pipeline.py              # Python script for the ETL pipeline
└── README.md                    # This README file
