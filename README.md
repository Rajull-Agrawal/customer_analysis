
# Customer Data Analysis

## Author: Rajul Agrawal

### Overview
This Jupyter notebook performs data analysis on customer-related datasets using PySpark. The analysis involves loading various datasets, cleaning data, transforming date formats, and displaying distinct demographic information.

### Dataset
The notebook processes the following CSV datasets:
- **Customer Product**: Contains product details held by customers.
- **Customer Channel Activity**: Captures customer interactions through various channels.
- **Customer Demographics**: Includes demographic details of customers.
- **Customer Transaction History**: Tracks customers' transaction details.
- **Product Lookup**: Provides details about different products.

### Key Steps
1. **Data Loading**: The datasets are loaded into PySpark DataFrames.
2. **Data Transformation**: 
   - A UDF is applied to standardize various date formats across the datasets.
   - The schema of each dataset is printed to understand the structure.
   - Distinct values of demographic fields like `Marital_Status` are analyzed.
3. **Data Export**: Commented-out sections allow exporting the DataFrames to CSV for further analysis.

### Dependencies
- PySpark
- Pandas
- Datetime
- Pgeocode (for geographic data processing)

### Tableau Dashboard
This analysis is complemented by a Tableau dashboard that visualizes key insights from the data. Screenshots of the dashboard can be added here.

![Dashboard 1](https://github.com/user-attachments/assets/dae892a5-e2c4-4f1a-bfcc-dacb66f3fab7)
![Dashboard 2](https://github.com/user-attachments/assets/3e13cad5-7777-4c96-bb5e-7158c6139d10)
![Dashboard 3](https://github.com/user-attachments/assets/ba2ec6fb-0181-46c1-825d-3b3e01bffe44)
