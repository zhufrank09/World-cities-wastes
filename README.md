# Global Urban Waste Management

## About
This repository was created for **English 105** at the **University of North Carolina at Chapel Hill**.  
It contains data and analysis related to how municipal solid waste (MSW) is generated, managed, and diverted in cities around the world.

The purpose of this project is to:
- Examine waste generation trends across global cities,
- Evaluate the effectiveness of waste diversion methods like recycling and composting,
- Raise awareness of urban environmental management challenges.

## What's in this Repository?
- `city_level_data_0_0.csv` – Raw dataset of global solid waste statistics.
- `diversion_rate_subset.csv` – A filtered subset focusing on waste diversion rates by city.
- `urban_waste_analysis.ipynb` – Python notebook for cleaning, analyzing, and visualizing the data.
- `README.md` – This documentation file.

## Data Provenance
The dataset originates from the [World Bank Group](https://datacatalog.worldbank.org/search/dataset/0039596), specifically the *What a Waste* global database.  
It includes city-level information on:
- Annual MSW generation (tons/year),
- Waste composition,
- Treatment and disposal methods,
- Environmental impacts.

The data was downloaded, cleaned, and formatted for analysis. No values were modified beyond standard cleaning (e.g., fixing column names, removing null entries).

## Why This Data?
Urban waste management is a critical global issue, impacting public health, climate change, and sustainable development.  
By analyzing waste statistics city-by-city, we can:
- Identify major contributors to global waste generation,
- Recognize leaders in waste diversion practices,
- Inspire policies that promote recycling, composting, and other sustainable methods.

**Potential users of this data include:**
- Environmental policy analysts,
- Sustainability researchers,
- Urban planners and city officials,
- Curious individuals interested in global environmental challenges.

## Key Findings
- Countries with the highest total waste output.
- Cities with the best and worst diversion rates.
- Top 10 waste-generating cities globally.
- Observed links between economic development and waste treatment practices.

## How to Use
1. Open `urban_waste_analysis.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run through the cleaning and analysis workflow.
3. View exported datasets (`.csv`) for reuse, further visualization, or reporting.

*Note:* Data subsets were created using the `.to_csv()` method in Python for easier sharing and further analysis.

## What's Next?
This project could be expanded by:
- Exploring correlations between waste generation, GDP per capita, and population density.
- Visualizing diversion rates geographically using GIS tools.
- Studying the impact of policy interventions on diversion success rates.
