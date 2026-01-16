<!-- =============================== -->
<!-- HERO / HEADER SECTION -->
<!-- =============================== -->

<div align="center" style="padding:40px 20px;">

<!-- Wallpaper banner -->
<img src="assets/wallpaper.jpg" alt="Project Wallpaper" width="100%" style="border-radius:12px; max-height:400px; object-fit:cover;" />

<!-- Logo overlay with border -->
<img src="assets/logo.png" alt="Logo" width="120" style="
    margin-top:-80px;
    border-radius:50%;
    border:4px solid #1f4e79;
    background-color:#ffffff;
    padding:5px;
    position:relative;
" />

<!-- Titles -->
<h1 style="color:#1f4e79; margin-top:10px;">Where Population Meets Carbon</h1>
<h3 style="color:#2f75b5; font-weight:400;">Europe’s Leading Countries (2021)</h3>
<p style="color:#555555;">Advanced Cartography · Climate Data Visualization · GIS Analysis</p>

</div>

---

<!-- =============================== -->
<!-- CONTENT SECTION -->
<!-- =============================== -->

## <span style="color:#1f4e79;">Project Overview</span>

<div style="background-color:#f0f4f8; padding:12px; border-left:4px solid #1f4e79; border-radius:6px;">
This project presents a **thematic choropleth map of greenhouse gas (GHG) emissions per capita across European countries**, combined with **proportional symbols representing the ten most populated European countries (2021)**.

Developed as part of the **Advanced Cartography** course, the map explores the **spatial relationship between population size and per-capita carbon emissions**, applying advanced cartographic design principles to ensure clarity, accuracy, and interpretability at the continental scale.

The visualization integrates **color-based thematic mapping** with **graduated symbols** to support comparative spatial analysis of climate-related indicators.
</div>

---

## <span style="color:#1f4e79;">Objectives</span>

<div style="background-color:#f9f9f9; padding:12px; border-left:4px solid #2f75b5; border-radius:6px;">
- Visualize **GHG emissions per capita** (tCO₂-e per capita) across Europe  
- Highlight the **ten most populated European countries** using proportional symbols  
- Apply **advanced cartographic principles** in thematic map design  
- Demonstrate appropriate **CRS selection, classification methods, and visual hierarchy**  
- Communicate climate-related spatial patterns in an **academically rigorous manner**  
</div>

---

## <span style="color:#1f4e79;">Data Sources</span>

<div style="background-color:#f0f4f8; padding:12px; border-left:4px solid #1f4e79; border-radius:6px;">
**Greenhouse Gas Emissions (per capita)**  
- United Nations Statistics Division  
- SDG Indicator 13.2.2 – Greenhouse gas emissions per capita  

**Population Data (2021)**  
- World Bank – Total Population  
- Indicator: SP.POP.TOTL  

**Basemap & Administrative Boundaries**  
- Esri, TomTom, Garmin, FAO, NOAA, USGS  
- OpenStreetMap contributors  

All datasets were **cleaned, harmonized, and joined at the country level** prior to cartographic visualization.
</div>

---

## <span style="color:#1f4e79;">Methodology</span>

<div style="background-color:#f9f9f9; padding:12px; border-left:4px solid #2f75b5; border-radius:6px;">

### <span style="color:#2f75b5;">1. Data Preparation</span>
- GHG and population datasets processed using **Microsoft Excel**  
- Population data filtered to extract the **ten most populated European countries**  
- Attribute joins performed to link statistical data with spatial boundaries  

### <span style="color:#2f75b5;">2. Projection / CRS Selection</span>
- A **Europe-appropriate projected coordinate reference system** was selected  
- Projection choice prioritized **area preservation and visual balance**, essential for choropleth mapping  

### <span style="color:#2f75b5;">3. Thematic Mapping</span>
- **Choropleth mapping** used for GHG emissions per capita  
- **Sequential color scheme** applied (darker = higher emissions)  
- **Proportional symbols** represent population size
</div>

---

## <span style="color:#1f4e79;">Cartographic Design Principles</span>

<div style="background-color:#f0f4f8; padding:12px; border-left:4px solid #1f4e79; border-radius:6px;">
- Data normalization using **per capita indicators**  
- Appropriate **classification scheme** for thematic clarity  
- Clear visual contrast between choropleth colors and proportional symbols  
- Balanced layout including **legend, scale bar, north arrow, and map elements**  
- Integration of **SDG 13 – Climate Action** thematic context  
</div>

---

## <span style="color:#1f4e79;">Tools & Software Used</span>

<div style="background-color:#f9f9f9; padding:12px; border-left:4px solid #2f75b5; border-radius:6px;">
| Software | Purpose |
|----------|---------|
| QGIS     | Spatial data processing & thematic mapping |
| ArcGIS Pro | Cartographic layout design & refinement |
| Microsoft Excel | Data cleaning, filtering & preparation |
</div>

---

## <span style="color:#1f4e79;">Map Output</span>

<div style="text-align:center; margin-top:12px;">
![Final Choropleth Map](outputs/final_map.png)
</div>

---

## <span style="color:#1f4e79;">Authorship</span>

<div style="background-color:#f0f4f8; padding:12px; border-left:4px solid #1f4e79; border-radius:6px;">
**Map Author:** Meenu Anil  
Master’s in Geospatial Analytics  
Advanced Cartography
</div>

---

## <span style="color:#1f4e79;">License</span>

<div style="background-color:#f9f9f9; padding:12px; border-left:4px solid #2f75b5; border-radius:6px;">
This project is intended for **academic and educational purposes only**.  
All data sources retain their original licenses.
</div>
