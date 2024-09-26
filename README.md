# World Happiness Report Data Processing (2020-2024)

This notebook processes and compiles data from the World Happiness Report (WHR) for the years 2020 to 2024. It extracts key indicators of happiness, adjusts for differences in data formats across the years, and creates a consolidated CSV file containing all relevant metrics, ready for analysis.

## Features
- **Data Extraction**: Reads and processes the World Happiness Report files for each year.
- **Consistency Handling**: Standardizes column names and structures data to ensure uniformity across all years.
- **Region Mapping**: Adds geographic information, mapping countries to sub-regions and broader regions.
- **Ranking Metrics**: Computes rankings for key happiness metrics within each year to facilitate comparative analysis.
- **Data Cleaning**: Removes irrelevant data points, corrects column names, and organizes columns for a clean final output.
- **CSV Export**: Generates a single CSV file (`WHR_2020_2024.csv`) containing all processed and consolidated data.

## Usage
1. Place the raw World Happiness Report files for the years 2020 to 2024 in the specified file paths.
2. Run the notebook to process the data files, perform necessary cleaning, and compute rankings.
3. The final output is saved as a CSV file named `WHR_2020_2024.csv`.

## Requirements
- Python 3.x
- Pandas library

## Output
The notebook generates a CSV file with the following key columns:
- `Year`, `Region`, `Sub-Region`, `Country Name`
- `Ladder Score`, various explanatory factors, and their rankings
- Upper and lower whiskers for confidence intervals
- Sub-Region and general region mappings

This processed data allows for in-depth analysis of global happiness trends over time.
