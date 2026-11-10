# Mineral_Resource
Interactive GIS dashboards and spatial analytics exploring African natural resources (oil, gas, critical minerals), logistics corridors, and hydroclimatic water stress / contamination risks.
# African Natural Resources & Mining Water-Risk Spatial Analytics

An interactive geospatial and data science portfolio project analyzing the spatial distribution of energy reserves, critical battery minerals, export infrastructure, and environmental hydroclimatic risks across Africa.

### 🔗 Live Dashboards

| Dashboard | Link |
|---|---|
| 🗺️ African Natural Resources Map | [Open dashboard](https://<your-username>.github.io/<repo-name>/resources-map.html) |
| 💧 Mining Water-Stress & Contamination Dashboard | [Open dashboard](https://<your-username>.github.io/<repo-name>/water-risk-map.html) |

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Key Features](#️-key-features)
- [Data Sources](#-data-sources)
- [Tech Stack](#️-tech-stack)
- [How to Run Locally](#-how-to-run-locally)

---

## 📌 Project Overview

Mining, energy, and exploration executives face critical questions about **geological prospectivity**, **export logistics**, and **ESG / water security**. This project synthesizes continental GIS datasets (USGS, geological surveys, and infrastructure inventories) into interactive, client-side web dashboards that address two core dimensions.

### 1. Continental Resource Distribution & Logistics

- **Energy basins:** Oil & gas sedimentary basins, active LNG terminals, and Karoo coal provinces.
- **Critical minerals:** Spatial clustering of energy-transition minerals:
  - Copperbelt Cu-Co (DRC / Zambia)
  - Hard-rock lithium (Zimbabwe, Mali, DRC)
  - PGE & chromite (Bushveld / Great Dyke)
  - Flake graphite
- **Supply chain connectivity:** Pipeline corridors and deepwater commodity export ports.


---

## 🗺️ Key Features

- **Multi-layer geospatial visualization:** Built with Leaflet.js, using CartoDB Positron and OpenStreetMap basemaps.
- **Dynamic layer toggles:** Show or hide pipelines, export ports, river networks, and administrative boundaries.
- **Regional & commodity filtering:** Filter by sub-region (North, West, Central, East, Southern Africa), development stage, and mineral commodity.
- **Color-coded legends:** Clear keys for hydroclimatic stress tiers, buffer proximity rings, and commodity classes.
- **Responsive analytics sidebar:** Dynamic summary metrics and distribution charts.

---

## 📊 Data Sources

| Source | Used For |
|---|---|
| **USGS World Minerals Exploration Database (WMED)** | Mineral exploration sites, development stages, and deposit classifications |
| **USGS Global Energy Assessments** | Conventional and undiscovered oil, gas, and coal basin boundaries |
| **Natural Earth Hydrology Database** | African river networks, drainage basins, and natural lake boundaries |
| **Infrastructure inventories** | Pipeline networks, LNG terminals, and mineral-exporting seaports |
| **GADM / UN-standardized boundaries** | Political and sub-national administrative borders |

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Mapping & GIS** | Leaflet.js, GeoJSON |
| **Frontend / UI** | Vanilla JavaScript (ES6+), HTML5, CSS3 (Grid & Flexbox) |
| **Deployment** | GitHub Pages (static, client-side web application) |

---

## 🚀 How to Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

**2. Open a dashboard in your browser**

- `resources-map.html`
- `water-risk-map.html`

> No local web server or build step required.
