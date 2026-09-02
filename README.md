# Interactive Researcher Profile & STEM Data Web Application

An interactive web application built with Streamlit, Pandas, and NumPy designed to display researcher profiles, handle dynamic publication uploads with real-time text filtering, and provide interactive exploratory widgets across multiple STEM datasets.

## Overview
This application serves as an interactive portfolio interface and analytical web dashboard. It allows users to dynamically load academic publication data, filter records on the fly, visualize dynamic bar chart trends, and interactively slice multi-domain STEM datasets (Physics, Astronomy, and Meteorology) using live slider controls.

## Key Features & Functionality
- **Dynamic Profile Management:** Displays structured researcher profile details alongside custom media branding.
- **CSV Data Processing & Filtering:** Enables CSV uploading with live keyword search filtering across all DataFrame columns using lambda functions.
- **Dynamic Trend Analytics:** Automatically parses uploaded schemas for temporal variables (`Year`) to generate interactive bar charts.
- **STEM Data Exploration Hub:** 
  - **Physics Module:** Energy range filtering ($0.0 - 10.0\text{ MeV}$) using `pd.Series.between()`.
  - **Astronomy Module:** Magnitude brightness slice-and-dice controls.
  - **Weather Module:** Multi-variable joint range filtering (Temperature and Humidity percentage).

## Tech Stack
- **Web Framework:** Streamlit
- **Data Manipulation:** Pandas, NumPy
- **Language:** Python 3.x
- **Environment:** Ubuntu Linux, VS Code, Git/GitHub

## Project Structure
```text
├── app.py              # Main Streamlit application pipeline
├── requirements.txt    # Application dependencies
└── README.md           # Repository documentation
