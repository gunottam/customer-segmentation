# Customer Segmentation

This repository contains an end-to-end customer segmentation analysis by Gunottam Maini.

## Overview

Customer segmentation is the process of partitioning a customer base into groups of individuals that share similar characteristics. This project uses transactional data from a UK-based online retail store to cluster customers based on their purchasing behavior.

It aims to help businesses understand their customers better and target their marketing strategies more effectively.

## Dataset

The dataset utilized in this analysis is the **E-Commerce Data** which contains transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

_(Note: Data files are excluded from the repository via `.gitignore` to prevent large file uploads. To reproduce, download the dataset from Kaggle and place it in an `input` directory.)_

## Project Structure

- `customer-segmentation.ipynb`: The main Jupyter Notebook containing the data exploration, preprocessing, and machine learning models (K-Means clustering, PCA, etc.).
- `.gitignore`: Configured to ignore virtual environments, raw `.csv` data, and unnecessary cache files.
- `input/data.csv`: (Not tracked) The location where you should place the downloaded dataset.

## How to Run

1. Clone the repository.
2. Initialize and activate a Python virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install the necessary packages (pandas, scikit-learn, matplotlib, seaborn, jupyter):
   ```bash
   pip install pandas scikit-learn matplotlib seaborn jupyter
   ```
4. Extract the Kaggle E-Commerce Data to the `input/` folder so it resides at `input/data.csv`.
5. Launch Jupyter Notebook:
   ```bash
   jupyter notebook customer-segmentation.ipynb
   ```

## License

MIT License
