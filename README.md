# GEOG 458 — Lab 4: Map Design and Tile Generation

## Web Map URL
https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/

## Study Area
A continental-scale extent covering a large portion of Europe.

## Zoom Levels (per tileset)
- Tileset 1 (Basemap): z = 4–8
- Tileset 2 (Thematic): z = 4–7 (reduced to limit tile count)
- Tileset 3 (Combined): z = 4–7
- Tileset 4 (Theme Basemap): z = 4–8

> Note: All tiles were generated in Web Mercator (EPSG:3857) using QMetaTiles/QTiles and stored as `{z}/{x}/{y}.png`.

## Tileset Descriptions
- **Tileset 1 — Basemap (Mapbox Studio → WMTS → QGIS Tiles):**  
  A customized Classic Mapbox basemap intended to provide geographic context with a relatively restrained color palette and adjusted styling (colors/fonts).

- **Tileset 2 — Thematic (My Dataset → QGIS Tiles):**  
  European political boundaries generated from a geospatial dataset loaded into QGIS (e.g., Natural Earth Admin 0 Countries), styled as a thematic overlay.

- **Tileset 3 — Combined (Basemap + Thematic → QGIS Tiles):**  
  A single raster tileset exported with both the basemap and thematic boundary layer visible to demonstrate a baked-in cartographic composition.

- **Tileset 4 — Theme Basemap (Mapbox Studio Theme → WMTS → QGIS Tiles):**  
  A Mapbox Studio basemap with a “Political Europe” theme emphasizing administrative boundaries and reducing non-essential visual clutter.

## Screenshots (required)
Add 4 screenshots to the `img/` folder and link them here:

- Tileset 1 (Basemap)  
  ![Basemap](img/tileset1_basemap.png)

- Tileset 2 (Thematic)  
  ![Thematic](img/tileset2_thematic.png)

- Tileset 3 (Combined)  
  ![Combined](img/tileset3_combined.png)

- Tileset 4 (Theme)  
  ![Theme](img/tileset4_theme.png)

## Repository Structure
