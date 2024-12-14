# Cadastral Mapping Web App  

**Interactive Cadastral Mapping Tool** for viewing, analyzing, and managing parcel data. This web-based application provides advanced geospatial functionalities, enabling users to filter, search, and interact with cadastral layers seamlessly.  

## Features  

1. **Interactive Parcel Viewing**:  
   - Visualize cadastral parcels with detailed attributes.  
   - View parcel information dynamically when interacting with the map.  

2. **Filters by Parcel Size**:  
   - Filter parcels based on size thresholds to focus on specific datasets.  

3. **Search by Plate ID**:  
   - Quickly locate parcels by entering their Plate ID in the search bar.  

4. **Zoom and Pan**:  
   - Effortlessly zoom in and out or pan across the map to explore areas of interest.  

5. **Layer Interactions**:  
   - Enable or disable map layers for customized data visualization.  
   - Add or remove basemaps to change the map's background style.  

6. **Measurement Tools**:  
   - Measure distances and areas directly on the map for on-the-fly analysis.  

7. **Live Location Tracking**:  
   - Display your real-time location on the map with geolocation functionality.  

8. **Basemaps**:  
   - Choose from multiple basemap options (e.g., satellite imagery, street maps).  

9. **Search Button**:  
   - Use an intuitive search button to find parcels or locations instantly.  

## Technologies Used  

- **Frontend**: HTML, CSS, JavaScript  
- **Mapping Library**: [Leaflet.js](https://leafletjs.com/)  
- **QGIS**:qgis2web  
- **Hosting**: GitHub Pages  

## Live Demo  

Visit the live demo of the application: [Cadastral Mapping Web App](https://your-github-username.github.io/cadastral-mapping-web-app)  

## Installation  

If you'd like to run the application locally:  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-github-username/cadastral-mapping-web-app.git
   ```  

2. Navigate to the project directory:  
   ```bash
   cd cadastral-mapping-web-app
   ```  

3. Open the `index.html` file in your browser.  

## Usage  

1. Open the app in your browser.  
2. Use the toolbar to:  
   - Filter parcels by size.  
   - Search parcels by Plate ID.  
   - Add or remove layers and basemaps.  
   - Measure distances and areas on the map.  
3. Click the **Live Location** button to see your current location.  
4. Interact with parcels by clicking on them to view their attributes.  

## File Structure  

```
cadastral-mapping-web-app/  
├── index.html         # Main HTML file  
├── css/  
│   ├── style.css      # Custom styles  
├── js/  
│   ├── app.js         # Main JavaScript file  
│   ├── map-config.js  # Map configuration and layer setup  
├── data/  
│   ├── parcels.geojson  # GeoJSON file containing parcel data  
├── README.md          # Documentation file (this file)  
```  

## Contributing  

Contributions are welcome! If you find a bug or have a feature request, feel free to create an issue or submit a pull request.  

## License  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

## Acknowledgments  

- **[Leaflet.js](https://leafletjs.com/)** for the mapping library.  
- **GitHub Pages** for hosting the application.  
- OpenStreetMap contributors for basemap data.  

---
