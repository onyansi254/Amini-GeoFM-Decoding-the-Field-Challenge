
# 🌍 Amini GeoFM Decoding the Field Challenge — Crop Classification

This repository contains my solution for the **Amini GeoFM Decoding the Field Challenge** hosted on Zindi.

## 🏆 Challenge Summary
The goal is to classify crop types (**rubber, oil palm, cocoa**) using Sentinel-2 multispectral time series data. The challenge leverages **Geospatial Foundation Models (GeoFMs)**:
- **PRESTO** (by NASA Harvest)
- **Amini Earth FM** (by Amini.ai)

Participants must source **public and free** datasets for training and use the pretrained GeoFMs to extract features and build a classifier.

---

## 📂 Project Structure
```

├── data/                 # Training datasets (public)
├── notebooks/            # Jupyter Notebooks for experiments
├── src/                  # Scripts for preprocessing and modeling
├── submissions/          # Final submissions
├── environment.yml       # Environment setup
├── README.md             # Project description
└── LICENSE               # License file

```

---

## 🛰️ Datasets Used
All datasets are publicly available:
- Radiant Earth AgriFieldNet India
- South Africa Crop Type Dataset (Radiant MLHub)
- Global Oil Palm Dataset (BIOPAMA)
- Cocoa Mapping Datasets (West Africa)
- Sentinel-2 (via Google Earth Engine)

---

## 💡 Technologies
- Python
- Sentinel-2 Processing
- GeoFM Models (PRESTO, Amini Earth FM)
- XGBoost / LightGBM
- Google Earth Engine
- Radiant MLHub

---

## 📋 Submission Format
Predictions submitted in the required CSV format with **log loss** as the evaluation metric.

---

## 📝 License
This project is licensed for research and educational purposes.

---

## 📬 Contact
For questions, feel free to open an issue or start a discussion in this repo.

