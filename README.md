# OceanAnalytics

### **Azure Synapse Repo**

The project aims to analyze population trends of marine mammals (e.g., whales, dolphins, and seals) in different regions over time. By leveraging descriptive analytics, the project seeks to identify changes in population densities, migration patterns, and environmental factors affecting these populations.

**Objective**:

To use historical and spatial data to understand how marine mammal populations evolve and to create visualizations that highlight key trends.

---

### **2. Data Sources**

- **Source 1**: **OBIS (Ocean Biogeographic Information System)**
    
    Global dataset of species occurrence, including geolocated sightings of marine mammals.
    
    **Link**: [OBIS](https://obis.org/)
    
- **Source 3**: **Sea Surface Temperature & Climate Data**
    
    Climate and oceanographic data from NASA or Copernicus, relevant to analyzing environmental impacts.
    
    **Link**: [NASA EarthData](https://earthdata.nasa.gov/)
    

---

### **3. Data Processing Pipeline**

1. **Data Collection**
    - Download data for whales in OBIS Mapper.
    - Download climate data for regions of interest.
2. **Data Cleaning**
    - Remove duplicate or inconsistent records.
    - Standardize data formats (e.g., coordinates, date/time).
3. **Data Integration**
    - Combine species data with environmental data (temperature, salinity, etc.).
    - Use geospatial tools to align datasets by location and time.
4. **Data Analysis**
    - Perform descriptive statistics to identify population trends.
    - Group data by species, region, and year to visualize long-term changes.
5. **Data Visualization**
    - Use **Power BI** or **Tableau** for interactive dashboards.
    - Create heatmaps of species density and time-series graphs of population changes.

---

### **4. Technology Stack**

- **Data Storage**: Azure Data Lake
- **Data Ingestion**: Azure Data Factory
- **Data Processing**: Azure Synapse Analytics
- **Data Visualization**: Power BI

---

### **5. Project Timeline**

| **Phase** | **Duration** | **Deadline** |
| --- | --- | --- |
| Data Collection | 1 week | Day 7 |
| Data Cleaning & Integration | 2 weeks | Day 21 |
| Data Analysis | 1.5 weeks | Day 31 |
| Data Visualization | 1 week | Day 38 |
| Reporting & Documentation | 1 week | Day 45 |

---

### **6. Quality Assurance**

1. **Data Validation**
    - Cross-check data against original sources for consistency.
    - Use automated scripts to identify missing or outlier values.
2. **Pipeline Testing**
    - Test each step in the processing pipeline individually (e.g., ingestion, cleaning).
    - Perform dry runs to ensure the integration of datasets.
3. **Peer Review**
    - Share findings and visualizations with peers or mentors for feedback.

---

### **7. Reporting and Documentation**

- **Documentation**:
    - Maintain a log of data sources, processing steps, and scripts in a **Notion page**.
    - Include a README file for the repository explaining how to replicate the analysis.
- **Reporting**:
    - Prepare a final report with key findings, supported by visualizations.
    - Deliver a presentation (PowerPoint or Notion page) summarizing insights and recommendations.

 ### **8. Reporting and Documentation**

 **Link**: [Notion Page](https://www.notion.so/edeme/OceanAnalytics-142f89c19b3380cfa489cea56ce4653a)
