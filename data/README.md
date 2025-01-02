# Data Cleaning Process

**Kaggle Raw Data Link:** https://www.kaggle.com/datasets/rkiattisak/sports-car-prices-dataset/data

**Scraped website, CarMax:** https://www.carmax.com/cars/sports-cars

## Overview

The raw dataset underwent several cleaning steps to ensure accuracy, consistency, and reliability. The cleaning process aimed to handle missing values, remove irrelevant or redundant columns, standardize data formats, and improve overall data quality.**The raw data can be found in the "Raw" folder, processed data in "Processed" folder, and the two data sets joined in "Combined" folder."**

---

## Cleaning Process

### 1. **Removal of Unnecessary Columns**

- **car_trim**: The "car_trim" column was removed as it did not contribute meaningful insights or impact pricing.
- **Unnecessary Symbols**: Symbols such as "$" and "k" were removed from the **mileage** column to convert shorthand notations (e.g., "8k" → 8000).

### 2. **Handling Missing Values**

- **Engine Size, Horsepower, and Acceleration Time**: Missing values were filled using the average of the respective **car_make** and **year**. This approach ensured more accurate data imputation based on the available context of the car models.

### 3. **Conversion of Data Types**

- **Mileage**: Converted to numeric values by removing symbols and treating any non-numeric entries as missing values.
- **Price**: Converted to numeric values by removing symbols like "$".

### 4. **Standardization of Column Values**

- **Year**: Standardized all entries to four-digit formats to avoid discrepancies.
- **Car Make and Model**: Standardized to ensure consistent naming conventions (e.g., "Ford" → "Ford", "BMW" → "BMW").
- **Engine Size & Horsepower Units**: Ensured that units were consistent across entries.
