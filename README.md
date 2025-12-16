# An Analysis of the Determinants of Open Unemployment in Central Java Using the SAR Method

This project analyzes the determinants of **Open Unemployment Rate** in **Central Java** using a **Spatial Autoregressive (SAR)** model.

The study incorporates spatial effects to capture regional dependencies between districts/cities, providing a more realistic analysis compared to classical regression models.

## Project Overview
- Analysis of open unemployment rate in Central Java
- Identification of socioeconomic determinants
- Spatial econometric approach using SAR
- Examination of spatial dependence across regions

## Data
The dataset consists of regional-level data from districts/cities in Central Java, including:
- Open Unemployment Rate
- Socioeconomic and demographic variables
- Spatial information represented through a spatial weight matrix

Data preprocessing includes:
- Data cleaning and transformation
- Construction of spatial weight matrix
- Exploratory data analysis

## Methodology
This project applies the **Spatial Autoregressive (SAR)** model to account for spatial autocorrelation in unemployment data.

The SAR model allows the unemployment rate in one region to be influenced by neighboring regions, making it suitable for regional economic analysis.

## Results
The analysis provides:
- Estimated effects of key determinants on unemployment
- Evidence of spatial dependence in unemployment rates
- Interpretation of regional spillover effects

## Tools & Libraries
- Python 
- Pandas / GeoPandas
- NumPy
- Matplotlib / Seaborn

