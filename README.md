# Real-Time-Crypto-Market-Dashboard-using-Power-BI
A real-time interactive Power BI dashboard that visualizes key market metrics for over 100 cryptocurrencies. It highlights performance trends across 1h, 24h, and 7d timeframes with KPIs, top gainers/losers, and market cap breakdown.


## Project Overview
This project showcases a dynamic cryptocurrency market dashboard built using Power BI and powered by web-scraped data from [CoinGecko](https://www.coingecko.com/).  
Data extraction was performed using **Python**, utilizing `BeautifulSoup` and `Requests` to parse HTML content and extract metrics such as:

- Coin names & symbols  
- Current prices  
- Percentage changes (1h, 24h, 7d)  
- Trading volume  
- Market capitalization

The scraped data was cleaned and structured into tabular form using **Pandas** and **Excel**, then visualized in **Power BI**.  
The dashboard offers a clear, interactive overview of market movements, highlighting:

- Top gainers and losers  
- Volume leaders  
- Performance trends across timeframes

---

## Tools Used

| Tool            | Purpose                                      |
|-----------------|----------------------------------------------|
| Python          | Data scraping and preprocessing              |
| BeautifulSoup   | HTML parsing and data extraction from CoinGecko |
| Requests        | Sending HTTP requests to fetch web content   |
| Pandas          | Data cleaning and transformation             |
| Power BI        | Interactive dashboard and data visualization |
| Microsoft Excel | Optional: Data inspection and formatting     |
| GitHub          | Documentation and version control            |

---

## Data Source
Data was scraped directly from **[CoinGecko](https://www.coingecko.com/)** — a trusted cryptocurrency data aggregator.

### Data Collection Process:
- HTTP requests were sent to CoinGecko to fetch live HTML content.
- `BeautifulSoup` was used to parse and extract data.

### Key Metrics Extracted:
- Coin Name and Symbol  
- Current Price  
- 1h, 24h, and 7d % Change  
- 24h Trading Volume  
- Market Capitalization  

---

### DashBoard
**[Explore Dashbord](https://app.powerbi.com/view?r=eyJrIjoiNjQzYjBlOTQtODUzNy00YTA5LTlkMzMtNTlkZTgyOWYzNTEyIiwidCI6ImZlNGY2MDAyLTAzMjktNGI4Yi04NTZmLThhM2YzMGRiYjhkZiJ9)**

## Project Objective

The goal of this project is to turn raw, unstructured cryptocurrency market data into a structured, interactive Power BI dashboard to support data-driven decision making.

### Key Objectives:
1. Extract real-time crypto market data from CoinGecko using Python.
2. Structure and clean the data using Pandas and Excel.
3. Visualize key market indicators using Power BI.
4. Identify top-performing and underperforming coins.
5. Enable interactivity through slicers, filters, and dynamic visuals.

This project simulates a real-world **fintech analytics use case**, tailored to both technical and non-technical users.

---

## Insights

- **Short-Term Market Recovery**: Despite a negative 7-day trend, average 24h gains hint at potential market rebound.
- **Dominant Coins**: Bitcoin (BTC) and Ethereum (ETH) lead in market capitalization.
- **Top Gainers**: AAVE, TRX, and BCH exhibit strong short-term performance.
- **Top Losers**: PI, WIF, and TWT show significant declines, suggesting bearish sentiment.
- **Volume Concentration**: A few high-cap coins dominate trading activity, indicating liquidity centralization.

---

## Recommendations

- **Short-Term Trading**: Monitor 1h and 24h top gainers for potential trade opportunities.
- **Long-Term Investment**: Use 7-day trends and market cap data to assess stability and growth.
- **Risk Awareness**: Be cautious of high-volume coins showing negative trends — volatility risk is high.
- **Diversification Strategy**: Avoid overinvesting in consistently underperforming assets.
- **Monitor Volume Spikes**: Unusual spikes in volume may precede significant price action.

---

## Conclusion

This project demonstrates a complete data analytics pipeline:  
**From raw data scraping ➝ cleaning ➝ structuring ➝ visualization.**

Using:

- **Python (BeautifulSoup & Requests)** for web scraping  
- **Pandas & Excel** for data transformation  
- **Power BI** for interactive dashboard creation  

The final result is a real-time, insightful cryptocurrency dashboard — useful for investors, analysts, or fintech professionals.  
It effectively showcases end-to-end data analysis and visualization skills.

---

## Author

**Amankwe Amarachi Francisca**  
*Data Analyst*
