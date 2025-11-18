# Lab 4 – Interactive Web Mapping  
### GEOG 328 – University of Washington

This repository contains two interactive web maps created using **MapLibre GL JS** and local GeoJSON datasets. The main deliverable is a choropleth map of Washington State COVID-19 vaccination rates, and a secondary example map shows U.S. population density.

---

## Repository Structure

/[lab4-web-mapping]
│── index.html → Final deliverable: WA COVID-19 map
│── pop_density.html → Example: U.S. population density map
│── readme.md → Project documentation (current file)
└── assets/
├── wa-covid-data-102521.geojson
└── state_data.geojson

---

## WA COVID-19 Vaccination Map (`index.html`)

This map visualizes **fully vaccinated people per 10,000 residents** by Washington county (as of Oct. 25, 2021).

Features include:

- Choropleth color symbology  
- Hover interaction showing county name and vaccination rate  
- Click interaction with popup positioned above the county  
- Highlight outline for selected county  
- Legend describing vaccination ranges  

**Attribute used:** `fullyVaxPer10k`

---

## U.S. Population Density Map (`pop_density.html`)

This example map shows population density (people per square mile) for all U.S. states.

Features include:

- Choropleth color scale  
- Hover and click interaction  
- Legend matching density ranges  

**Attribute used:** `density`

---

## Technologies Used

- MapLibre GL JS  
- HTML, CSS, JavaScript  
- Local GeoJSON files in `/assets`

---

## GitHub Pages URLs

Main deliverable:  
https://[nurcoodes].github.io/[lab4-web-mapping]/index.html

Population density example:  
https://[nurcoodes].github.io/[lab4-web-mapping]/pop_density.html
