# Population Density Mapping of Pakistan – QGIS Project

## Overview

This project visualises population density across Pakistan using Geographic Information Systems. The analysis combines administrative boundary shapefiles with population statistics to create a thematic map that highlights regional variations in population distribution. The work demonstrates spatial data preparation, data joining, attribute calculations, map styling, and professional cartographic layout design.

## Project Objectives

The primary objectives were to:

- Prepare and clean spatial and tabular datasets for analysis.
- Join population data with Pakistan’s administrative boundaries.
- Calculate population density using area and population values.
- Create a clear, readable, and well-designed thematic map.
- Export the final map in PDF format for reporting and documentation purposes.

## Dataset Description

Two datasets were used:

### Administrative Boundary Shapefile
- Pakistan’s district or provincial boundaries  
- Contains geometry and region names  

### Population Dataset
- Population figures by district or province  
- Cleaned and formatted for joining  
- Includes region names that match the boundary file  

Both datasets were prepared to ensure a common join field such as district or province name or code.

## Steps Performed

### 1. Data Preparation
- Cleaned the population dataset in spreadsheet format.  
- Verified that region names aligned with the boundary shapefile fields.  
- Removed invalid or incomplete entries before importing into QGIS.

### 2. Joining Population Data
- Imported both datasets into QGIS.  
- Performed a table join using a common administrative field.  
- Validated that population attributes correctly attached to each boundary polygon.

### 3. Calculating Population Density
- Added a new field in the attribute table.  
- Computed the formula:  
  `Population Density = Population / Area`  
- Ensured that density values were consistent across all regions.

### 4. Map Design and Layout
- Applied a graduated colour symbology from light to dark to represent low to high density.  
- Added district or province labels.  
- Inserted essential cartographic elements:  
  - Title  
  - Legend  
  - Scale bar  
  - North arrow  
- Adjusted layout for clarity, spacing, and visual balance.

### 5. Export
- Exported the final map as a high-quality PDF file.  
- The exported map is included in this repository.

## Deliverables

This repository contains:

- `Pakistan_Population_Density.qgz` — the complete QGIS project  
- `Population_Density_Map.pdf` — the final exported map  
