# IPO_Analysis
Data-driven analysis of 264 Indian IPOs (2010–2021) using Python, statistical modeling, and Power BI to identify the key drivers of IPO listing performance.
# IPO Success Drivers in India (2010–2021)

A data-driven analysis of 264 Indian IPOs to identify the key factors influencing listing-day performance using statistical analysis, regression modeling, and interactive dashboards.

---

## Overview

This project investigates the major drivers of IPO listing gains in India between 2010 and 2021. The analysis combines financial data, investor subscription metrics, market sentiment indicators, and statistical techniques to understand what contributes to successful IPO performance.

The project covers the complete analytics workflow, including data cleaning, exploratory data analysis, hypothesis testing, regression analysis, dashboard development, report writing, and presentation creation.

---

## Dataset

### IPO Dataset

* 264 Indian IPOs (2010–2021)
* Issue Size
* QIB Subscription
* HNI Subscription
* Retail Subscription
* Total Subscription
* Listing Prices
* Listing Gains (%)

### Market Sentiment Dataset

* NIFTY 50 historical data
* Open, High, Low, Close prices
* Trading volume and turnover
* NIFTY 30-Day Return
* NIFTY 90-Day Return

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* SciPy
* Statsmodels
* Matplotlib
* Seaborn
* Microsoft Excel
* Power BI

---

## Project Workflow

### 1. Data Loading

* Imported IPO and NIFTY datasets.
* Performed initial inspection and validation.

### 2. Data Cleaning

* Handled missing values.
* Standardized formats.
* Converted data types.
* Removed inconsistencies.

### 3. Exploratory Data Analysis

* Distribution analysis.
* Trend analysis.
* Correlation analysis.
* Category-based performance analysis.

### 4. Feature Engineering

* Subscription categories.
* Institutional confidence groups.
* Issue size categories.
* Market sentiment variables.

### 5. Statistical Analysis

* Correlation analysis.
* T-tests.
* ANOVA tests.
* Hypothesis testing.

### 6. Regression Analysis

* Multiple Linear Regression (OLS).
* Variable significance testing.
* Model evaluation using R² and p-values.

### 7. Power BI Dashboard

* Market Overview
* Demand Analysis
* Institutional Participation Analysis
* Market Sentiment Analysis

### 8. Reporting and Presentation

* Detailed project report.
* PowerPoint presentation.
* Interactive dashboard.

---

## Dashboard Features

* KPI cards
* Interactive slicers
* Trend analysis
* Scatter plots
* Correlation analysis
* Year-wise performance tracking
* Category-based comparisons
  <img width="1382" height="777" alt="SHEET 1" src="https://github.com/user-attachments/assets/c93f9112-2e1b-469f-aa8b-bc46537fa71e" />
  <img width="1380" height="780" alt="SHEET 2" src="https://github.com/user-attachments/assets/e49cb6eb-c6c7-47a5-906e-d0da65e468f4" />
  <img width="1382" height="802" alt="SHEET 3" src="https://github.com/user-attachments/assets/c922568b-4d74-465b-ba65-b960060263fe" />
  <img width="1382" height="783" alt="SHEET 4" src="https://github.com/user-attachments/assets/342466be-9869-47ed-8123-ee9d6954ba9d" />





---

## Key Results

* Subscription demand emerged as the strongest predictor of IPO performance.
* High-demand IPOs generated significantly higher listing gains.
* Institutional participation positively influenced returns but lost significance after controlling for demand.
* Market sentiment showed a weak positive relationship.
* Issue size demonstrated moderate impact on listing performance.

---

## Project Structure

```text
IPO-Success-Drivers-India/
│
├── Dashboard Screenshots/
├── Engineered Dataset/
├── ORIGINAL DATASET/
├── PYTHON FILES/
├── Presentation/
├──Report/
├── Dashboard.pbix
└── README.md
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/IPO-Success-Drivers-India.git
```

2. Install required libraries.

```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels
```

3. Open the Jupyter notebook and run all cells.

4. Open the Power BI dashboard (.pbix file).

5. View the report and presentation files.

---

## Author

**Gopal Agarwal**

NIT Rourkela

Finance and Data Analytics Enthusiast
