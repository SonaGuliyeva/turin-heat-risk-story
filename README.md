# Turin heat risk – story assets (Team 4, ESA Science Hub Challenge 2026)

Web-ready files used by the eodash / RACE narrative "Heat Risk Mapping – Turin case study".

- `lst_night_2026-08-DD.tif` – Sentinel-3 SLSTR night-time land surface temperature (°C), Cloud-Optimized GeoTIFF, EPSG:3857. 10 and 13 August are strongly cloud-affected (values < 15 °C are cloud tops).
- `ndvi_2026-08-01_15.tif` – Sentinel-2 NDVI median composite, 1–15 Aug 2026, COG, EPSG:3857, 20 m.
- `imperviousness_2024.tif` – Copernicus HRL Imperviousness 2024 (%), COG, EPSG:3857, 20 m (255 = no data).
- `*_style.json` – eodash / OpenLayers flat styles with legends for the rasters above.
- `*.png` – static figures from the analysis notebook.

Data: Copernicus / ESA (Sentinel-2, Sentinel-3), Copernicus Land Monitoring Service, Città di Torino open data.
