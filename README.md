# Oil and Gas Production Data Analysis

This project analyzes federal oil and gas production data from the Office of Natural Resources Revenue (OGORB).

## Dataset

The `OGORBcsv_cleaned.csv` file contains production records with the following information:
- Production dates
- Land classification and location details
- Commodity types (gas, oil, etc.)
- Disposition codes and descriptions
- Production volumes

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
Run the EDA script to understand the dataset:
```bash
python eda.py
```

This will:
- Load and examine the dataset structure
- Analyze production volumes by region, commodity, and time
- Identify key trends and patterns
- Generate summary statistics

### 2. Generate Visualizations
The EDA script automatically creates visualizations including:
- Production trends over time
- Regional production comparisons
- Commodity distribution analysis
- Disposition type breakdowns

Visualizations are saved in the `visualizations/` directory.

### 3. Generate Report
Create a professional report to share with colleagues. Choose between HTML or PDF format:

**For HTML Report:**
```bash
python generate_html_report.py
```

**For PDF Report:**
```bash
python generate_pdf_report.py
```

Both formats include:
- Executive summary
- All visualizations with captions
- Statistical summaries
- Narrative analysis of trends
- Key insights and findings from the data

The report combines verbal descriptions with visualizations to tell the complete story of the oil and gas production data.

## Requirements

Install required packages:
```bash
# Core packages
pip install pandas matplotlib seaborn numpy

# For PDF reports (optional)
pip install reportlab
```

## Getting Started

1. Ensure the CSV file is in the project directory
2. Install dependencies
3. Run the EDA script
4. Generate the HTML report
5. Open `report.html` in your browser to view the complete analysis
