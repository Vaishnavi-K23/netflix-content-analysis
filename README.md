# Netflix Content Analysis (Business Data Analytics Project)

## Overview

Streaming platforms rely heavily on data to decide **what content to produce, acquire, and promote**.
This project analyzes Netflix’s content catalog to uncover patterns in genres, release timing, countries of production, and content types.

The goal is to demonstrate how exploratory data analysis (EDA) can generate business insights from real-world data using Python.

---

## Objectives

This project answers key business questions such as:

* What type of content does Netflix produce more — Movies or TV Shows?
* Which countries contribute the most content?
* How has Netflix content production changed over time?
* Which genres dominate the platform?
* When does Netflix release the most content?

---

## Dataset

The dataset contains metadata about Netflix titles, including:

* Title
* Type (Movie or TV Show)
* Director
* Cast
* Country
* Release year
* Date added to Netflix
* Duration
* Rating
* Genre (listed_in)

This is a real-world dataset commonly used for analytics and visualization tasks.

---

## Data Cleaning

The dataset required preprocessing before analysis:

* Handled missing values in country, cast, and director columns
* Converted `date_added` to datetime format
* Extracted year and month from dates
* Standardized categorical fields
* Split multi-genre fields for analysis

---

## Exploratory Data Analysis

### Content Type Distribution

Analyzed the proportion of Movies vs TV Shows to understand Netflix’s content strategy.

### Content Growth Over Time

Studied how the number of titles added each year has changed as Netflix expanded globally.

### Country Analysis

Identified top countries producing Netflix content.

### Genre Analysis

Determined which genres are most common on the platform.

### Release Timing

Examined which months Netflix tends to add the most content.

Visualizations were created using:

* Pandas
* Matplotlib
* Seaborn

---

## Key Insights

* Netflix hosts significantly more Movies than TV Shows
* Content additions increased rapidly after 2015 (global expansion period)
* The United States contributes the largest share of content
* Drama and International content dominate the platform
* Netflix adds the most titles toward the end of the year

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## How to Run the Project

### 1. Clone repository

```bash
git clone https://github.com/Vaishnavi-K23/netflix-content-analysis.git
cd netflix-content-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## Skills Demonstrated

* Data cleaning and preprocessing
* Exploratory data analysis
* Data visualization
* Insight generation
* Business storytelling with data

---

## Future Improvements

* Recommendation system
* Popu
