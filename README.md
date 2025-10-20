# Task-1
# 📊 Data Cleaning and Preprocessing Task

## 📄 Description
This project demonstrates the steps for **cleaning and preprocessing a dataset** to make it ready for analysis or machine learning.  
The dataset contains customer information including demographics, purchases, and behavior.

### ✅ Tasks Performed
- **Standardize Text Columns:**  
  Cleaned categorical text columns such as `Education` and `Marital_Status` for consistent naming.

- **Convert Date Columns:**  
  Standardized `Dt_Customer` to `dd-mm-yyyy` format and converted it to datetime type.

- **Fix Data Types:**  
  Ensured numeric columns like `Year_Birth`, `Income`, `Kidhome`, `Teenhome`, etc., have proper numeric types (`int` or `float`), and categorical columns are set as `category`.

- **Clean Column Headers:**  
  Renamed columns to lowercase, removed spaces, and special characters for uniformity.

- **Optional Step:**  
  Added `Age` column calculated from `Year_Birth`.



## 🗂️ Dataset
- Dataset used: `marketing_data.csv`
- Columns include:  
  `ID`, `Year_Birth`, `Education`, `Marital_Status`, `Income`, `Kidhome`, `Teenhome`, `Dt_Customer`, `Recency`, purchase amounts, etc.




