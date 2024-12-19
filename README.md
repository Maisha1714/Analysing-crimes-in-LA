# Los Angeles Crime Analysis with Heatmap Visualization

## Overview

This project analyzes crime data in Los Angeles to identify patterns in criminal behavior and visualize crime hotspots using heatmaps. The insights can help law enforcement agencies allocate resources more effectively and improve public safety.

## Features

- **Data Cleaning and Preprocessing**: Handles missing and invalid values in the dataset.
- **Exploratory Data Analysis (EDA)**: Provides insights into crime patterns over time, space, and victim demographics.
- **Heatmap Visualization**: Visualizes high-crime areas on an interactive map using `folium`.
- **Dynamic Visualizations**: Includes bar charts, line plots, and histograms for better understanding of crime trends.

## Technologies Used

- **Python**: Primary programming language.
- **Libraries**:
  - `pandas`: For data manipulation and cleaning.
  - `matplotlib` and `seaborn`: For creating static visualizations.
  - `folium`: For generating interactive maps and heatmaps.
  - `streamlit` (optional): For building a web-based dashboard.
  
## Dataset

The dataset is sourced from a modified version of the Los Angeles Open Data platform. It includes the following fields:
- `DATE OCC`, `Date Rptd`: Dates of crime occurrence and reporting.
- `TIME OCC`: Time of crime occurrence.
- `AREA NAME`: The 21 geographic areas of LAPD's jurisdiction.
- `Crm Cd Desc`: Crime descriptions.
- Victim demographics: `Vict Age`, `Vict Sex`, and `Vict Descent`.
- `Weapon Desc`: Weapons used (if applicable).
- `LOCATION`: Street address of the crime.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Maisha1714/Analysing-crimes-in-LA.git
   cd Analysing-crimes-in-LA


## Visualizations
  **## Temporal Analysis**: Crime trends over time.

  **##Spatial Analysis**: Bar chart of crime frequency by area.

  **##Heatmap**: Interactive map showing crime density.

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request for improvements.


## Contact
Author: jannatulferdous201018@gmail.com
GitHub: [Maisha1714](https://github.com/Maisha1714)
