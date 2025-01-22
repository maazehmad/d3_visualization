# d3_visualization
# D3 Visualization Dashboard Project

## Overview
This project is a data visualization dashboard built using **D3.js**, designed to showcase interactive and dynamic visual representations of datasets. The dashboard includes various visualizations such as timelines, force-directed graphs, treemaps, and geographic maps, providing an intuitive and insightful way to explore the data.

---

## Features
- **Interactive Dashboards**: Includes multiple visualizations such as:
  - Force-Directed Graph
  - Timeline Visualization
  - Treemap Visualization
  - Geographic Map
- **Data Integration**: Visualizes data from CSV files to enable seamless updates and scalability.
- **Responsive Design**: Styled using a custom CSS file to ensure compatibility across devices and browsers.
- **Reusable Components**: Modular design for easy extension and customization.

---

## Project Structure
```
project_root/
|— aggregated_tb1.csv            # Dataset for visualization
|— aggregated_tb2.csv            # Dataset for visualization
|— dashboard.html              # Main dashboard entry point
|— forcedirected.html           # Force-directed graph visualization
|— geographicmap.html          # Geographic map visualization
|— timeline.html               # Timeline visualization
|— treemap.html                # Treemap visualization
|— treemap_dataset.csv         # Dataset for treemap
|— style.css                   # Styling for visualizations
|— screenshots/               # Screenshots of visualizations
    |— visualization1.png
    |— visualization2.png
|— docs/                      # Documentation and reports
    |— dav_project_final.docx
```

---

## Getting Started

### Prerequisites
- **Web Browser**: Any modern browser (e.g., Chrome, Firefox, Edge)
- **Web Server** (optional): For local hosting, use tools like Python's `http.server` or Node.js' `http-server`.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/d3-visualization-dashboard.git
   ```
2. Navigate to the project directory:
   ```bash
   cd d3-visualization-dashboard
   ```
3. Open the desired HTML file in your browser:
   ```bash
   open dashboard.html
   ```
   Or serve the project locally:
   ```bash
   python -m http.server
   ```
   Then navigate to `http://localhost:8000` in your browser.

---

## Usage
- Open `dashboard.html` to explore the main visualization dashboard.
- Interact with individual visualizations such as the timeline or treemap by opening their respective HTML files (e.g., `timeline.html`, `treemap.html`).
- Modify datasets (CSV files) to customize the visualizations as needed.

---

## Datasets
This project uses the following datasets:
- `aggregated_tb1.csv`
- `aggregated_tb2.csv`
- `grouped_by_country (copy).csv`
- `treemap_dataset.csv`

Each dataset can be updated or replaced to reflect new data while maintaining functionality.

---

## Screenshots
Here are some examples of the visualizations included in the project:

### Force-Directed Graph
![Force-Directed Graph](screenshots/visualization1.png)

### Geographic Map
![Geographic Map](screenshots/visualization2.png)







