<!-- HERO SECTION -->
<div align="center">

<img src="assets/wallpaper.jpg" width="100%" style="border-radius:12px;" />

<br><br>

<img src="assets/logo.png" width="120" />

<h1>Where Population Meets Carbon</h1>

<h3>Europe’s Leading Countries (2021)</h3>

<p>
Advanced Cartography · Thematic Mapping · Climate Data Visualization
</p>

</div>

---

<!-- FADE-IN EFFECT USING SVG -->
<div align="center">

<svg width="0" height="0">
  <defs>
    <style>
      .fade {
        animation: fadeIn 2s ease-in-out;
      }
      @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
      }
    </style>
  </defs>
</svg>

</div>

---

## 📌 Project Overview
<div class="fade">

This project presents a **thematic choropleth map of greenhouse gas (GHG) emissions per capita across European countries**, combined with **proportional symbols representing the ten most populated European countries (2021)**.

Developed as part of the **Advanced Cartography** course, the map explores the **spatial relationship between population size and per-capita carbon emissions** using advanced cartographic design principles.

The visualization integrates **color-based thematic mapping** and **graduated symbols** to enhance interpretability and support **comparative spatial analysis** at the continental scale.

</div>

---

## 🎯 Objectives
- Visualize **GHG emissions per capita** (tCO₂-e per capita) across Europe  
- Highlight the **ten most populated European countries** using proportional symbols  
- Apply **advanced cartographic principles** in thematic map design  
- Demonstrate appropriate **CRS selection, classification methods, and visual hierarchy**  
- Communicate climate-related spatial patterns in an **academically rigorous** manner  

---

## 🗂️ Data Sources

**Greenhouse Gas Emissions (per capita)**  
- United Nations Statistics Division  
- SDG Indicator **13.2.2 – GHG emissions per capita**

**Population Data (2021)**  
- World Bank – Total Population  
- Indicator: **SP.POP.TOTL**

**Basemap & Boundaries**  
- Esri, TomTom, Garmin, FAO, NOAA, USGS  
- OpenStreetMap contributors  

> All datasets were cleaned, harmonized, and joined at the **country level** prior to cartographic visualization.

---

## 🗺️ Methodology

### 1️⃣ Data Preparation
- GHG and population datasets processed using **Microsoft Excel**  
- Population data filtered to extract the **top ten most populated European countries**  
- Attribute joins performed to link statistical data with spatial boundaries  

### 2️⃣ Projection / CRS Selection
- A **Europe-appropriate projected CRS** was selected  
- Projection choice prioritized **area preservation and visual balance**, essential for choropleth mapping  

### 3️⃣ Thematic Mapping
- **Choropleth mapping** used for GHG emissions per capita  
- **Sequential color scheme** (darker = higher emissions)  
- **Proportional symbols** applied to represent population magnitude  

---

## 🎨 Cartographic Design Principles Applied
- Data normalization using **per capita indicators**  
- Appropriate **classification scheme** for thematic clarity  
- Clear visual contrast between choropleth colors and proportional symbols  
- Balanced layout including **legend, north arrow, and map elements**  
- Integration of **SDG 13 – Climate Action** context  

---

## 🛠️ Tools & Software Used

| Tool | Purpose |
|----|----|
| **QGIS** | Spatial data processing & thematic mapping |
| **ArcGIS Pro** | Cartographic layout design & refinement |
| **Microsoft Excel** | Data cleaning, filtering & preparation |

---

## 📚 Academic Context
This project was completed as part of the **Advanced Cartography** course and demonstrates:

- Application of **thematic cartography techniques**  
- Critical decision-making in **CRS selection and classification**  
- Use of cartography as a tool for **climate data communication**  

---

## 🌍 Relevance & Interpretation
By combining **population magnitude** with **per capita emissions**, the map provides insights into:

- Spatial disparities in carbon emissions across Europe  
- Relationships between population size and environmental impact  
- Evidence-based perspectives relevant to **climate policy and sustainability research**

---

## 🖼️ Map Output
```markdown
![Final Choropleth Map](outputs/final_map.png)
