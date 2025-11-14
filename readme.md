# WA COVID-19 Case Rate Choropleth Map (Lab 04)

This repository contains the web map I created for **GEOG 495 – Lab 04**.
The assignment requires creating a choropleth map using Washington State COVID-19 data (as of October 25, 2021) provided in the `wa-covid-data-102521.geojson` file.

---

## 🔍 Map Overview

The map visualizes:

### **Cumulative COVID-19 Case Rate (per 10,000 people)**
for all Washington counties.

---

## 🗺️ Features of the Web Map

### ✔ Appropriate Webpage Title
`Cumulative COVID-19 Case Rate per 10k People in WA (as of 2021-10-25)`

### ✔ Map Title
Displayed in the top-left overlay.

### ✔ Correct Initial View
The map automatically centers and zooms on Washington State (`zoom: 6`, centered on WA).

### ✔ Choropleth Color Scheme
A seven-class sequential red color scale is applied to match the data distribution
(approximately 300–2000 cases per 10k people).

### ✔ Legend
Includes:

- Title
- Color categories
- Break values

### ✔ Hover Interaction
Hovering over a county displays:

- County name
- County abbreviation
- Case rate (per 10,000 people)

### ✔ County Labels
County abbreviations appear on the map using centroid points
(ensuring **only one label per county**, even for MultiPolygon counties).

---

## 📁 Files Included
  ```powershell
  [Interactive-Map]
      │index.html
      │pop_density.html
      │readme.md
      ├─assets
      │      stateData.geojson
      │      wa-covid-data-102521.json

  ```



