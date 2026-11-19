# Agricultural Data Acquisition and Cleaning

## Week 1 – Agricultural Data Analytics Project

### Project Overview
This project focuses on acquiring, inspecting, cleaning, and validating agricultural crop production data using Python, Pandas, and SQL in Google Colab.

The project uses the **Crop Production in India** dataset from Kaggle. The objective is to transform raw agricultural data into a structured and reliable dataset suitable for further analysis.

### Student Details
- **Name:** Rounak Majumder
- **Department:** B.Tech CSE (AI/ML)
- **Project:** Agricultural Data Acquisition and Cleaning
- **Assignment:** Week 1

### Dataset Information
- **Dataset Name:** Crop Production in India
- **Source:** Kaggle
- **Dataset Link:** https://www.kaggle.com/datasets/abhinand05/crop-production-in-india

The dataset contains agricultural information such as:
- State Name
- District Name
- Crop Year
- Season
- Crop
- Area
- Production

*Note: The exact dataset structure and record count are verified during notebook execution.*

### Technologies Used
- Python
- Pandas
- DuckDB
- SQL
- Google Colab

### Project Objectives
1. Acquire agricultural data from a public dataset.
2. Understand the dataset structure and data types.
3. Identify missing and duplicate records.
4. Detect invalid and inconsistent values.
5. Standardise column names and text fields.
6. Convert numeric columns into appropriate data types.
7. Separate invalid records for manual review.
8. Generate a cleaned dataset.
9. Validate the cleaned data using SQL queries.
10. Generate summary reports for agricultural analysis.

### Data Cleaning Process
The following steps are performed:

**1. Data Acquisition**
- Download the agricultural dataset from Kaggle.
- Upload the CSV file to Google Colab.
- Load the dataset using Pandas.

**2. Data Inspection**
- Examine dataset dimensions.
- Inspect column names and data types.
- Preview sample records.
- Check missing and blank values.

**3. Data Cleaning**
- Handle missing values.
- Identify duplicate records.
- Remove unnecessary whitespace.
- Standardise text fields.
- Validate numeric measurements.
- Check invalid crop-year values.

**4. SQL-Based Validation**
- Perform data profiling using DuckDB SQL.
- Identify records that fail validation rules.
- Maintain a separate review table.
- Create a clean agricultural dataset.
- Perform post-cleaning validation.

**5. Data Transformation**
- Convert area and production into numeric values.
- Calculate yield per area where area is greater than zero.
- Generate agricultural summary tables.

### Repository Structure

```text
Agricultural-Data-Acquisition-and-Cleaning/
│
├── README.md
│
├── notebooks/
│   └── Week1_Agricultural_Data_Acquisition_and_Cleaning.ipynb
│
├── reports/
│   └── Week1_Agricultural_Data_Acquisition_and_Cleaning_Report.docx
│
├── data/
│   └── README.md
│
├── outputs/
│   ├── crop_production_clean.csv
│   ├── crop_production_review.csv
│   └── agricultural_summary.csv
│
└── screenshots/
    ├── dataset_preview.png
    ├── data_cleaning.png
    └── validation_results.png
```

### Expected Outputs
- **Clean Dataset:** Contains records that pass the defined cleaning rules.
- **Review Dataset:** Contains records requiring manual inspection.
- **Agricultural Summary:** Provides grouped agricultural statistics.
- **DuckDB Database:** Stores the staging, working, clean and review tables.

### How to Run the Project

1. Clone or download this repository.
2. Open the `.ipynb` notebook in Google Colab.
3. Install the required dependencies when prompted.
4. Download the CSV dataset from Kaggle.
5. Upload the CSV file when the notebook requests it.
6. Execute all notebook cells sequentially.
7. Review the cleaning and validation results.
8. Download the generated output files.

### Learning Outcomes
Through this project, the following concepts are demonstrated:
- Agricultural data acquisition.
- Data preprocessing and cleaning.
- Exploratory data inspection.
- SQL queries and data validation.
- Duplicate and missing-value handling.
- Data transformation and summarisation.
- Reproducible data-cleaning workflows.

### Conclusion
This project demonstrates a structured approach to agricultural data acquisition and cleaning using Python and SQL. The cleaned dataset can serve as a foundation for further agricultural analytics, including crop production trends, seasonal comparisons, and state-wise agricultural performance analysis.

---

**Author:** Rounak Majumder  
**Department:** B.Tech CSE (AI/ML)
