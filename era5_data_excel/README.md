### 📊 6-Hour ERA5 Weather Data (2000–2025)

This folder contains downsampled ERA5 weather variable data in Excel format. Each file corresponds to one variable and includes data from **2000 to 2025**, saved in a wide-format structure for efficient analysis and modeling.

#### ✅ Key Details

- **⏱️ Time Resolution**:  
  Data is downsampled to **6-hour intervals** to reduce file size and match [GraphCast](https://github.com/google-deepmind/graphcast) prediction frequency.

- **📁 Format**:  
  Each Excel file includes **one sheet per year**, structured as:
  - **Rows**: `(latitude, longitude)` grid points  
  - **Columns**: Timestamps at 6-hour steps

- **🗺️ Spatial Coverage**:  
  Grid points are limited to the **Bhutan region**, using the bounding box:  
  `lat: 26.5°N to 28.5°N`, `lon: 88.5°E to 92.0°E`  
  This subset of ERA5 data focuses on Bhutan for regional climate and flood modeling.

- **📌 Variables Included**:
  - `total_precipitation`
  - `surface_runoff`
  - `sub_surface_runoff`
  - `10m_u_component_of_wind`
  - `10m_v_component_of_wind`
  - `2m_temperature`

- **📤 Source**:  
  Data was extracted from **ERA5 `.grib` files** and processed via an automated pipeline for visualization and machine learning workflows.


