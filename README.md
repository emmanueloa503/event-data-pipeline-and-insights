# Event Data Pipeline & Insights

### Python | Pandas | Data Cleaning | Data Transformation | Exploratory Data Analysis

## Project Overview

This project demonstrates an end-to-end data preparation, cleaning, transformation, and exploratory analysis workflow using Python.

The project uses **synthetic organizational and community health event datasets** to simulate real-world data quality challenges, build structured datasets, and generate actionable insights.

The workflow includes auditing organizational records, identifying missing values and duplicates, transforming data into a standardized template, integrating survey records from five events, and analyzing participant responses.

**All datasets used in this portfolio project are synthetic and intended for demonstration purposes.**

## Project Objectives

- Identify and assess data quality issues, including missing values, duplicate records, and inconsistent formatting.
- Clean and validate organizational data using Python and Pandas.
- Transform organizational records into a standardized reporting structure.
- Combine multiple event survey datasets into a unified analytical dataset.
- Analyze participant awareness, health-monitoring device use, and comfort communicating with healthcare providers.
- Communicate findings through visualizations and a presentation.

## Technologies Used

- **Python:** Data processing and analytical workflows
- **Pandas:** Data cleaning, manipulation, transformation, and aggregation
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Jupyter Notebook:** Reproducible analysis and documentation
- **Microsoft Excel:** Source data and transformed outputs
- **PowerPoint:** Presentation of findings and recommendations

## Dataset Overview

The project includes:

**Organizational Data:** A synthetic dataset containing 510 organizational records with attributes such as organization identifiers, names, locations, organization types, therapeutic areas, demographic focus, and reach counts.

**Event Survey Data:** 325 synthetic survey records collected across five fictional community health events, including pre-survey and post-survey responses.

## Data Processing Workflow

### 1. Data Quality Assessment
- Inspected data structures and column types.
- Identified missing values and duplicate records.
- Evaluated inconsistencies across organizational and event datasets.

### 2. Data Cleaning and Transformation
- Applied data-cleaning and standardization techniques.
- Prepared organizational records for a structured output template.
- Validated transformed data for consistency.

### 3. Event Data Integration
- Combined five event worksheets into one analytical dataset.
- Standardized relevant fields and survey response categories.
- Preserved event and survey-phase information for analysis.

### 4. Exploratory Data Analysis
- Compared pre-survey and post-survey response distributions.
- Examined cardiovascular awareness and comfort discussing symptoms with healthcare providers.
- Analyzed health-monitoring device use.
- Explored differences across age groups and events.

## Key Findings

Based on the synthetic event dataset:

| Metric | Pre-Survey | Post-Survey |
|---|---:|---:|
| High cardiovascular awareness | 21.9% | 29.8% |
| High comfort discussing symptoms | 16.9% | 21.2% |
| Regular health-monitoring device use | 27.4% | 26.5% |

Positive event satisfaction varied between 14.3% and 43.3%.

These findings demonstrate how event survey data can support descriptive analysis and identify opportunities for program improvement. Because the data is synthetic and the pre- and post-survey groups are not individually matched, these differences should not be interpreted as causal effects.

## Project Files

- `Event_Data_Pipeline_and_Insights_Portfolio.ipynb` — Python data preparation and analytics notebook.
- `Event_Data_Pipeline_Synthetic_Portfolio.xlsx` — Synthetic source workbook.
- `New_Template_Mock_Organizations_Completed.xlsx` — Standardized organizational output.
- `Event_Data_Pipeline_Insights_Portfolio_Presentation.pptx` — Seven-slide presentation summarizing analytical findings.

## How to Run

1. Download or clone this repository.
2. Install Python and the required packages.
3. Open the Jupyter notebook in VS Code or JupyterLab.
4. Ensure the synthetic Excel workbook is accessible at the path referenced in the notebook.
5. Run the notebook cells sequentially.

Example installation:

```bash
pip install pandas numpy matplotlib openpyxl jupyter
```

## Project Takeaways

This project demonstrates practical skills in data quality assessment, Python-based data transformation, analytical problem-solving, data validation, and communicating data-driven insights.

The emphasis is on building a reproducible workflow that converts imperfect source data into structured information for analysis and reporting.

## Author

**Emmanuel Owusu-Ampaw**

[GitHub Profile](https://github.com/emmanueloa503)
