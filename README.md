# 🎨 Montreal Arts & Culture Venues Visualization 🎭

This repository contains a Python-based geospatial analysis and visualization project that explores arts and culture venues in Montreal, Canada. The project uses data from OpenStreetMap (OSM) and creates a fishnet grid to visualize the spatial distribution of venues such as museums, theaters, galleries, and arts centers across the city. The code includes data retrieval from OSM using the Overpass API, data processing and transformation with GeoPandas and Shapely, and data visualization with Matplotlib.

## 🌟 Key Features

- Retrieval of arts and culture venues data from OpenStreetMap using the Overpass API.
- Creation of a fishnet grid to divide the city of Montreal into grid cells.
- Geospatial analysis to count the number of venues by type within each grid cell.
- Visualization of the spatial distribution of venues on a map with a custom legend.
- Highlighting of key places of interest on the map.

## 💡 Usage

This project is intended for individuals interested in geospatial analysis, urban planning, cultural studies, and data visualization. It provides an example of how to use open-source geospatial tools to analyze and visualize geographic data. The code can be adapted to explore other types of amenities or geographic regions.

## 📦 Dependencies

- GeoPandas
- Shapely
- Overpy
- Matplotlib
- NumPy
- Pandas

## 🛠️ Installation

1. Clone the repository to your local machine by opening the terminal and pasting the following:
```git clone https://github.com/Sakeeb91/montreal-venues-visualization/```

2. Change directory to the cloned repository:
```cd montreal-venues-visualization```

3. Install the required Python libraries using the `requirements.txt` file: ```pip install -r requirements.txt```

4. Open the Jupyter Notebook using Jupyter Notebook or JupyterLab.

## 🌐 Data Source

The project uses data from the following sources:

-OpenStreetMap: Data on cultural and arts venues in Montreal is obtained using the Overpass API.
-Shapefile: A shapefile (LIMADMIN.shp) containing the administrative boundaries of Montreal is used to create a grid for spatial analysis. The file was downloaded from http://donnees.ville.montreal.qc.ca/dataset/polygones-arrondissements

## 📄 License

This project is open-source and available for educational and non-commercial use. Please provide proper attribution if you use or adapt the code for your own projects. This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss any changes or improvements.

## 📧 Contact

For any questions or feedback, please contact the repository owner.

## 🙏 Acknowledgments

* OpenStreetMap contributors for providing valuable data on cultural and arts venues. 🗺️
* The GeoPandas, Shapely, Overpy, and Matplotlib communities for developing and maintaining the libraries used in this project. 📊🛠️
