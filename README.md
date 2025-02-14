# E-Commerce Public Data Analysis with Python - Dicoding

![E-Commerce Data Dashboard](dashboard.gif)

[E-Commerce Data Dashboard Streamlit App](https://data-analyst-project.streamlit.app/)

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)

## Overview

This project focuses on public data related to e-commerce through data analysis and visualization. It comes with code for exploratory data analysis (EDA), data wrangling, and an interactive data exploration dashboard called Streamlit. Analyzing data from the E-Commerce Public Dataset is the goal of this project.

## Project Structure

- `dashboard/`: This directory contains dashboard.py which is used to create dashboards of data analysis results.
- `data/`: Directory containing the raw CSV data files.
- `notebook.ipynb`: This file is used to perform data analysis.
- `notebook_ID.ipynb`: notebook.ipynb in Indonesian.
- `README.md`: This documentation file.

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/ahmadnurhidayat/data-analyst-project.git
```

2. Go to the project directory

```
cd data-analyst-project
```

3. Install the required Python packages by running:

```
pip install -r requirements.txt
```

## Usage

1. **Data Wrangling**: Data wrangling scripts are available in the `notebook.ipynb` file to prepare and clean the data.

2. **Exploratory Data Analysis (EDA)**: Explore and analyze the data using the provided Python scripts. EDA insights can guide your understanding of e-commerce public data patterns.

3. **Visualization**: Run the Streamlit dashboard for interactive data exploration:

```
cd data-analyst-project/dashboard
streamlit run dashboard.py
```

Access the dashboard in your web browser at `http://localhost:8501`.

## Data Sources

The project uses E-Commerce Public Dataset from [Belajar Analisis Data dengan Python's Final Project](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view) offered by [Dicoding](https://www.dicoding.com/).
