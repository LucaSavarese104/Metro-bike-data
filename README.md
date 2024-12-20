# Metro Bikeshare Data Analysis Project

## Overview

The **Metro Bikeshare Data Analysis Project** is designed to analyze bikeshare data and provide insights into trip patterns, station demand, and passholder trends. Using a dimensional modeling approach, the project organizes the data into a structured format to enable analytics and visualization.

---

## Objectives

### **Business Requirements**
- **Peak Times Analysis**: Understand when bike usage is highest.
- **Station Demand**: Identify the busiest and least used stations.
- **Passholder Trends**: Explore how different passholder types contribute to bike usage.

### **Functional Requirements**
- **Data Loading**: Import data into the analysis tool.
- **Data Cleaning**: Remove missing or inconsistent values.
- **Time-Based Analysis**: Group trips by hour/day to find peak usage times.
- **Station Analysis**: Count trips starting and ending at each station.


---

## Datasets

The following datasets are utilized in this project:
1. **[Metro Bikeshare Trip Data](https://bikeshare.metro.net/about/data/)**:
   - [2024 3rd Quarter trip data used](https://bikeshare.metro.net/wp-content/uploads/2024/10/metro-trips-2024-q3.zip)
2. **[Metro Bikeshare Station Data](https://bikeshare.metro.net/wp-content/uploads/2024/10/metro-bike-share-stations-2024-10-01.csv)**

## Data Requirements
Data sources: **[Metro Bikeshare Trip Data](https://bikeshare.metro.net/about/data/)**


**Data Columns**: trip_id, duration, start_time, end_time,start_station, start_kiosk_name, start_region, start_lat, start_lon, end_station, end_kiosk_name, end_region, end_lat, end_lon, trip_route_category, passholder_type, and bike_type

**Number of Rows**: 131760