# 🎯 Dave & Buster’s Site Suitability Analysis – Greater Sudbury, ON

## 📍 Project Overview
This project identifies the most suitable locations for opening a **Dave & Buster’s entertainment center** in Greater Sudbury, Ontario, using **ArcGIS Pro** and spatial analysis techniques.  

The analysis integrates multiple datasets, applies site suitability criteria, and produces final candidate sites with the highest potential for business success.

---

## 🗺️ Methodology
### 1. Data Collection
- **Greater Sudbury Boundary** – defines study area  
- **Roads Network** – identifies major access routes  
- **Hotels & Motels** – potential nearby customer sources  
- **Traffic Intersection Counts** – measures high-traffic zones  
- **Zoning Information** – ensures site compliance  
- **Environmental Layers** – avoids hazard-prone areas like floodplains  

### 2. Criteria Development
- ✅ Within **500 meters** of major roads  
- ✅ Within **1 km** of hotels & motels  
- ✅ High intersection traffic counts  
- ✅ Zoned for commercial use (C2)  
- 🚫 Outside environmental hazard zones  

### 3. Geoprocessing & Analysis
- **Buffering** – to create influence zones around features  
- **Intersect & Union** – to combine criteria layers  
- **Attribute Queries** – to filter eligible areas  
- **Final Selection** – ranking sites based on multiple weighted factors  

---

## 📊 Results
- **Number of Candidate Sites:** 3  
- **Top Site:** Parcel ID `43529` – optimal access, high visibility, strong surrounding businesses  
- **Map Output:**  
  ![Final Map](Maps/final_map.png)  

---

## 🛠 Tools Used
- **ArcGIS Pro** – geoprocessing, map layouts, and spatial analysis  
- **ArcGIS Online** – web map publishing  
- **Microsoft Excel** – data review & cleaning  
- **GitHub** – version control & project showcase  

---

## 🌐 Live Web Map
[Click here to view on ArcGIS Online](https://www.arcgis.com/home/webmap/viewer.html) <!-- Replace with your real link -->

---

## 📂 Repository Structure
```
DaveAndBusters_SiteSuitability/
│
├── Maps/                   # Exported PNG/JPEG map images
├── Data/                   # Public or sample datasets only
├── README.md               # Project documentation
├── ProjectReport.pdf       # Optional – full write-up
└── .gitignore              # Ignore unnecessary local files
```

---

## 👤 Author
**Lakshay Girdher**  
📧 Email: lakshay.girdher@example.com  
🔗 [LinkedIn](https://www.linkedin.com/in/lakshay-girdher)  
🔗 [Portfolio Website](https://yourportfolio.com)
