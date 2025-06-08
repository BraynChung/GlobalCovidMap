# 🌍 Interactive Geospatial Data Visualization: COVID-19 Analysis

![COVID-19 Geospatial Map](https://img.shields.io/badge/Map-COVID--19%20Analysis-blueviolet?style=for-the-badge)  
**Visualize the global impact of COVID-19 with interactive maps and geospatial insights.**

This project is an interactive geospatial data visualization and analysis tool focused on the global spread of COVID-19. Using Python, Pandas, Folium, and Geopy, it creates dynamic maps to display confirmed cases, recoveries, and deaths across countries, with a focus on geographic coordinates for precise visualization. Explore the data through heatmaps and marker clusters to uncover patterns and insights about the pandemic's global impact.

---

## 📊 Project Overview

This Jupyter Notebook project leverages geospatial data to create interactive visualizations of COVID-19 cases worldwide. It includes:

- **Geocoding**: Extracting latitude and longitude for countries using the `geopy` library.
- **Data Preparation**: Aggregating COVID-19 data (confirmed cases, recoveries, deaths) from a CSV dataset.
- **Interactive Visualizations**:
  - **Marker Cluster Map**: Displays death counts per country with clickable markers.
  - **Heatmap**: Visualizes the intensity of confirmed cases globally using a gradient-based heatmap.

The visualizations are powered by the `Folium` library, which generates interactive maps using Leaflet.js, making it easy to explore the data geographically.

---

## 🛠️ Features

- **Geocoding with Geopy**: Automatically fetches latitude and longitude for each country.
- **Data Aggregation**: Summarizes global COVID-19 data (confirmed, recovered, deaths) up to April 2022.
- **Interactive Maps**:
  - **Marker Clusters**: Zoomable map with markers showing death counts per country.
  - **Heatmap**: Visual representation of confirmed cases with adjustable radius and intensity.
- **Scalable Analysis**: Easily adaptable for other geospatial datasets or metrics.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/covid19-geospatial-analysis.git
   cd covid19-geospatial-analysis
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   Or manually install:
   ```bash
   pip install geopy pandas numpy matplotlib folium
   ```

3. **Download the Dataset**:
   - The project uses `countries-aggregated.csv`, which contains COVID-19 data (Date, Country, Confirmed, Recovered, Deaths).
   - Place the dataset in the `data/` folder or update the file path in the notebook.

4. **Run the Notebook**:
   ```bash
   jupyter notebook Interactive_Geospatial_Data_Visualisation_Covid_19.ipynb
   ```

---

## 📈 Usage

### Extract Coordinates
The notebook uses geopy to fetch latitude and longitude for each country in the dataset.  
Example: For "Tawau," it retrieves (4.2435206, 117.885331).

### Data Preparation
- Loads and aggregates COVID-19 data from `countries-aggregated.csv`.
- Groups data by country to compute maximum values for Confirmed, Recovered, and Deaths.

### Visualizations
- **Marker Cluster Map**: Run the cell under "Spatial Analysis with Folium" to generate a map with markers showing death counts.
- **Heatmap**: Run the cell under "Geographic Heatmap of Confirmed Cases" to create a heatmap of confirmed cases.

### Explore the Maps
- Open the generated HTML map files in a browser.
- Zoom, pan, and click markers to explore data interactively.

---

## 📂 Project Structure
```
covid19-geospatial-analysis/
├── Interactive_Geospatial_Data_Visualisation_Covid_19.ipynb  # Main Jupyter Notebook
├── data/
│   └── countries-aggregated.csv                             # COVID-19 dataset
├── requirements.txt                                         # Dependencies
└── README.md                                                # This file
```

---

## 🖼️ Visualizations

### 1. Marker Cluster Map
![Marker Cluster Map](https://github.com/user-attachments/assets/ab33dc45-61f6-4136-92c9-6bec33909c0a)

A global map with clustered markers, each displaying the total number of COVID-19 deaths for a country. Zoom in to see individual markers and click for details.

### 2. Heatmap of Confirmed Cases
![Heatmap of Confirmed Cases](https://github.com/user-attachments/assets/f44125b9-273b-487c-9712-9c6cc45ab74b)

A heatmap visualizing the density of confirmed COVID-19 cases worldwide, with color intensity representing case counts.

*Note: Replace placeholder images with actual screenshots of your maps for a more professional look.*

---

## 📚 Dataset
The dataset (`countries-aggregated.csv`) contains:

- **Columns**: Date, Country, Confirmed, Recovered, Deaths
- **Time Range**: January 22, 2020, to April 16, 2022
- **Source**: Aggregated global COVID-19 data (ensure to credit the original source if known, e.g., JHU CSSE or WHO)

---

## 💻 Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and aggregation
- **Geopy**: Geocoding for latitude and longitude
- **Folium**: Interactive map generation
- **Matplotlib**: Data visualization (optional for static plots)
- **Jupyter Notebook**: Interactive development environment

---

## 🤝 Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

---

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🌟 Acknowledgments

- **Geopy**: For providing geocoding services.
- **Folium**: For enabling interactive map visualizations.
- **OpenStreetMap**: For the map tiles used in visualizations.
- **Dataset Providers**: For the COVID-19 data (e.g., JHU CSSE, WHO, or other sources).

---

## 📬 Contact
Have questions or suggestions? Reach out!  

**GitHub**: BraynChung  
**Email**: braynchung88@gmail.com

---

*Stay curious, keep exploring, and let's map the world together!* 🌎
