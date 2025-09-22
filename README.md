# U.S. Energy Analytics Dashboard

## Project Overview
Interactive Power BI dashboard analyzing 35 years of U.S. energy consumption data (1990-2024). Built with a complete ETL pipeline from EIA API data extraction to executive-ready visualizations, revealing key insights into America's energy transition.

## Dashboard Preview
<img width="1478" height="856" alt="image" src="https://github.com/user-attachments/assets/22d1afa3-8b7c-40f7-919f-c52300c8338d" />

*Executive Overview: 35-year energy consumption trends and source breakdown*

<img width="1472" height="853" alt="image" src="https://github.com/user-attachments/assets/6fe11787-a0f1-42ef-bddf-68de0bde9eef" />

*Energy Transition: Fuel switching patterns and renewable growth analysis*

## Key Insights Discovered
- **Natural Gas Dominance**: Leading energy source at 165+ trillion BTU (37% of total mix)
- **Coal Decline**: Dramatic 60%+ reduction from peak consumption levels  
- **Renewable Growth**: Doubled from ~19K to 43K trillion BTU over 35 years
- **Energy Transition**: Clear shift from traditional fossil fuels to cleaner sources

## Tech Stack
- **Python**: Data extraction, API integration, and transformation
- **PostgreSQL**: Data storage, views, and advanced SQL queries  
- **Power BI**: Interactive dashboards and business intelligence
- **EIA API**: U.S. Energy Information Administration data source

## Advanced Python Analytics

### Statistical Visualizations
- **Four Forces Analysis**: Area charts showing the major energy transformation patterns
- **Investment Performance Metrics**: 20-year returns analysis with risk thresholds  
- **Correlation Matrix**: Statistical relationships between energy sources
- **Portfolio Allocation Framework**: Strategic categorization of energy investments

### Key Statistical Findings
- **Renewable Energy**: 122% growth over 20 years (strongest performer)
- **Coal**: -58.8% decline (clear divestment signal)  
- **Natural Gas**: 72.7% growth (reliable growth play)
- **Strong negative correlation** (-0.9) between coal and natural gas consumption

![Four Forces Analysis]
<img width="2486" height="1533" alt="image" src="https://github.com/user-attachments/assets/0ce8edf3-61de-4da6-afab-5adb5e4eacd2" />

![Correlation Matrix]
<img width="1068" height="1012" alt="image" src="https://github.com/user-attachments/assets/2eef502f-9bc1-4426-8f6d-15819d7a9e4d" />



## Dashboard Features

### Page 1: Executive Overview
- **35-year trend analysis** across all major energy sources
- **Interactive time-series** visualizations with year filtering
- **Energy source rankings** and consumption breakdowns
- **Total consumption metrics** and summary statistics

### Page 2: Energy Transition Analysis  
- **Traditional vs renewable** energy mix comparison (donut chart)
- **Coal vs natural gas** fuel switching patterns (dual line chart)
- **Renewable energy growth** trajectory over time
- **Key transition metrics** for current year (2024)

## Data Sources & Methodology
- **Primary Source**: U.S. Energy Information Administration (EIA) API
- **Data Coverage**: 8 major energy series spanning 1990-2024
- **Update Frequency**: Monthly data aggregated to annual totals
- **Data Units**: Trillion British Thermal Units (BTU)
- **Quality Assurance**: Automated data validation and unit conversion

## Setup Instructions

### Prerequisites
- Python 3.8+
- PostgreSQL 12+
- Power BI Desktop
- EIA API access

### Installation
1. **Clone the repository**

git clone https://github.com/yourusername/energy-analytics-dashboard.git
cd energy-analytics-dashboard



2. **Install Python dependencies**

pip install -r requirements.txt



3. **Set up PostgreSQL database**

psql -U postgres -f scripts/database_setup.sql



4. **Configure API access**

Add your EIA API key to environment variables

export EIA_API_KEY="your-api-key-here"



5. **Run data extraction pipeline**

python scripts/data_extraction.py



6. **Open Power BI dashboard**
- Launch Power BI Desktop
- Open `energy markets project.pbix`
- Update data source connection to your PostgreSQL instance

## Business Impact
This dashboard enables energy stakeholders to:
- **Monitor energy transition progress** with quantified, time-series metrics
- **Identify emerging market trends** for strategic investment decisions  
- **Benchmark renewable growth** against traditional energy sources
- **Support data-driven policy** development and energy planning

## Technical Highlights
- **Full ETL Pipeline**: Automated data flow from API to visualization
- **Real-time Data Integration**: Direct connection to EIA's official datasets
- **Advanced SQL Views**: Optimized queries for dashboard performance
- **Interactive Filtering**: Dynamic year and energy source selection
- **Professional Design**: Executive-ready formatting and styling
- **Scalable Architecture**: Easily extendable to additional data sources

## Future Enhancements
- [ ] Add state-level energy consumption breakdowns
- [ ] Implement forecasting models for energy trends
- [ ] Include energy price data integration
- [ ] Add carbon emissions analysis
- [ ] Deploy dashboard to Power BI Service

## Project Learnings
- **API Integration**: Handling complex government data APIs with rate limiting
- **Data Quality**: Managing inconsistent units and missing values across decades
- **Dashboard Design**: Balancing executive-level insights with detailed analysis
- **ETL Optimization**: Building efficient data pipelines for regular updates

## Connect With Me
- **LinkedIn**: [https://www.linkedin.com/in/lorenzo-jara-jr-9479a6337/]  
- **Email**: [lorenzoj1202@gmail.com]

---

