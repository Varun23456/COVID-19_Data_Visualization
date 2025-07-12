
# COVID-19 Data Visualization Dashboard

An interactive web-based dashboard for visualizing COVID-19 data and related air quality metrics. This project provides comprehensive data analysis and visualization tools to understand the pandemic's impact through multiple perspectives and interactive charts.

## Overview

The COVID-19 Data Visualization Dashboard is a comprehensive web application that presents COVID-19 pandemic data through interactive visualizations. The project includes multiple analytical perspectives including global statistics, regional comparisons, air quality correlations, and temporal trend analysis.

### Key Objectives
- **Data Visualization**: Create intuitive and interactive visualizations of COVID-19 data
- **Multi-Perspective Analysis**: Analyze pandemic data from various angles
- **Air Quality Correlation**: Explore relationships between COVID-19 and air quality
- **Regional Insights**: Compare data across different cities and regions
- **Temporal Analysis**: Track trends and patterns over time

## Features

### Core Visualizations
- **Global COVID-19 Statistics**: Worldwide pandemic overview and metrics
- **Regional Data Analysis**: City-wise and country-wise comparisons
- **Time Series Analysis**: Temporal trends and pattern identification
- **Air Quality Integration**: AQI data correlation with COVID-19 metrics
- **Interactive Charts**: Dynamic and responsive data visualizations

### Geographic Coverage
- **Global Data**: Worldwide COVID-19 statistics and trends
- **Indian Cities**: Detailed analysis for major Indian metropolitan areas
  - Delhi
  - Mumbai
  - Bangalore
  - Chennai
  - Hyderabad

### Chart Types
- **Line Charts**: Time series data and trend analysis
- **Bar Charts**: Comparative statistics and regional data
- **Interactive Maps**: Geographic data representation
- **Multi-axis Charts**: Correlation analysis between different metrics
- **Dashboard Widgets**: Summary statistics and key indicators

### Technical Features
- **Responsive Design**: Mobile-friendly and cross-browser compatible
- **Interactive Elements**: Hover effects, tooltips, and dynamic filtering
- **Data Processing**: Client-side data manipulation and analysis
- **Performance Optimization**: Efficient rendering and data handling
- **Modular Architecture**: Component-based structure for maintainability

## Installation

### Prerequisites
- **Web Browser**: Modern browser with JavaScript support (Chrome, Firefox, Safari, Edge)
- **HTTP Server**: Local server for development (optional but recommended)
- **Text Editor**: Any code editor (VS Code, Sublime, Atom)

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/covid19-data-visualization.git
cd covid19-data-visualization
```

2. **Open project locally:**
```bash
# Direct file access
open `index.html` directly in browser
```

## Project Structure

```
covid19-data-visualization/
├── index.html              # Main dashboard homepage
├── q1.html                 # Question 1: Global COVID-19 analysis
├── q2.html                 # Question 2: Overview page
├── q2_1.html              # Question 2.1: Detailed regional analysis
├── q2_2.html              # Question 2.2: City-wise comparisons
├── q2_3.html              # Question 2.3: Temporal trend analysis
├── q3.html                # Question 3: Advanced analytics
├── report.pdf             # Comprehensive project report
├── .vscode/               # VS Code configuration
│   └── settings.json      # Editor settings
├── archive/               # Data files and datasets
│   ├── covid.csv          # Main COVID-19 dataset
│   ├── Global_data.csv    # Global statistics
│   ├── q2_2.csv           # Question 2.2 specific data
│   ├── q2_bangalore_aqi.csv   # Bangalore air quality data
│   ├── q2_chennai_aqi.csv     # Chennai air quality data
│   ├── q2_covid.csv       # COVID-19 regional data
│   ├── q2_delhi_aqi.csv   # Delhi air quality data
│   ├── q2_hyderabad_aqi.csv   # Hyderabad air quality data
│   ├── q2_monthly.csv     # Monthly aggregated data
│   ├── q2_mumbai_aqi.csv  # Mumbai air quality data
│   └── q3_montly.csv      # Question 3 monthly data
├── CSS/                   # Stylesheets
│   ├── q1.css             # Question 1 specific styles
│   ├── q2_1.css           # Question 2.1 styles
│   ├── q2_2.css           # Question 2.2 styles
│   ├── q2_3.css           # Question 2.3 styles
│   ├── q3.css             # Question 3 styles
│   └── styles.css         # Global styles
└── JS/                    # JavaScript files
    ├── q1.js              # Question 1 functionality
    ├── q2_1.js            # Question 2.1 scripts
    ├── q2_2.js            # Question 2.2 scripts
    ├── q2_3.js            # Question 2.3 scripts
    ├── q3_1.js            # Question 3.1 functionality
    ├── q3_2.js            # Question 3.2 functionality
    └── q3_3.js            # Question 3.3 functionality
```

## Data Sources

### COVID-19 Data
- **Global Statistics**: Worldwide confirmed cases, deaths, and recoveries
- **Regional Data**: Country and state-level pandemic metrics
- **Temporal Data**: Daily, weekly, and monthly trend data
- **Demographic Data**: Age-group and population-based analysis

### Air Quality Data
- **AQI Metrics**: Air Quality Index for major Indian cities
- **Pollutant Data**: PM2.5, PM10, NO2, and other pollutant levels
- **Temporal Correlation**: Pre-pandemic vs. pandemic air quality
- **City Comparisons**: Multi-city air quality analysis

### Data Processing
- **Data Cleaning**: Preprocessing and validation of raw datasets
- **Aggregation**: Monthly and weekly data summaries
- **Normalization**: Standardized metrics for comparison
- **Integration**: Combining COVID-19 and air quality datasets

## Visualizations

### Question 1: Global COVID-19 Analysis
- **World Map**: Interactive global COVID-19 spread visualization
- **Timeline Charts**: Pandemic progression over time
- **Country Comparisons**: Comparative analysis of affected nations
- **Statistical Summaries**: Key metrics and indicators

### Question 2: Regional and Air Quality Analysis
- **City Dashboards**: Individual city analysis pages
- **AQI Correlation**: COVID-19 vs. air quality relationships
- **Multi-City Comparison**: Side-by-side city comparisons
- **Temporal Trends**: Before, during, and after lockdown analysis

### Question 3: Advanced Analytics
- **Predictive Models**: Trend forecasting and projections
- **Statistical Analysis**: Correlation coefficients and significance tests
- **Pattern Recognition**: Seasonal and cyclical pattern identification
- **Comparative Studies**: Cross-regional and cross-temporal comparisons

## Technical Details

### Frontend Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Responsive design and animations
- **JavaScript (ES6+)**: Interactive functionality and data processing
- **D3.js**: Advanced data visualization framework
- **Chart.js**: Chart rendering and interactions

### Data Processing
- **CSV Parsing**: Client-side CSV data processing
- **Data Transformation**: Real-time data manipulation
- **Statistical Calculations**: Mean, median, correlation analysis
- **Filtering and Aggregation**: Dynamic data filtering

### Performance Optimization
- **Lazy Loading**: On-demand data loading
- **Caching**: Browser-based data caching
- **Minification**: Optimized CSS and JavaScript
- **Responsive Images**: Adaptive image loading

### Browser Compatibility
- **Modern Browsers**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Mobile Support**: Responsive design for tablets and phones
- **Progressive Enhancement**: Fallbacks for older browsers


## Known Issues and Limitations

### Current Limitations
- **Data Currency**: Datasets may not reflect real-time updates
- **Browser Dependency**: Requires JavaScript-enabled browser
- **Large Datasets**: Performance may vary with very large datasets
- **Offline Usage**: Requires internet connection for external libraries

### Future Enhancements
- **Real-Time Data**: Integration with live data APIs
- **Additional Metrics**: More comprehensive health and economic indicators
- **Machine Learning**: Predictive analytics and trend forecasting  
