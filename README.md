# Chicago Crime Data Analysis (2024–2025)

## Overview
An exploratory data analysis of a Chicago crime dataset covering April 2024 to April 2025, using Python and pandas. The project examines crime patterns across type, time, location, and arrest outcomes, supported by 40 written insights and comparisons to real news coverage.

## Dataset Note
This dataset was provided by my professor for a coursework exercise. Its structure (Case Number, IUCR code, FBI code, Community Area, coordinates) closely resembles Chicago's public crime records, though I have not independently verified its original source.

## Tech Stack
- Python
- pandas
- numpy
- matplotlib
- seaborn
- folium (for geographic heatmapping)

## What I Did
- Parsed and cleaned the Date column into a proper datetime format
- Filled missing values in location description, coordinates, and related fields using mode-based imputation
- Extracted new features from the date, including month, day, day of week, hour, and AM/PM
- Converted relevant columns to categorical data types for cleaner analysis
- Analyzed crime patterns by type, time of day, day of week, month, and location
- Compared arrest outcomes across crime types and locations
- Built a geographic heatmap of crime hotspots using folium
- Wrote 40 insights interpreting each visualization, several cross-referenced with real news articles

## Key Findings
- Theft was the most common crime type, followed by battery
- Crimes occurred throughout the day, with a notable spike around midday and again near midnight
- Only a small proportion of cases resulted in an immediate arrest
- Crime volume was fairly evenly distributed across days of the week
- Streets, apartments, and residences were the most frequent crime locations, each with a different dominant crime type

## What I Learned
This project strengthened my pandas skills for data cleaning, feature engineering from datetime fields, and exploratory analysis. I also practiced interpreting real-world data patterns and communicating findings clearly through visualizations, while cross-checking my interpretations against outside sources for context.

## Note on Heatmap Visualization
The geographic heatmap was built using folium but could not be re-captured for this repository at the time of writing due to a local storage/environment issue. A screenshot will be added once available.
