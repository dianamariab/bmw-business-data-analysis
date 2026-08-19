# BMW Group Business Data Analysis

This project was developed as part of my Decision Support Systems coursework. The main objective was to analyze different aspects of BMW Group's activity using database management, data analysis, forecasting and data visualization techniques.

The project combines publicly available BMW Group data with simulated records created for academic purposes.

## Tools Used

- Microsoft Excel
- Microsoft Access
- Power BI

## Project Overview

The project was divided into several parts, starting with the organization and preparation of the data and continuing with statistical analysis, visualization, forecasting and decision analysis.

### Database Management

The data was initially organized in Excel and then imported into Microsoft Access.

The database contains information about:

- products
- customers
- employees
- jobs
- company locations
- sales
- financial indicators
- stock prices

Relationships between the tables were created in Access, followed by several queries used to explore sales, transaction values and employee information.

### Data Cleaning and Analysis

Excel was used to check and prepare the data before the analysis.

Some of the tasks included:

- checking text formatting
- validating phone numbers
- checking date values
- formatting numerical and financial data
- identifying possible outliers using the IQR method
- calculating descriptive statistics for financial indicators

The financial analysis included indicators such as revenue, EBITDA, net profit, total assets, equity and total liabilities.

### Power BI Dashboard

An interactive Power BI dashboard was created to summarize and visualize different aspects of the data.

The dashboard includes:

- revenue evolution between 2014 and 2024
- total sales
- employee distribution by country
- product sales by brand
- model distribution by vehicle category
- geographical information about company locations
- filters for brand and country

![Power BI Dashboard](images/power-bi-dashboard.png)

### Forecasting

The project also includes a time series analysis of BMW Group's stock closing prices.

Several forecasting methods were compared:

- moving average
- exponential smoothing
- TREND function
- linear regression
- Holt-Winters

The predicted values were compared with actual stock prices to evaluate the results of the different methods.

### Decision Analysis

A decision-making problem was analyzed using the TOPSIS method.

Three strategic alternatives were compared based on several criteria related to operational capacity, estimated costs and strategic impact. The purpose was to compare the alternatives using multiple criteria rather than relying on a single indicator.

## Repository Structure

```text
bmw-business-data-analysis/
│
├── analysis/
│   ├── descriptive-statistics.xlsx
│   ├── forecasting.xls
│   └── topsis-analysis.xlsx
│
├── data/
│   └── Bazadate_SSD.xlsx
│
├── database/
│   └── ProiectSSD_BD.accdb
│
├── images/
│   └── power-bi-dashboard.png
│
├── power-bi/
│   └── Dashboard_SSD.pbix
│
├── report/
│   └── bmw-business-data-analysis-report.pdf
│
└── README.md
```

The repository contains the files used for the different parts of the project. The Excel files include the descriptive analysis, forecasting and TOPSIS analysis, while the Access database contains the relational database implementation and the Power BI file contains the interactive dashboard.

The complete academic report is also included for additional details about the methodology and results.

## What I Learned

This project gave me the opportunity to work with different stages of a data analysis process, from organizing and checking the data to analyzing and visualizing the results.

I gained practical experience with Excel, Access and Power BI, as well as with forecasting and multi-criteria decision analysis. It also helped me understand how different tools can be combined to explore data and support business decisions.

## Project Context

This is an individual academic project developed as part of my university coursework in Decision Support Systems.
