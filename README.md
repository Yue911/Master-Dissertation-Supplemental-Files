# Accessibility of Regent Street and its Impact on Retail Property Rents
# Project Overview

This project is supervised by Professor Nicolas Holliman from King’s College London (KCL) and involved in the KPMG BODS Dissertation Scheme. The topic is inspired by the "Future of Regent Street (2024)" project, a collaboration between the Crown Estate and Westminster City Council. The study examines transportation and green space accessibility in Regent Street from both static and dynamic perspectives, along with social and retail property characteristics, and explores how these factors influence retail rents.

## 1. Source Code

The source code consists of three IPynb files:

- **1-web_crawler**: Collects retail property information from Rightmove.
- **2-BODS_position**: Collects real-time bus positions every 20 minutes.
- **3-main_analysis**: Contains all analyses in this study (available in Releases).

## 2. List of HTML Maps and Charts in This Repository

- **[Heat map of bus stops in London](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/heatmap_bus_stops.html)**

- **[Heat map of bus stops in Regent Street](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/heatmap_bus_stops_regent.html)**

- **[Heat map of tube stations in London](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/heatmap_tube_stations.html)**

- **[Heat map of tube stations in Regent Street](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/heatmap_tube_stations_regent.html)**

- **[Heat map of retail properties](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/heatmap_properties.html)**

- **[BODS raw data on July 19](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0719.html)**

- **[BODS raw data on July 20](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0720.html)**

- **[BODS raw data on July 21](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0721.html)**

- **[BODS raw data on July 22](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0722.html)**

- **[BODS raw data on July 23](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0723.html)**

- **[BODS raw data on July 24](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0724.html)**

- **[BODS raw data on July 25](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_interactive_map_0725.html)**

- **[Comparison of 10 and 20-minute isochrones obtained by Open Service Route (Folium map)](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/OpenServiceRoute_interactive_map_folium.html)**

- **[Comparison of 10 and 20-minute isochrones obtained by Open Service Route (Plotly chart)](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/OpenServiceRoute_interactive_map_plotly.html)**

- **[Line chart showing the number of buses within Regent Street over time](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_Number_of_Buses_in_Regent_Area_over_Time.html)**

- **[Line chart showing the 20-minute isochrones area in Regent Street over time](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/BODS_20_min_Isochrone_Area_over_Time.html)**

- **[Road network in Regent Street](https://github.kcl.ac.uk/pages/k23031223/YueMa_k23031223_NicolasHolliman_SupplementalFile_2023-24/html_map_chart/regent_road_network.html)**

## 3. Exported Datasets During the Main Analysis (CRS of all GeoDataFrames: EPSG:4326)

- **study_region_QGIS**: Shapefile of the study region exported from QGIS.
- **borough_gdf**: GeoDataFrame of London boroughs with road betweenness centrality.
- **model_gdf**: GeoDataFrame for spatial regression (HPM).
- **ors_cycling_isochrone_gdf**: GeoDataFrame of 10 and 20-minute cycling isochrones from Open Route Service.
- **ors_driving_isochrone_gdf**: GeoDataFrame of 10 and 20-minute driving isochrones from Open Route Service.
- **ors_walking_isochrone_gdf**: GeoDataFrame of 10 and 20-minute walking isochrones from Open Route Service.
- **properties_gdf**: GeoDataFrame of property features.
- **properties_gdf_with_isochrones**: GeoDataFrame of property features with isochrone areas added.
- **regression_gdf**: GeoDataFrame for spatial regression (transformed variables).
- **rightmove_london_commercial_properties**: Retail property information collected from Rightmove.
- **regent_street_shops**: Shop information collected from the Regent Street website.

## 4. BODS_realtime_position_api

Raw data collected with the BODS API using a bounding box (every 20 minutes).

## 5. BODS_realtime_position

Bus positions within Regent Street (every 20 minutes).

## 6. PPT(brief)

This version of the presentation is used for reporting to CUSP and the Crown Estate.
