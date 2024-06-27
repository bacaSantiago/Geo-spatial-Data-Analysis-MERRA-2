# Geo-spatial Data Analysis: MERRA-2

---

## Overview

The Geo-spatial Data Analysis project focuses on utilizing the Modern-Era Retrospective analysis for Research and Applications, Version 2 (MERRA-2) dataset to extract insights from meteorological data. The dataset, introduced in 1980, incorporates modern observational data, including hyperspectral radiance, microwave observations, and GPS-Radio Occultation datasets, providing a comprehensive resource for meteorological research.

This project delves into the analysis of October 19, 2005, during Hurricane Wilma, leveraging the extensive dataset provided by MERRA-2. Through NetCDF format files, the project aims to explore geospatial data using multi-dimensional variables, allowing for detailed examination of Hurricane Wilma's impact across spatial and temporal dimensions.

---

## Key Features

1. **Global Surface and Sea Level Pressure Evolution**: Visualizes the surface pressure (PS) and sea level pressure (SLP) for each of the 8 3-hour time periods across the world region using subplots.

2. **Jet Stream at 300 hPa Across the Globe**: Graphs the jet stream at 300 hPa height for each of the 8 3-hour time periods globally.

3. **Hurricane Wilma's Evolution**: Investigates Hurricane Wilma's evolution throughout the day, focusing on the Caribbean area, using sea level pressure (SLP) and relative humidity fields.

4. **Mexico City Temperature Variation**: Examines temperature variation throughout the day for Mexico City, analyzing data from the surface to the 'top' of the atmosphere.

5. **City Temperatures Profiles: London, New York, Sydney, Mérida**: Plots temperature profiles for selected cities at different time periods, showcasing temperature evolution throughout the day.

6. **Horizontal Wind Speed Distribution**: Generates histograms for the magnitude of horizontal velocity at 00:00 hours, providing insights into wind speed distribution across vertical levels.

7. **Extra: GIF**: Creates a GIF illustrating the evolution of relative humidity throughout the day during Hurricane Wilma.

---

## Dependencies:
- Python 3.x
- `matplotlib`: For plotting graphs and visualizations.
- `numpy`: For numerical calculations and array manipulation.
- `netCDF4`: For reading NetCDF format files containing MERRA-2 data.
- `cartopy`: For mapping and geographical features.
- `imageio`: For creating GIF animations.
- `warnings`: For handling warnings.
- `IPython.display`: For displaying images and animations in Jupyter notebooks.

**Resources:**
- MERRA2_data.n4.IMG (MERRA-2 dataset from October 19, 2005 in NetCDF format)

---

This project offers a comprehensive analysis of meteorological data, demonstrating the capabilities of geospatial data analysis and visualization techniques in understanding complex weather phenomena such as hurricanes.