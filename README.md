
# Bhutan Climate Modeling

🌏 This repository is part of [Omdena's local chapter challenge](https://www.omdena.com/chapter-challenges/leveraging-ai-to-combat-climate-change-in-bhutan), focused on leveraging AI to combat climate change in Bhutan.

We aim to model climate patterns and predict extreme events such as glacial lake outburst floods (GLOFs) through collaborative, data-driven analysis.

## ✅ Project Goals

- Understand historical meteorological trends and seasonal patterns  
- Identify regions vulnerable to extreme climate events  
- Build predictive models using AI/ML to forecast floods and extreme weather events  
- Explore the use of **ERA5 reanalysis data** for high-resolution temporal modeling  
- Investigate potential for **river and lake metrics** to serve as proxies for flood risk  
- Support downstream applications like risk maps and early-warning systems

This repo includes data, code, and outputs for:
- Analyzing historical meteorological patterns across Bhutan
- Identifying seasonal and regional climate trends
- Supporting predictive modeling of extreme weather events

## 🧠 Modeling Directions

We are actively developing predictive models using the following approaches:

- **Feature engineering** using lagged and rolling weather indicators (e.g., rainfall, Tmax, Tmin, RH)  
- **Short-term precipitation forecasting** using models like XGBoost and SARIMAX  
- **Extreme flood risk prediction** incorporating river discharge proxies and glacial lake data  
- Future directions include:  
  - Spatial modeling with **graph neural networks (GNNs)**  
  - Event detection using **transformers and deep learning**  

## 📁 Repository Structure

- **`code/`** – Python scripts and notebooks for data processing and analysis  
- **`data/`** – Raw meteorological data files
- **`era5_data/`** – Hourly climate variables from ERA5, organized by variable and year
- **`processed_data/`** – Cleaned and standardized data for each region  
- **`world_boundaries_for_bhutan_map/`** – Shapefiles and boundary data for mapping  
- **`README.md`** – Project overview and instructions  

