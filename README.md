# Tesla Stock Analysis: Historical Share Price and Revenue

This Python script performs an analysis of Tesla's historical share price and revenue, plotting the data to visualize trends over time. It uses yfinance to retrieve historical stock price data and web scraping techniques via requests and BeautifulSoup to gather Tesla's quarterly revenue information.

## Overview

The code utilizes yfinance to extract Tesla's historical stock data and web scraping methods to obtain quarterly revenue data from Macrotrends. The collected data is then visualized using Plotly, providing a comparative view of Tesla's historical share prices and revenue in a graphical format.

## Usage

### Prerequisites

- Python 3.x
- Required libraries are included in the script. If not installed, use:
    ```bash
    pip install pandas yfinance requests plotly
    ```

### Execution

1. Open the Python script in your preferred editor.
2. Run the script to gather historical share price and revenue data for Tesla.
3. Utilize the `plot_graph` function to generate and display the Plotly graph, illustrating Tesla's historical share prices and revenue trends.

### Code Breakdown

- **Historical Stock Price:** Utilizes yfinance to extract Tesla's historical stock price data.
- **Revenue Data Retrieval:** Performs web scraping using requests and BeautifulSoup to collect Tesla's quarterly revenue information from Macrotrends.
- **Visualization:** Uses Plotly to create a graph illustrating the historical trends of Tesla's share price and revenue.

## Results

The generated graph showcases Tesla's historical share prices and revenue over time, allowing users to observe and analyze the trends and potential correlations between stock performance and revenue.

## Additional Notes

- The code is specific to Tesla (TSLA) and Macrotrends' data structure; modifications may be required for different stocks or websites.
- Additional features or analyses can be added to this code for more in-depth insights into Tesla's financial performance.

Feel free to use, modify, or extend this code for further analysis or adapt it to cater to your specific needs.

For more detailed insights and instructions, refer to the script itself or reach out for additional assistance or inquiries.

Happy analyzing! 📈✨
