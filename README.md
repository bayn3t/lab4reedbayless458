# GEOG 458 — Lab 4: Map Design and Tile Generation

## Web Map URL
https://bayn3t.github.io/lab4reedbayless458/

---

## Study Area
This project focuses on a continental-scale study area covering much of **Europe**.  
The extent was intentionally limited to avoid excessive tile generation while still supporting regional comparison and cartographic context.

All tiles were generated in **Web Mercator (EPSG:3857)** and displayed using Mapbox GL JS.

---

## Zoom Levels by Tileset
- **Tileset 1 (Basemap):** Zoom levels 4–8  
- **Tileset 2 (Thematic):** Zoom levels 4–7  
- **Tileset 3 (Combined):** Zoom levels 4–7  
- **Tileset 4 (Theme Basemap):** Zoom levels 4–8  

Zoom ranges were adjusted to balance geographic coverage, visual clarity, and file size constraints for GitHub Pages.

---

## Tileset Descriptions

### Tileset 1 — Basemap (Mapbox Studio)
This tileset is a customized **Classic Mapbox basemap** designed to provide neutral geographic context.  
Colors, fonts, and visual hierarchy were adjusted in Mapbox Studio to reduce clutter while maintaining legibility across continental scales.

This basemap is intended to support thematic overlays rather than communicate a specific analytical message.

---

### Tileset 2 — Thematic: European Political Boundaries
This tileset visualizes **sovereign-level political boundaries** across Europe using a geospatial dataset loaded into QGIS (e.g., Natural Earth Admin 0 Countries).

**Why sovereignty is relevant:**  
Sovereign boundaries define nation-states and political jurisdictions, which are fundamental to understanding European geography, governance, and regional organization. At a continental scale, sovereignty provides a clear, interpretable thematic layer that supports comparison across countries without excessive detail.

The dataset was styled as a thematic layer and exported independently from any basemap to demonstrate how analytical layers can function on their own.

---

### Tileset 3 — Combined Basemap + Thematic
This tileset combines **Tileset 1 (Basemap)** and **Tileset 2 (Political Boundaries)** into a single raster tileset.

The combined export demonstrates how multiple layers can be composed into a single static tileset for performance optimization and visual consistency, which is useful when interactive layer control is not required.

---

### Tileset 4 — Theme Basemap: Political Europe
This tileset is a **Mapbox Studio–designed thematic basemap** focused on emphasizing political structure across Europe.

The style was derived from a Classic Mapbox basemap and customized to:
- Increase the visual prominence of national boundaries
- Reduce visual noise from minor roads and points of interest
- Use a restrained color palette appropriate for political reference mapping

Unlike Tileset 2, this tileset functions as a **basemap**, not a data overlay, and communicates political structure through cartographic design rather than explicit datasets.

---

## Screenshots (placeholders)

Add screenshots of the live web map with only one tileset visible at a time.  
Place images in the `img/` folder and replace the filenames below when ready.

### Tileset 1 — Basemap
*(Placeholder — add screenshot here)*  
`img/tileset1_basemap.png`

### Tileset 2 — Thematic (Political Boundaries)
*(Placeholder — add screenshot here)*  
`img/tileset2_thematic.png`

### Tileset 3 — Combined
*(Placeholder — add screenshot here)*  
`img/tileset3_combined.png`

### Tileset 4 — Theme Basemap
*(Placeholder — add screenshot here)*  
`img/tileset4_theme.png`

---

## Repository Structure
