# NYC Urban Traffic Safety & Risk Analytics
A comprehensive data analytics solution designed to visualize ten years of NYC parking violation data. This project utilizes **Python** for dataset generation and **Power BI** for relational modeling, DAX-driven measures, and geospatial insights.

**Tech Stack**
- **Power BI**: Relational modeling, Data visualization, and Geospatial mapping.
- **Python (Pandas/NumPy)**: Data generation
- **DAX**: Complex measures for dynamic filtering and cross-table lookups.

## Key Features

- Geospatial Heatmapping & Risk Assessment
- Statistical Demographic & Violation Modeling
- Advanced Temporal Analysis

## How to Read the Data
- Each point represents a location with recorded parking violations. The density and color shift indicate the magnitude of violations in that specific area.
  This was done as in the original project, data size was an issue so the points were congregated. Instead of have multiple points on one Longitude and Latitude, there is now one point that represnts all of them,
  where color dictates how many of those points would have been in that same location

### How to Use
To explore this analytics solution locally:
1. **Download the Dataset**: Download the `NYC_Parking_Data_High_Variance.xlsx` file from this repository.
2. **Download the Power BI File**: Download the `.pbix` file.
3. **Connect the Data**: Open the Power BI file. If prompted for a data source, point the connection to the location of the downloaded Excel file on your machine.

> [!WARNING]
> Data used is NOT REAL
