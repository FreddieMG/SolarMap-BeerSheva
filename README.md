# SolarMap-BeerSheva
A geospatial analysis pipeline for detecting and tracking solar panel installations in Be'er Sheva using high-resolution GIS tiles and deep learning-based segmentation. This repository includes data processing, model integration, and visualization tools for analyzing solar adoption trends across different building types and years.

### Files and Descriptions

#### 📓 Project.ipynb
A Jupyter Notebook containing the main codebase for data processing, GIS tile scraping, machine learning modeling, and visualization.

#### 🌍 building_usage_types_map.html
An interactive **KeplerGL map** visualizing different building usage types (e.g., residential vs. public) based on GIS data.

#### 📂 buildings.csv
A raw dataset containing building information in Be’er Sheva, including location coordinates (latitude, longitude, ITM), usage type, and structural details.

#### 📂 buildings_processed_final.csv
A preprocessed version of the `buildings.csv` dataset that includes additional computed features, such as tile coordinates for GIS scraping and inferred solar panel presence.

#### 🌞 solar_installation_map_enhanced.html
An enhanced **KeplerGL map** visualizing the presence of solar installations across Be’er Sheva, integrating GIS imagery with building data.

#### 📜 LICENSE
Contains the license governing the use and distribution of this project.

---

This repository supports the study of solar panel adoption trends by leveraging GIS data and machine learning. Contributions and discussions are welcome!
