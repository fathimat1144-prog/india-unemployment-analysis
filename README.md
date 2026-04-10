# India Unemployment Analysis During COVID-19

## Overview
This project analyzes unemployment trends in India during the COVID-19 period using two unemployment datasets. The notebook focuses on how unemployment changed before and after the nationwide lockdown, differences between rural and urban areas, and which regions were most affected.

The project also includes a professional dashboard built with Matplotlib for visualizing unemployment patterns across time and regions.

## Objectives

- Analyze unemployment trends in India during 2020
- Compare unemployment before and after the COVID-19 lockdown
- Study rural vs urban unemployment differences
- Identify regions with the highest unemployment rates
- Explore the relationship between labour participation and unemployment
- Build a visual dashboard for economic insights

## Dataset Information

This project uses the following datasets:

1. 'Unemployment in India.csv'
2. 'Unemployment_Rate_upto_11_2020.csv'

The datasets contain:

- Region / State
- Date
- Area Type (Urban / Rural)
- Estimated Unemployment Rate (%)
- Estimated Employed Population
- Labour Participation Rate (%)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

india-unemployment-analysis/
├── data/
│   ├── Unemployment in India.csv
│   └── Unemployment_Rate_upto_11_2020.csv
├── notebooks/
│   └── india_unemployment_analysis.ipynb
├── README.md
└── requirements.txt

## Key Analysis Performed

- Data cleaning and preprocessing
- Date conversion and missing value handling
- National unemployment trend analysis
- Rural vs urban unemployment comparison
- Pre-lockdown vs post-lockdown analysis
- Regional unemployment peak analysis
- Employment vs unemployment scatter analysis
- Labour participation vs unemployment trend analysis

## Dashboard Features

- National unemployment timeline
- Rural vs urban trend chart
- Lockdown impact comparison
- Top regions by unemployment rate
- Employment vs unemployment relationship
- Labour participation vs unemployment relationship

## Key Findings

- Unemployment increased sharply after the COVID-19 lockdown.
- Urban unemployment was generally higher than rural unemployment.
- Some regions experienced unemployment spikes above 20%.
- Labour participation rate showed a relationship with unemployment trends.
- Employment levels dropped significantly during peak lockdown months.

## How to Run the Project

1. Clone the repository
2. Open the project folder
3. Install dependencies using 'pip install -r requirements.txt'
4. Launch Jupyter Notebook using 'jupyter notebook'
5. Open the notebook file and run all cells

## Future Improvements

- Add interactive charts using Plotly
- Build a Streamlit dashboard version
- Include state-wise map visualizations
- Add forecasting for unemployment trends
- Compare unemployment across multiple years

## Author

Tabassum Fathima
