
# Distribution of Medical Facilities in California

This project provides an in-depth look at the distribution of healthcare facilities across counties in California, 
highlighting population-based adjustments to reveal potential disparities in healthcare accessibility.

## Project Overview

The objective of this project is to explore and visualize the geographical distribution of healthcare facilities in 
California and to analyze how these distributions vary when adjusted for population. This approach uncovers areas that 
may be underserved relative to their population, helping to inform decisions in healthcare resource allocation.

## Data and Methodology

### Data Cleaning
The data cleaning process, detailed in [`DataCleaning.ipynb`](./DataCleaning.ipynb), includes steps such as:
- Handling missing values
- Standardizing formats
- Removing duplicates
- Transforming data for analysis and visualization

This process ensures that the data is accurate and ready for meaningful analysis.

### Tableau Visualization
The primary insights from the data are visualized using Tableau, which enables an interactive exploration of healthcare 
facility distribution across California's counties. Key elements of the dashboard include:

1. **Number of Facilities by County**: This choropleth map highlights the concentration of healthcare facilities in 
   each county. The counties with higher populations, like Los Angeles, have more facilities overall.

2. **Population-Adjusted Distribution**: An additional view provides insights into facility distribution after adjusting 
   for population. This helps to identify disparities, showing that while Los Angeles has a large number of facilities, 
   the population-adjusted view indicates a more uniform distribution across the state, revealing counties that might 
   have fewer facilities per capita.

3. **Treemap and Bubble Charts**:
   - **Treemap**: Displays the absolute count of facilities, with Los Angeles County significantly highlighted.
   - **Bubble Chart**: Shows facility distribution with and without population adjustment, emphasizing the change in 
     relative availability per capita.

![Data Visualization](./02_content/tableau_workbook/Healthcare_facilities_vizualization.jpg)

You can view the interactive Tableau dashboard [here on Tableau Public](<[Insert_Your_Tableau_Public_Link_Here](https://public.tableau.com/app/profile/craig.albuquerque3286/viz/Healthcare_facilities_vizualization/Distribution)>).

These visualizations provide a comprehensive view of healthcare accessibility across California.

## Technologies Used
- **Python (Jupyter Notebook)**: Data cleaning and preprocessing
- **Tableau**: Visualization and dashboard design
- **Libraries**: Pandas, NumPy, Matplotlib (if applicable)

## Insights
- Counties with large populations naturally have a greater number of facilities, but this doesn’t always correspond to 
  equitable access.
- Adjusting for population size reveals that some less populated counties might actually have more facilities per capita, 
  while others are underserved.

## Usage
To explore this project:
1. Clone this repository to your local machine.
2. Review the data cleaning steps in [`DataCleaning.ipynb`](./DataCleaning.ipynb).
3. Open `Healthcare_facilities_vizualization.twbx` in Tableau for a local view, or visit the [Tableau Public link](<Insert_Your_Tableau_Public_Link_Here>) 
   for an online, interactive experience.
4. The cleaned data files are available in the `data` folder, and raw files in the `data_raw` folder.

## Acknowledgments
This project leverages OpenStreetMap and Tableau to provide geographical and data visualization insights.
