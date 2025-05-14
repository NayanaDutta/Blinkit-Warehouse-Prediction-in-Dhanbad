# Blinkit-Warehouse-Prediction-in-Dhanbad
A data-driven project to predict optimal Blinkit warehouse locations in Dhanbad using clustering, population, and geospatial analysis.
This project focuses on identifying optimal warehouse locations for Blinkit in the Dhanbad zone using a data-driven approach. The objective is to enhance delivery efficiency by strategically positioning warehouses in high-demand, underserved areas. The analysis utilizes three key datasets: Area_name.csv containing region names, Dhanbad_locations.csv providing geographical coordinates and existing warehouse status, and Population_data.csv detailing area-wise population figures.

By integrating these datasets, we assessed current service gaps and demand concentration. Locations without existing warehouses were filtered, and their coordinates were processed using K-Means clustering to group them based on geographic proximity and population density. The clustering output helped predict three optimal locations for new warehouses, targeting regions with higher population and no current warehouse coverage.

Visualizations were created to display both existing and predicted warehouses on a map, allowing for clear comparison and validation. This approach not only ensures wider coverage but also supports Blinkit's fast delivery goals by reducing travel distance and improving supply chain responsiveness.

In summary, the project demonstrates how geospatial and demographic data, combined with machine learning, can inform strategic infrastructure planning, enabling Blinkit to scale effectively and serve customers in Tier-2 cities like Dhanbad with greater speed and efficiency.
