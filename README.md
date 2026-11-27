# Vendor & Spatial Data Analysis Dashboard
### Vendor Mapping & Operational Insights | Kudus Dandangan Festival 2025

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" />
  <img src="https://img.shields.io/badge/Looker%20Studio-Dashboard-orange" />
  <img src="https://img.shields.io/badge/Machine%20Learning-K--Means-green" />
  <img src="https://img.shields.io/badge/Project-Data%20Analytics-purple" />
</p>

## Project Overview

This project focuses on analyzing and mapping 950 vendor records from Kudus Dandangan Festival 2025 to understand vendor distribution, merchandise categories, stall allocation, retribution payment status, and data validation performance.

The analysis explores vendor characteristics, geographic distribution across stall zones, registration and validation timelines, and discrepancies in vendor information.

An interactive dashboard was developed to present vendor distribution and operational insights through data visualization. The project also applies K-Means clustering to explore vendor segments based on selected operational characteristics.

## Project Dashboard

**View the Interactive Dashboard:**

[Open Vendor Mapping Dashboard](https://datastudio.google.com/reporting/50e4cd64-10e6-4149-bdaa-f29110a97456)

## Project Objectives

- Analyze vendor distribution during Kudus Dandangan Festival 2025.
- Identify the most common merchandise categories and types.
- Examine vendor distribution across stall zones.
- Monitor retribution payment status.
- Evaluate vendor data validation results and discrepancies.
- Analyze vendor registration and validation timelines.
- Explore geographic patterns using vendor coordinates.
- Analyze stall area requirements across merchandise categories.
- Explore vendor segmentation using K-Means clustering.
- Present analytical findings through an interactive dashboard.

## Dataset Description

The dataset contains **950 vendor records** and **17 variables**.

| Category | Variables |
|---|---|
| Vendor Information | Vendor ID, Business Name |
| Merchandise Information | Category, Merchandise Type |
| Geographic Information | District of Origin, Stall Zone, Stall Number, Latitude, Longitude, Coordinates |
| Stall Information | Stall Size (m²) |
| Retribution Information | Retribution Payment Status |
| Registration Information | Registration Date, Validation Date |
| Validation Information | Validation Status, Discrepancy Type |
| Event Information | Event Name |

### Dataset Summary

| Metric | Value |
|---|---:|
| Total Vendors | 950 |
| Total Variables | 17 |
| Stall Zones | 6 |
| Merchandise Categories | 7 |
| Vendor Origin Districts | 9 |

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Vendors | 950 |
| Retribution Paid | 838 |
| Retribution Unpaid | 112 |
| Retribution Payment Rate | 88.21% |
| Validation Completed as Appropriate | 920 |
| Vendors Requiring Correction | 30 |
| Total Stall Area | 4,805 m² |
| Average Stall Size | 5.06 m² |
| Average Validation Duration | 3.20 days |

## Dashboard Features

### 1. Vendor Profile & Merchandise Analysis

- Vendor distribution by merchandise category
- Top merchandise types
- Merchandise category comparison
- Vendor business profile

### 2. Geographic & Stall Zone Analysis

- Vendor distribution by stall zone
- Vendor origin by district
- Geographic distribution of vendor coordinates
- Vendor category distribution by zone

### 3. Retribution Payment Analysis

- Paid and unpaid vendor distribution
- Retribution payment status
- Unpaid vendor distribution by zone
- Payment status comparison across zones

### 4. Data Validation & Discrepancy Analysis

- Validation status distribution
- Vendor data correction analysis
- Discrepancy type analysis
- Validation duration analysis
- Corrected vendor distribution by zone

### 5. Registration & Operational Timeline

- Daily vendor registration trends
- Daily vendor validation trends
- Registration and validation timeline
- Validation processing duration

### 6. Stall Area Analysis

- Total stall area by category
- Average stall size by category
- Stall size distribution
- Stall area requirements for event planning

### 7. Vendor Segmentation Using Machine Learning

- Feature preprocessing
- K-Means clustering
- Optimal cluster selection using silhouette score
- PCA visualization
- Cluster distribution
- Cluster profile analysis

## Key Findings & Business Insights

### 1. Vendor Category Distribution

The largest vendor category is Food, representing 343 vendors.

| Category | Vendors | Percentage |
|---|---:|---:|
| Food | 343 | 36.1% |
| Beverages | 163 | 17.2% |
| Clothing | 137 | 14.4% |
| Toys & Entertainment | 104 | 10.9% |
| Accessories & Crafts | 97 | 10.2% |
| Household Supplies | 63 | 6.6% |
| Others | 43 | 4.5% |

Food vendors represent the largest share of the event's vendor composition.

### 2. Merchandise Type Analysis

The most common merchandise type is Bakso/Mie, with 82 vendors.

Other major merchandise types include:

- Snacks: 71 vendors
- Satay: 69 vendors
- Fried Food: 66 vendors
- Main Meals: 55 vendors
- Coffee: 48 vendors

### 3. Geographic & Stall Zone Distribution

Vendor distribution is relatively balanced across six stall zones.

| Stall Zone | Vendors |
|---|---:|
| Zona A | 170 |
| Zona B | 160 |
| Zona C | 160 |
| Zona D | 150 |
| Zona E | 160 |
| Zona F | 150 |

Zona A has the highest number of vendors, with 170 records.

The largest vendor origin group comes from Kecamatan Kota, with 202 vendors (21.3%).

### 4. Retribution Payment Performance

A total of 838 vendors have completed their retribution payments.

- Paid vendors: 838 (88.21%)
- Unpaid vendors: 112 (11.79%)

The payment status analysis provides an overview of retribution completion and identifies vendors whose payment status requires further monitoring.

### 5. Vendor Data Validation

The dataset records 920 vendors with validation status "Sesuai" and 30 vendors with status "Dikoreksi".

- Validation status "Sesuai": 920 vendors (96.84%)
- Validation status "Dikoreksi": 30 vendors (3.16%)

The most common discrepancy is "Nama usaha tidak sesuai", with 12 cases.

Other discrepancies include:

- Stall location mismatch: 7 cases
- Merchandise category mismatch: 7 cases
- Stall size mismatch: 4 cases

### 6. Registration & Validation Timeline

Vendor registration dates range from February 3 to February 16, 2025.

Validation dates range from February 4 to February 24, 2025.

The average duration between registration and validation is approximately 3.20 days.

### 7. Stall Area Analysis

The dataset records a total stall area of 4,805 m².

- Total vendors: 950
- Average stall size: 5.06 m²
- Largest total stall area by category: Food, with 1,688 m²
- Toys & Entertainment has the highest average stall size among categories, at approximately 7.16 m².

### 8. Vendor Segmentation

The project applies K-Means clustering to explore vendor segments based on selected operational characteristics:

- Merchandise category
- Vendor origin district
- Stall zone
- Stall size
- Validation duration

The clustering workflow includes feature preprocessing, standardization, optimal cluster selection using silhouette scores, PCA visualization, and cluster profiling.

## Methodology

The project follows a structured analytical workflow:

1. **Data Understanding** – Examining dataset structure, variables, and vendor characteristics.
2. **Data Quality Assessment** – Checking missing values, duplicate records, duplicate vendor IDs, duplicate stall numbers, and geographic coordinate validity.
3. **Data Preparation** – Calculating validation duration, registration month, and standardizing text labels.
4. **KPI Development** – Calculating total vendors, payment status, validation results, total stall area, and average validation duration.
5. **Exploratory Data Analysis** – Analyzing vendor categories, merchandise types, geographic distribution, payment status, and validation results.
6. **Geographic Analysis** – Visualizing vendor coordinates based on stall zones.
7. **Machine Learning** – Applying K-Means clustering to explore vendor segmentation.
8. **Data Visualization** – Developing charts and dashboard components.
9. **Insight Generation** – Identifying operational patterns and summarizing findings.

## Tools & Technologies

| Tool | Application |
|---|---|
| Python | Data cleaning, analysis, feature engineering, and machine learning |
| Pandas | Data manipulation and aggregation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Data preprocessing, K-Means clustering, PCA, and silhouette score evaluation |
| Microsoft Excel | Dataset storage and data review |
| Google Colab | Python-based analytical workflow |
| Looker Studio | Interactive dashboard visualization |

## Technical Skills Demonstrated

- Data Analysis
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Quality Assessment
- Geographic Data Analysis
- Data Visualization
- KPI Development
- Data Validation
- Vendor Segmentation
- K-Means Clustering
- Principal Component Analysis (PCA)
- Business Insight Generation
- Dashboard Development

## Data Quality & Limitations

- The dataset contains 950 records and 17 variables.
- No missing values were found in the main vendor identification, category, geographic coordinate, payment status, and validation status fields.
- The `Jenis_Ketidaksesuaian` variable contains 920 missing values because discrepancy types are recorded for vendors requiring correction.
- No duplicate rows, vendor IDs, or stall numbers were identified.
- There are 88 duplicate business names. Identical business names do not necessarily represent the same vendor and may require further review.
- Geographic scatter plots show relative vendor distribution based on coordinates. Without an official basemap or zone boundary data, the visualization cannot confirm official stall boundaries or exact positional accuracy.
- The dataset contains retribution payment status but does not include retribution amounts. Therefore, total retribution revenue cannot be calculated.
- The analysis is descriptive and identifies operational patterns rather than causal relationships.
- K-Means clustering is used to explore vendor segments based on selected features. Cluster interpretations depend on preprocessing and clustering results.

## Project Deliverables

The project includes:

- Interactive Vendor Mapping Dashboard
- Python analytical notebook
- Exploratory data analysis
- Geographic visualization
- Vendor segmentation using K-Means
- Cluster profiling
- Cleaned vendor dataset export

## Dashboard Access

[Click Here to View the Interactive Dashboard](https://datastudio.google.com/reporting/50e4cd64-10e6-4149-bdaa-f29110a97456)

## Author

**Amanda Diyas Setiyoadi**

Data Analytics Portfolio

Interested in Data Analytics, Business Intelligence, Data Visualization, Geographic Data Analysis, and Business Insights.
