# Marketing Campaign Data Cleaning

This project focuses on cleaning a messy marketing campaign dataset using Python (Pandas, NumPy) inside Jupyter Notebook.
This is my First Project Next Time will be better than it.
## 🔧 Data Cleaning Steps

1. **Column Name Cleaning**
   - Stripped whitespace, standardized casing, replaced spaces with underscores

2. **Handled Duplicate Columns**
   - Identified and removed duplicate columns (e.g., duplicate `Clicks` column), keeping the one with fewer NaN values

3. **Removed Duplicate Rows**
   - Checked and dropped duplicate records to ensure data integrity

4. **Date Format Standardization**
   - Converted `Start_date` and `End_date` to proper datetime format using `pd.to_datetime()`

5. **Impossible Value Masking**
   - Detected and masked logically impossible values (e.g., negative spend, clicks > impressions)

6. **Time-based Masking**
   - Applied masking based on date/time logic (e.g., End_date earlier than Start_date)

7. **Outlier Detection**
   - Identified outliers in numeric columns (Spend, Clicks, Impressions, Conversions) using statistical methods

8. **Feature Extraction — Season**
   - Extracted `Season` from `Start_date` to enable seasonal trend analysis

## 🛠 Tools Used
- Python, Pandas, NumPy
- Jupyter Notebook

