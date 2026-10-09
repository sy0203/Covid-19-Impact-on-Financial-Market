
# COVID-19 Impact on Global Financial Markets

---

## Project Overview

This project investigates the relationship between the COVID-19 pandemic and global stock market performance through statistical analysis and interactive data visualization.

Using historical COVID-19 case counts and stock market index data, we developed a Python-based application to examine how financial markets responded to the pandemic and recovered over time.

The project compares five countries:

- United States
- Brazil
- France
- India
- Japan

**Objective:** Analyze changes in stock market performance during COVID-19, evaluate relationships between infection cases and stock prices, and compare financial market recovery across countries.

---

## Methodology

### 1. Data Collection & Preprocessing

- Collected historical COVID-19 case counts and stock market index data.
- Organized country-specific datasets into CSV files.
- Processed and transformed time-series data for statistical analysis.
- Calculated percentage changes in stock index prices and summarized COVID-19 case trends.

### 2. Statistical Analysis

Applied descriptive statistics and correlation analysis to evaluate financial market behavior.

Key measures included:

- Mean percentage change
- Median percentage change
- Standard deviation
- Correlation coefficients
- Percentage change in stock index prices
- Time required for market recovery

Correlation analysis was used to examine the direction and strength of the relationship between COVID-19 case counts and stock market performance.

### 3. Data Visualization

Developed visualizations using Plotly to compare financial market trends across countries.

**Visualizations include:**

- **Choropleth Map:** Geographic comparison of stock market recovery.
- **Time-Series Line Graphs:** Stock market index performance over time.
- **Country-Level Comparisons:** COVID-19 case trends alongside stock index performance.
- **Scatterplots:** Relationships between COVID-19 cases and stock market prices.
- **Recovery Tables:** Comparison of stock market recovery across countries.

### 4. Interactive Application Development

Built a Python application using Pygame to allow users to explore different countries and financial indicators.

The application includes:

- Interactive navigation menus
- Country-specific analysis
- Statistical summaries
- Multiple visualization options
- Comparative financial market recovery information

---

## Key Findings

### 1. Global Stock Market Recovery

The analysis identified substantial market fluctuations during the COVID-19 pandemic.

All five countries examined eventually recovered to or exceeded their pre-pandemic benchmark index levels within the observed dataset.

However, recovery patterns and rates varied across countries.

### 2. Differences Across Countries

The examined markets experienced different magnitudes of stock price changes.

In the project's comparative analysis:

- Brazil recorded the highest percentage increase.
- India recorded the lowest percentage increase.
- Recovery timelines differed across markets.

These results highlight differences in financial market performance during the pandemic.

### 3. COVID-19 Cases and Stock Market Performance

Correlation analysis was used to examine relationships between COVID-19 case counts and stock index price changes.

The analysis demonstrates how statistical methods can be used to investigate relationships between public health developments and financial market trends.

However, correlation does not establish a causal relationship between COVID-19 infections and stock market movements.

---

## Tools & Technologies

| Category | Tools |
|---|---|
| Programming | Python |
| Data Processing | Python CSV Module |
| Statistical Analysis | Descriptive Statistics, Correlation Analysis |
| Visualization | Plotly |
| Interactive Application | Pygame |
| Data Structure | CSV, Python Classes and Functions |

---

## Repository Structure

```text
Covid-19-Impact-on-Financial-Market/
│
├── main.py
├── calc_helper.py
├── graph_manager.py
├── info_collection.py
├── world_map.py
├── stock_data_filter.py
│
├── Filtering _Covid_19_cases.py
├── Transforming_Covid_19_cases.py
├── Transforming_Covid_19_cases_2.py
│
├── Brazil_cases.csv
├── Brazil_stock.csv
├── France_cases.csv
├── France_stock.csv
├── India_cases.csv
├── India_stock.csv
├── Japan_cases.csv
├── Japan_stock.csv
│
├── data/
├── proj1/code/
└── us_stock_data.png
```

**Main Components:**

- `main.py`: Interactive application and user interface.
- `calc_helper.py`: Statistical calculations and data structures.
- `graph_manager.py`: Data visualization functions.
- `info_collection.py`: CSV data loading and processing.
- `stock_data_filter.py`: Stock market data filtering.
- `world_map.py`: Geographic visualization-related code.
- `Transforming_Covid_19_cases.py`: COVID-19 data transformation.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sy0203/Covid-19-Impact-on-Financial-Market.git
cd Covid-19-Impact-on-Financial-Market
```

### 2. Install Required Libraries

```bash
pip install pygame plotly
```

### 3. Run the Application

```bash
python main.py
```

**Note:** The application uses local CSV datasets and was originally developed in 2021. Depending on your Python environment, some file paths or dependencies may require adjustments.

---

## Limitations

- The analysis examines a selected group of five countries and does not represent all global financial markets.
- Correlation analysis cannot establish causation.
- Stock market performance may also be influenced by monetary policy, government interventions, investor expectations, and other economic factors.
- The findings reflect the historical observation period and should not be interpreted as current market conditions.

---

## Project Significance

This project demonstrates the application of Python programming, statistical analysis, and interactive visualization to a real-world economic problem.

By combining public health data with financial time series, the application provides an accessible way to explore international market trends and compare recovery patterns during the COVID-19 pandemic.

**Key Skills Demonstrated:**
- Python Programming
- Statistical Data Analysis
- Data Cleaning and Transformation
- Time-Series Visualization
- Correlation Analysis
- Interactive Application Development
- Object-Oriented Programming
