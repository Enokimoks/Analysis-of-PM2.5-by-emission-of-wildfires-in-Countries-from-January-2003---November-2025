# PM2.5 Wildfire Emissions Analysis (Python & Excel)

A concise, reproducible analysis of **PM2.5 emissions from wildfires**, built with **Python (Jupyter Notebook)** and **Excel dashboards**.  
The project transforms raw PM2.5 emission data into clear trends, country rankings, visual insights, and a polished PDF report.

---

## Project Overview

Wildfires are a major source of fine particulate matter (PM2.5), which poses serious air-quality and health risks.  
This project analyzes wildfire-related PM2.5 data to identify:

- Countries most affected by wildfire PM2.5  
- Long-term and short-term emission trends  
- Years and periods with emission spikes  
- Clear visual summaries suitable for reports and presentations  

The analysis is designed to be **simple, academic-ready, and reusable**.

---

## Tools & Technologies

- **Python** (Pandas, Matplotlib, Jupyter Notebook)
- **Excel** (Pivot Tables, Charts, Dashboard)
- **PDF export** for final reporting

---

## Dataset

- **Source:** Annual PM2.5 emissions from wildfires (CSV format)
- **Format:** Country, Year, PM2.5 emissions
- **Usage:** Raw CSV is loaded directly into Python and Excel for analysis

> Dataset is placed in the `data/` folder and remains unchanged for reproducibility.

---

## Project Structure

```text
pm25-wildfire-analysis/
│
├── data/
│   └── annual-pm25-emissions-from-wildfires.csv
│
├── notebooks/
│   └── pm25_analysis.ipynb
│
├── excel/
│   └── pm25_dashboard.xlsx
│
├── outputs/
│   └── pm25_analysis_report.pdf
│
└── README.md

