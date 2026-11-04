# Task 1: Data Preparation and Power BI Setup (Easy)

**Goal:** Import, clean and transform the Netflix data so it is ready for reporting and visualization.

## ✅ Workflow

| Step | What was done |
|---|---|
| 1. Import the dataset | Loaded `Dataset.csv` (8,790 rows, 10 columns) into Power BI |
| 2. Clean and transform | Promoted headers, set data types, split `duration` into number and unit, cleaned and trimmed text columns |
| 3. Handle missing values and duplicates | Removed error rows, blank rows and duplicates on `show_id`; removed the 287 rows where country was "Not Given" or blank; removed the blank genre |
| 4. Relationships and data model | Date Table to Netflix Dataset on `date_added`, and Netflix Dataset to Genre Table on `show_id` |
| 5. Validate accuracy | Checked all totals against the raw file (table below) |

## 🔍 Validation

| Check | Result |
|---|---|
| Total Titles | **8,502** |
| Total Movies | **5,868** |
| Total TV Shows | **2,634** |
| Total Countries | **85** |
| Total Genres | **42** |
| Rating categories | **14** |
| Genre Table rows | **18,689** |
| Years of data | **14** |

**Data notes**
- 287 rows with country "Not Given" were removed, leaving 8,503 titles.
- One record with a line break inside its title appears to be dropped by the CSV import, so the final count is 8,502.
- The `director` column also contains "Not Given" values; it was not needed for the reports.

## 🖼️ Screenshots

**Data model**

![Data Model](Data_Model.png)

**Validation numbers**

![Validation Numbers](Validation_Numbers.png)

⬅️ [Back to tasks](../readme.md)
