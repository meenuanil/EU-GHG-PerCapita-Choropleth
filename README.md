<!-- ===================== -->
<!-- HERO HEADER SECTION -->
<!-- ===================== -->

<div align="center" style="background-image:url('assets/wallpaper.jpg');
background-size:cover;
background-position:center;
padding:60px 20px;
border-radius:12px;
animation: fadeIn 2s ease-in-out;">

<img src="assets/logo.png" alt="Logo" width="110" style="margin-bottom:20px;" />

<h1 style="color:#ffffff; font-weight:700;">
Where Population Meets Carbon
</h1>

<h3 style="color:#e0e0e0; font-weight:400;">
Europe’s Leading Countries (2021)
</h3>

<p style="color:#d0d0d0;">
Advanced Cartography · Climate Data Visualization · GIS Analysis
</p>

</div>

<!-- ===================== -->
<!-- ANIMATION STYLES -->
<!-- ===================== -->

<style>
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
@keyframes slideUp {
  from { opacity: 0; transform: translateY(25px); }
  to { opacity: 1; transform: translateY(0); }
}
.section {
  animation: slideUp 1.4s ease-in-out;
}
</style>

---

<div class="section">

## <span style="color:#1f4e79;">Project Overview</span>

This project presents a **thematic choropleth map of greenhouse gas (GHG) emissions per capita across European countries**, combined with **proportional symbols representing the ten most populated European countries in 2021**.

Developed as part of the **Advanced Cartography** course, the map explores the **spatial relationship between population size and per-capita carbon emissions**, applying advanced cartographic design principles to ensure clarity, accuracy, and interpretability at the continental scale.

The visualization integrates **color-based thematic mapping** with **graduated symbols** to support comparative spatial analysis of climate-related indicators.

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Objectives</span>

- Visualize **GHG emissions per capita** (tCO₂-e per capita) across Europe  
- Highlight the **ten most populated European countries** using proportional symbols  
- Apply **advanced cartographic principles** in thematic map design  
- Demonstrate appropriate **CRS selection, classification methods, and visual hierarchy**  
- Communicate climate-related spatial patterns in an **academically rigorous manner**

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Data Sources</span>

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

<div class="section">

## <span style="color:#1f4e79;">Methodology</span>

### <span style="color:#2f75b5;">1. Data Preparation</span>
- GHG and population data processed using **Microsoft Excel**  
- Population data filtered to extract the **ten most populated European countries**  
- Attribute joins performed to link statistical data with spatial boundaries  

### <span style="color:#2f75b5;">2. Projection / CRS Selection</span>
- A **Europe-appropriate projected coordinate reference system** was selected  
- Projection choice prioritized **area preservation and visual balance**, essential for choropleth mapping  

### <span style="color:#2f75b5;">3. Thematic Mapping</span>
- **Choropleth mapping** used for GHG emissions per capita  
- **Sequential color scheme** applied (darker tones = higher emissions)  
- **Proportional symbols** used to represent population magnitude  

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Cartographic Design Principles Applied</span>

- Data normalization using **per capita indicators**  
- Appropriate **classification scheme** for thematic clarity  
- Clear visual contrast between choropleth colors and proportional symbols  
- Balanced layout including **legend, scale bar, north arrow, and map elements**  
- Integration of **SDG 13 – Climate Action** context  

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Tools & Software Used</span>

| Software | Purpose |
|--------|--------|
| QGIS | Spatial data processing and thematic mapping |
| ArcGIS Pro | Cartographic layout design and refinement |
| Microsoft Excel | Data cleaning and preparation |

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Academic Context</span>

This project was completed as part of the **Advanced Cartography** course and demonstrates:
- Application of **thematic cartography techniques**
- Critical decision-making in **CRS selection and data classification**
- Use of cartography as a tool for **climate data communication**

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Relevance & Interpretation</span>

By combining **population magnitude** with **per capita emissions**, the map provides insight into:
- Spatial disparities in carbon emissions across Europe
- Relationships between population size and environmental impact
- Evidence-based perspectives relevant to **climate policy and sustainability research**

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Map Output</span>

![Final Choropleth Map](outputs/final_map.png)

</div>

---

<div class="section">

## <span style="color:#1f4e79;">Authorship</span>

**Map Author:** Meenu Anil  
Master’s in Geospatial Analytics  
Advanced Cartography

</div>

---

<div class="section">

## <span style="color:#1f4e79;">License</span>

This project is intended for **academic and educational purposes only**.  
All data sources retain their original licenses.

</div>
