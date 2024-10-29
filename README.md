# Cryptocurrency Data Analysis

This project is an ongoing data pipeline that gathers, stores, and visualizes cryptocurrency data to uncover trends and insights. Using **Python**, **SQL Server**, and **Power BI**, the pipeline collects real-time data from the CoinMarketCap API and processes it for analysis.

## Project Goal 🎯
The main goal of this project is to:
- Collect up to 3 months of cryptocurrency data.
- Store the data in SQL Server for efficient querying and analysis.
- Visualize data trends in Power BI, highlighting market movements and price fluctuations.

## Workflow 📈
1. **Data Collection**: Using Python, the pipeline connects to the CoinMarketCap API to fetch daily cryptocurrency data (price, market cap, trading volume).
2. **Data Storage**: Data is stored in SQL Server for trend analysis and historical comparison.
3. **Data Visualization**: Power BI dashboards provide insights into market trends and fluctuations, helping uncover patterns over time.

## Project Components 🛠️
- **Python**: For API integration and data processing.
- **SQL Server**: To store and manage the data.
- **Power BI**: For creating interactive dashboards to visualize market trends.

## Setup 🔧
### Requirements
- Python 3.x
- SQL Server
- Power BI
- CoinMarketCap API Key (sign up at https://coinmarketcap.com/api/)

### Running the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/tonydum/crypto-market-analysis.git
    ```
2. Install required Python packages:
    ```bash
    pip install requests pyodbc
    ```
3. Add your API key and configure your SQL Server connection in the script.
4. Run the Python script to fetch and store data.

## Future Work 🚀
- Automating data collection at regular intervals.
- Expanding the dashboard with comparative analysis between cryptocurrencies.
- Exploring additional data sources for deeper market insights.

Stay tuned for updates!

## License
This project is licensed under the MIT License.
