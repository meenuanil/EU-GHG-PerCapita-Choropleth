<!-- ===================== -->
<!-- HERO / HEADER SECTION -->
<!-- ===================== -->

<div align="center">

<img src="assets/wallpaper.jpg" alt="Project background" width="100%" style="border-radius:10px;" />

<br><br>

<img src="assets/logo.png" alt="Project logo" width="110" />

<h1>Where Population Meets Carbon</h1>

<h3>Europe’s Leading Countries (2021)</h3>

<p>
Advanced Cartography · Climate Data Visualization · GIS Analysis
</p>

</div>

---

## Project Overview

This project presents a **thematic choropleth map of greenhouse gas (GHG) emissions per capita across European countries**, integrated with **proportional symbols representing the ten most populated European countries in 2021**.

Developed as part of the **Advanced Cartography** course, the map investigates the **spatial relationship between population magnitude and per capita carbon emissions**, applying advanced cartographic design principles to support clear, accurate, and interpretable spatial analysis at the continental scale.

The visualization combines **color-based thematic mapping** with **graduated symbol representation** to enhance comparative interpretation of climate-related indicators.

---

## Objectives

- Visualize **GHG emissions per capita** (tCO₂-e per capita) across Europe  
- Highlight the **ten most populated European countries** using proportional symbols  
- Apply **advanced cartographic principles** in thematic map design  
- Demonstrate appropriate **CRS selection, classification methods, and visual hierarchy**  
- Communicate climate-related spatial patterns in an **academically rigorous** manner  

---

## Data Sources

The project uses **authoritative, internationally recognized datasets**:

**Greenhouse Gas Emissions (per capita)**  
- United Nations Statistics Division  
- SDG Indicator 13.2.2 – Greenhouse gas emissions per capita  

**Population Data (2021)**  
- World Bank – Total Population  
- Indicator: SP.POP.TOTL  

**Basemap and Administrative Boundaries**  
- Esri, TomTom, Garmin, FAO, NOAA, USGS  
- OpenStreetMap contributors  

All datasets were **cleaned, harmonized, and joined at the country level** prior to cartographic visualization.

---

## Methodology

### Data Preparation
- Tabular GHG and population datasets were processed using **Microsoft Excel**  
- Population data were filtered to identify the **ten most populated European countries**  
- Attribute joins were performed to link statistical datasets with spatial boundaries  

### Projection and CRS Selection
- A **Europe-appropriate projected coordinate reference system** was selected  
- Projection choice prioritized **area preservation and visual balance**, essential for choropleth representation  

### Thematic Mapping
- **Choropleth mapping** was used to represent GHG emissions per capita  
- A **sequential color scheme** was applied, where darker tones indicate higher emissions  
- **Proportional symbols** were used to represent population size, ensuring visual distinction without obscuring the thematic layer  

---

## Cartographic Design Principles Applied

- Data normalization using **per capita indicators**  
- Appropriate **classification scheme** to ensure thematic clarity  
- Clear visual contrast between choropleth colors and proportional symbols  
- Balanced layout including **legend, scale bar, north arrow, and map elements**  
- Integration of **SDG 13 (Climate Action)** thematic context  

---

## Tools and Software Used

| Software | Purpose |
|--------|--------|
| QGIS | Spatial data processing and thematic mapping |
| ArcGIS Pro | Cartographic layout design and refinement |
| Microsoft Excel | Data cleaning, filtering, and preparation |

---

## Academic Context

This project was completed as part of the **Advanced Cartography** course and demonstrates:

- Application of **thematic cartography techniques**  
- Critical decision-making in **projection selection and data classification**  
- Use of cartography as an analytical tool for **climate data communication**  

---

## Relevance and Interpretation

By combining **population magnitude** with **per capita emissions**, the map provides insights into:

- Spatial disparities in carbon emissions across Europe  
- The relationship between population size and environmental impact  
- Evidence-based perspectives relevant to **climate policy and sustainability research**  

---

## Map Output

```markdown
![Final Choropleth Map](outputs/final_map.png)
