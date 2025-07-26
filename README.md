# GRIB2 Weather Data Analysis

This project processes and analyzes GRIB2 weather data from the German Weather Service (DWD) focusing on solar direct radiation.

## Contents
- Data extraction scripts using Python (cfgrib, pygrib, pandas)
- Processed data CSV files
- Visualizations of solar radiation
- This project report

## Requirements
- Python 3.x
- Libraries: cfgrib, pygrib, pandas, xarray, matplotlib, eccodes, cython

## Usage
1. Download GRIB2 files from DWD.
2. Run extraction and analysis scripts.
3. View results in the CSV files and plots.

---

### 3. Initialize Git and Push to GitHub
If you have **Git** installed on your computer, open a terminal or command prompt, navigate to your project folder, and run:

```bash
git init
git add .
git commit -m "Initial commit - GRIB2 weather data analysis project"
git branch -M main
git remote add origin https://github.com/yourusername/GRIB2-weather-data-analysis.git
git push -u origin main
