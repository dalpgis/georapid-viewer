GeoRapid es una herramienta web de DALPGIS para cargar y visualizar datos geoespaciales en segundos. Soporta GeoJSON, KML/KMZ, Shapefile ZIP, CSV y Excel; incluye selección por dibujo, medición, buffers y análisis de proximidad, con exportación a GeoJSON, KML y KMZ.

---
## ✨ Funcionalidades

- **Cargar datos**:
  - GeoJSON / JSON (incluye soporte para ArcGIS FeatureSet JSON en muchos casos)
  - KML / KMZ
  - Shapefile (`.zip`)
  - CSV / Excel (`.csv`, `.xlsx`, `.xls`) con detección automática de **lat/lon**
  - Si no detecta lat/lon, abre un **selector X/Y** (WGS84 o UTM WGS84)

- **Visualización**
  - Mapa base: **OpenStreetMap** y **Esri World Imagery**
  - Gestión de capas: encender/apagar, transparencia, zoom a capa, eliminar, reordenar por drag & drop
  - Popups con atributos y **tabla de atributos** (panel inferior)

- **Herramientas de análisis**
  - Medición de **distancia y área**
  - Selección por **dibujo** (polígono/rectángulo) usando intersección
  - **Buffer** por clic sobre una entidad (y selección de intersectados)
  - **Proximidad** (capa A ↔ capa B): calcula nearest y filtra por umbral

- **Exportación**
  - Exporta capas a: **GeoJSON**, **KML**, **KMZ**

---

## 🧰 Stack / Librerías

- **Leaflet** (mapa)
- **Tailwind** (UI)
- **PapaParse** (CSV)
- **SheetJS / XLSX** (Excel)
- **Proj4js** (transformaciones CRS, UTM→WGS84)
- **Turf.js** (geoprocesos: intersección, buffer, distance, centroid)
- **JSZip** (ZIP/KMZ)
- **shpjs** (Shapefile ZIP)
- **togeojson** (KML→GeoJSON)
- **tokml** (GeoJSON→KML)

---

## 📄 Licencia
Este proyecto está bajo licencia MIT. Ver archivo LICENSE.
