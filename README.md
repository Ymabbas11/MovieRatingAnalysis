# Movie Rating Analysis Project

## Overview
The **Movie Rating Analysis Project** is a comprehensive data analysis and visualization project that examines trends in movie ratings. The project leverages raw and processed datasets, Python programming, and advanced visualization tools like Power BI to deliver insights into factors contributing to movie success.

## Table of Contents
1. [Project Structure](#project-structure)
2. [Setup and Installation](#setup-and-installation)
3. [Data Overview](#data-overview)
4. [Analysis Process](#analysis-process)
5. [Visualizations](#visualizations)
6. [How to Contribute](#how-to-contribute)
7. [License](#license)

---

## Project Structure
The project directory is organized as follows:

```
MovieRatingAnalysis/
|
|-- movie-rating-analysis/
|   |-- requirements.txt       # Python dependencies
|   |-- .gitignore             # Git configuration file
|   |
|   |-- data/                  # Datasets
|   |   |-- raw/               # Raw data
|   |   |   |-- movie_ratings_raw.csv
|   |   |
|   |   |-- processed/         # Processed data
|   |       |-- movie_ratings_processed.xlsx
|   |
|   |-- notebooks/             # Jupyter Notebooks
|   |   |-- MovieSuccess.ipynb
|   |
|   |-- visualizations/        # Visualization outputs
|       |-- presentations/
|       |   |-- movie_analysis_presentation.pptx
|       |
|       |-- powerbi/
|           |-- movie_analysis_dashboard.pbix
|
|-- .DS_Store                  # MacOS metadata (ignore)
|-- __MACOSX/                  # MacOS metadata (ignore)
```

---

## Setup and Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Power BI Desktop (for .pbix files)
- Jupyter Notebook (for `.ipynb` files)

### Steps to Set Up
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd movie-rating-analysis
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook to view or run the analysis:
   ```bash
   jupyter notebook notebooks/MovieSuccess.ipynb
   ```
4. Open the Power BI dashboard for visualizations:
   - Locate `movie_analysis_dashboard.pbix` in `visualizations/powerbi/` and open it in Power BI Desktop.

---

## Data Overview

### Raw Data
- **File**: `data/raw/movie_ratings_raw.csv`
- **Description**: Contains raw data on movie ratings, including information such as movie titles, release dates, genres, and viewer ratings.

### Processed Data
- **File**: `data/processed/movie_ratings_processed.xlsx`
- **Description**: Preprocessed data cleaned and prepared for analysis, including added features and structured data for machine learning or statistical exploration.

---

## Analysis Process

The main analysis is conducted using the `MovieSuccess.ipynb` Jupyter Notebook. Key steps include:

1. **Data Cleaning**:
   - Handle missing values.
   - Remove duplicate records.
   - Format and standardize data fields.

2. **Exploratory Data Analysis (EDA)**:
   - Identify trends in genres, ratings, and release years.
   - Analyze distribution of ratings and correlations with other factors.

3. **Feature Engineering**:
   - Create new features, such as average rating by genre.
   - Normalize numerical features for modeling.

4. **Visualization**:
   - Generate graphs and plots for insights (e.g., boxplots, histograms).

5. **Modeling (Optional)**:
   - Prepare datasets for predictive modeling to analyze what contributes to high ratings.

---

## Visualizations

### Power BI Dashboard
- **File**: `visualizations/powerbi/movie_analysis_dashboard.pbix`
- **Description**: Provides interactive visualizations for exploring the dataset, including:
  - Genre trends.
  - Rating distributions.
  - Yearly comparisons.

### Presentation
- **File**: `visualizations/presentations/movie_analysis_presentation.pptx`
- **Description**: A PowerPoint presentation summarizing key findings from the analysis, designed for stakeholders.

---

## How to Contribute

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push them to your fork.
4. Submit a pull request explaining your changes.

---


