
# Vendor & Spatial Data Analysis Dashboard

### Vendor Mapping & Operational Insights | Kudus Dandangan Festival 2025 | Data Analytics Portfolio

## Project Overview

This project focuses on analyzing and mapping 950 vendor records from Kudus Dandangan Festival 2025 to understand vendor distribution, merchandise categories, stall allocation, retribution payment status, and data validation performance.

The analysis explores vendor characteristics, geographic distribution across stall zones, registration and validation timelines, and discrepancies in vendor information.

An analytical dashboard was developed to present vendor distribution and operational insights through data visualization. The project also applies K-Means clustering to explore vendor segments based on merchandise categories, vendor origin, stall zones, stall size, and validation duration.

The analysis provides an overview of vendor registration, spatial distribution, and administrative data quality to support event management and operational monitoring.

## Project Details

| Category | Description |
|---|---|
| **Project Name** | Vendor & Spatial Data Analysis Dashboard |
| **Dataset** | 950 vendor records with 17 variables |
| **Background** | Vendor management during a large-scale festival requires accurate registration records, stall allocation, payment monitoring, and data validation. |
| **Objectives** | Analyze vendor profiles, merchandise distribution, payment status, validation performance, geographic distribution, and vendor segmentation. |
| **Tools** | Python, Microsoft Excel, Google Colab, Looker Studio |
| **Techniques** | EDA, Data Cleaning, Geographic Analysis, Data Validation, KPI Monitoring, Data Visualization, K-Means Clustering |
| **Dashboard** | [View Interactive Dashboard](https://datastudio.google.com/reporting/50e4cd64-10e6-4149-bdaa-f29110a97456) |

## Business Objectives

The main objectives of this project are:

1. Analyze overall vendor distribution during Kudus Dandangan Festival 2025.
2. Identify the most common merchandise categories and types.
3. Examine vendor distribution across stall zones.
4. Monitor retribution payment status and identify unpaid vendors.
5. Evaluate vendor data validation results and discrepancies.
6. Analyze vendor registration and validation timelines.
7. Examine geographic patterns using latitude and longitude coordinates.
8. Analyze stall area requirements across merchandise categories.
9. Explore vendor segmentation using K-Means clustering.
10. Present analytical findings through a dashboard to support operational monitoring.

## Dataset Description

The dataset consists of **950 vendor records** and **17 variables**.

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

### Dataset Dimensions

- Total Records: 950
- Total Variables: 17
- Event: Kudus Dandangan Festival 2025
- Stall Zones: 6
- Vendor Categories: 7
- Vendor Origin Districts: 9

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Vendors | 950 |
| Retribution Paid | 838 |
| Retribution Unpaid | 112 |
| Retribution Payment Rate | 88.21% |
| Validation Completed as Appropriate | 920 |
| Vendors Requiring Correction | 30 |
| Total Stall Area | 4,805 m² |

### Additional Operational Indicators

| KPI | Result |
|---|---:|
| Validation Accuracy Status Rate | 96.84% |
| Vendor Correction Rate | 3.16% |
| Average Stall Size | 5.06 m² |
| Average Validation Duration | 3.20 days |

## Dashboard Features

### 1. Vendor Profile & Merchandise Analysis

Analyzes the composition of vendors based on merchandise categories and business types.

- Vendor Distribution by Merchandise Category
- Top 10 Merchandise Types
- Merchandise Category Comparison
- Vendor Business Profile

### 2. Geographic & Stall Zone Analysis

Examines vendor distribution across designated stall zones and vendor origin districts.

- Vendor Distribution by Stall Zone
- Vendor Origin by District
- Geographic Distribution of Vendor Coordinates
- Vendor Category Distribution by Zone

### 3. Retribution Payment Analysis

Evaluates vendor retribution payment status to support payment monitoring.

- Paid and Unpaid Vendor Distribution
- Retribution Payment Status
- Unpaid Vendor Distribution by Zone
- Payment Status Comparison Across Zones

### 4. Data Validation & Discrepancy Analysis

Analyzes vendor data validation results and identifies common discrepancies.

- Validation Status Distribution
- Vendor Data Correction Analysis
- Discrepancy Type Analysis
- Validation Duration Analysis
- Corrected Vendor Distribution by Zone

### 5. Registration & Operational Timeline

Examines the registration and validation process throughout the event preparation period.

- Daily Vendor Registration Trends
- Daily Vendor Validation Trends
- Registration and Validation Timeline
- Validation Processing Duration

### 6. Stall Area Analysis

Evaluates stall area requirements based on merchandise categories.

- Total Stall Area by Category
- Average Stall Size by Category
- Stall Size Distribution
- Stall Area Requirements for Event Planning

### 7. Vendor Segmentation Using Machine Learning

Applies K-Means clustering to explore vendor segments based on selected operational characteristics.

- Merchandise Category
- Vendor Origin District
- Stall Zone
- Stall Size
- Validation Duration
- Cluster Distribution
- Cluster Profile Analysis

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

These findings indicate that food-related merchandise represents a substantial portion of the vendor population.

### 3. Geographic & Stall Zone Distribution

Vendor distribution is relatively balanced across six stall zones.

| Stall Zone | Vendors |
|---|---:|
| Zone A | 170 |
| Zone B | 160 |
| Zone C | 160 |
| Zone D | 150 |
| Zone E | 160 |
| Zone F | 150 |

Zone A has the highest number of vendors, with 170 records.

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

These findings highlight the importance of accurate vendor registration and validation procedures.

### 6. Registration & Validation Timeline

- Registration dates: February 3–16, 2025
- Validation dates: February 4–24, 2025
- Average validation duration: approximately 3.20 days

This analysis provides an overview of the administrative processing timeline and helps identify the duration required to complete vendor validation.

### 7. Stall Area Analysis

The dataset records a total stall area of 4,805 m².

- Total vendors: 950
- Average stall size: 5.06 m²
- Largest total stall area by category: Food, with 1,688 m²
- Toys & Entertainment has the highest average stall size among categories, at approximately 7.16 m².

Stall area analysis can support event space planning and allocation based on vendor category.

### 8. Vendor Segmentation

The project applies K-Means clustering to explore vendor segments based on:

- Merchandise category
- Vendor origin district
- Stall zone
- Stall size
- Validation duration

The clustering workflow includes feature preprocessing, standardization, optimal cluster selection using silhouette scores, PCA visualization, and cluster profiling.

The purpose of this analysis is to identify groups of vendors with similar operational characteristics.

## Analytical Conclusion

The analysis provides an overview of vendor composition, geographic distribution, retribution payment status, data validation performance, and stall area requirements during Kudus Dandangan Festival 2025.

The findings indicate that food vendors represent the largest merchandise category, vendor distribution is relatively balanced across stall zones, and most vendors have completed retribution payments and passed data validation.

The project demonstrates how data analytics and geographic visualization can support vendor management, operational monitoring, and event planning.

The K-Means clustering workflow provides an additional approach to exploring vendor segments based on selected operational characteristics.

## Methodology

The project follows a structured analytical workflow:

1. **Data Understanding** – Examining the dataset structure, variables, vendor characteristics, and event information.
2. **Data Quality Assessment** – Checking missing values, duplicate records, duplicate vendor IDs, duplicate stall numbers, and geographic coordinate validity.
3. **Data Preparation** – Calculating validation duration, registration month, and standardizing text labels.
4. **KPI Development** – Calculating total vendors, paid and unpaid vendors, validation results, total stall area, and average validation duration.
5. **Exploratory Data Analysis** – Analyzing vendor categories, merchandise types, geographic distribution, payment status, and validation results.
6. **Geographic Analysis** – Visualizing vendor coordinates based on stall zones.
7. **Machine Learning** – Applying K-Means clustering to explore vendor segmentation.
8. **Data Visualization** – Developing charts and dashboard components to communicate analytical findings.
9. **Insight Generation** – Identifying operational patterns and summarizing findings for vendor management and event planning.

## Tools & Technical Skills

| Tool | Application |
|---|---|
| Python | Data cleaning, analysis, feature engineering, and machine learning |
| Pandas & NumPy | Data manipulation, aggregation, and analytical calculations |
| Matplotlib & Seaborn | Data visualization and exploratory analysis |
| Scikit-learn | Data preprocessing, K-Means clustering, PCA, and silhouette score evaluation |
| Microsoft Excel | Dataset storage, review, and data preparation |
| Google Colab | Python-based analytical workflow |
| Looker Studio | Dashboard visualization and presentation |

### Technical Skills Demonstrated

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
- There are 88 duplicate business names. These require review because identical business names do not necessarily represent the same vendor.
- The dataset contains latitude and longitude coordinates for geographic visualization.
- Geographic scatter plots show relative vendor distribution based on coordinates. Without an official basemap or zone boundary data, the visualization cannot confirm official stall boundaries or exact positional accuracy.
- The dataset contains retribution payment status but does not include retribution amounts. Therefore, total retribution revenue cannot be calculated.
- The analysis is descriptive and identifies operational patterns rather than causal relationships.
- K-Means clustering is used to explore vendor segments based on selected features. Cluster interpretations depend on the preprocessing and clustering results.

## Project Deliverables

The main deliverable of this project is a Vendor & Spatial Data Analysis Dashboard designed to provide an overview of vendor distribution, merchandise composition, payment status, validation performance, and stall area requirements.

The project also includes a Python-based analytical notebook containing data preparation, exploratory analysis, geographic visualization, and vendor segmentation using machine learning.

### Dashboard Access

[Click Here to View the Interactive Vendor Mapping Dashboard](https://datastudio.google.com/reporting/50e4cd64-10e6-4149-bdaa-f29110a97456)

## Author

**Amanda Diyas Setiyoadi**

Data Analytics Portfolio

Interested in Data Analytics, Business Intelligence, Data Visualization, Geographic Data Analysis, and Business Insights.
