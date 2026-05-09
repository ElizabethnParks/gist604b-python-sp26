# [Python GIS and Containerization]

**Student:** [Elizabeth Parks]
**Course:** GIST 604B – Open Source GIS
**Module:** [MODULE #3 Python GIS and Containerization]
**University of Arizona**

## Project Description
This project focused on using Python for GIS and geospatial data analysis by using Jupyter notebooks to understand the code and pandas and GeoPandas to implement the functions from the corresponding src and python files. I worked with tabular, vector, and raster datasets using libraries such as pandas, GeoPandas, and Rasterio. I validated functions using pytest and practiced version control through GitHub and Codespaces.

## Tools and Technologies
-Python
-Jupyter Notebooks
-Pandas
-GeoPandas
-Rasterio

## What I Did
- Understand and run code within Jupyter notebooks.
- Implement functions into python scripts.
- Complete a full raster analysis workflow using Rasterio

## How to View / Run
- View the guided GIS workflow and raster analysis in the Jupyter notebooks.
- Run the Pythin scripts in the src. folder to execute the Pandas and GeoPandas functions.
- Use pytest in the terminal to test and validate the implemented functions.

## Repository Structure

    .
    ├── README.md
    ├── .devcontainer
    │   ├── devcontainer.json
    │   ├── Dockerfile
    ├── data/
    │   ├── neighborhood_samples.geojson
    │   ├── temperature_readings.csv
    │   └── weather_stations.csv
    ├── notebooks/
    │   ├── pandas/
    │   ├── geopandas/
    │   └── rasterio/
    ├── src/
    │   ├── pandas_basics.py
    │   ├── geopandas_basics.py
    │   └── download_real_data.py
    ├── tests/
    │   ├── test_pandas_basics.py
    │   └── test_geopandas_basics.py
    ├── pyproject.toml
    └── uv.lock

## Notes

- Notebooks are for exploration and learning.
- Final implementations are in `src/`.
- Tests validate pandas and GeoPandas functionality.
- Rasterio work is completed entirely in the notebook.
