# GEOG5995_Final_Project

## Project Title: Analysis of Housing Market in Leeds

### Overview
This project aims to analyze the relationship between median house prices and transaction counts in Leeds, UK. The analysis utilizes publicly available datasets and a GeoJSON file outlining the geographic boundaries of Leeds' LSOAs (Lower Layer Super Output Areas). The final visualizations provide insights into local real estate dynamics, helping stakeholders understand market trends and make informed decisions.

### Data Sources
1. **Median_Prices_Quarterly.csv**: Contains quarterly median house prices for various LSOAs within Leeds.
2. **Transaction_Count_Quarterly.csv**: Provides the quarterly transaction counts for the same LSOAs.
3. **Leeds_boundary.geojson**: Contains the geographic boundaries of Leeds' LSOAs.

### Files in This Repository
- `GEOG5995_Final_Project.ipynb`: The Jupyter Notebook containing the analysis.
- `Median_Prices_Quarterly.csv`: Dataset with median house prices.
- `Transaction_Count_Quarterly.csv`: Dataset with transaction counts.
- `Leeds_boundary.geojson`: GeoJSON file with Leeds LSOA boundaries.
- `GitHub_Link.txt`: A text file containing the link to this GitHub repository.

### Instructions to Run the Notebook
1. **Clone the Repository**:
    ```bash
    https://github.com/gy23xt/GEOG5995_Final_Project.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd GEOG5995_Final_Project
    ```
3. **Install Required Libraries**:
    Ensure you have Python installed. Then install the necessary libraries using pip:
    ```bash
    pip install pandas geopandas matplotlib
    ```
4. **Run the Jupyter Notebook**:
    Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
    Open `GEOG5995_Final_Project.ipynb` in the Jupyter interface and run the cells to execute the analysis.

### Description of Analysis
1. Data Loading and Preprocessing:
    - Load the median prices and transaction counts datasets.
    - Inspect and merge the datasets on the `lsoa_cd` column.
    - Load and inspect the GeoJSON file for Leeds.

2. Data Merging:
    - Merge the combined dataset with the GeoJSON file based on LSOA codes.
    - Ensure the geographic boundaries align correctly with the LSOA codes.

3. Visualization:
    - Non-Spatial Visualization: Plot the trend of median house prices over time for specific areas.
    - Spatial Visualization: Create geographic maps to show the distribution of median house prices and transaction counts across different LSOAs in Leeds.

### Final Plots
1. Geographic Distribution of Transaction Counts in Leeds:
    - A map showing transaction counts across different LSOAs.
2. Trend of Median Prices Over Time for Specific Area:
    - A line plot showing the relationship between transaction counts and median house prices over time.
3. Geographic Distribution of Median House Prices in Leeds:
    - A map displaying the distribution of median house prices across different LSOAs.

### Contact
For any questions or issues, please contact Xiaojing Tian at "gy23xt@leeds.ac.uk".

---

By following these instructions and using the provided files, you can replicate the analysis and explore the housing market dynamics in Leeds.
