# Knowledge Graph–Driven Soil Health Decision Support

This repository contains a single end‑to‑end Jupyter notebook (`KG_DS_system.ipynb`) that demonstrates how a lightweight decision support workflow can combine:

1. Open soil property rasters from the EcoDataCube (cloud‑optimized GeoTIFFs accessed directly over HTTP).
2. A domain Knowledge Graph (`soil_health_KG.ttl`) queried via SPARQL to extract agronomic thresholds (e.g., soil pH constraints, aluminium toxicity risk, beneficial ranges for crop production).
3. On‑the‑fly analytics: point extraction, temporal trends, depth profiles, small‑area downloads, multi‑property raster summaries, and knowledge‑driven soil health classification.
