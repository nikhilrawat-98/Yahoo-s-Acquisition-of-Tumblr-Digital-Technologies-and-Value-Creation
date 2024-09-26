# Yahoo's Acquisition of Tumblr: Digital Technologies and Value Creation

This project explores Yahoo's acquisition of Tumblr and its implications in terms of digital technology and value creation. The analysis focuses on user growth, monetization challenges, and strategic opportunities related to Tumblr's platform and its value to Yahoo. The project evaluates Yahoo's $1.1 billion acquisition and analyzes whether it was an overvaluation, leveraging time series forecasting, API scraping, and data-driven insights.

## Project Overview

- **Objective**: To analyze the valuation of Yahoo's acquisition of Tumblr, focusing on user growth, revenue potential, market position, and strategic value creation.
- **Key Focus**:
  - Estimating future user growth and its implications for Tumblr’s valuation.
  - Analyzing monetization challenges related to advertising and user engagement.
  - Strategic opportunities presented by Tumblr’s unique user base and market position.
- **Tech Stack**: Python, Pandas, Matplotlib, TBATS, Exponential Smoothing, Selenium for web scraping.

## Dataset

The dataset includes metrics such as Tumblr user growth, traffic trends, demographic information, and monthly active users (MAUs) from 2013 to 2023. Data was sourced using API scraping and supplemented with external reports.

### Key Features of the Dataset:
- `Year`: The year of the recorded metric.
- `Number of Blogs`: The cumulative number of blogs on Tumblr in millions.
- `Demographics`: Demographic breakdowns of Tumblr users by age, gender, and geographic region.
- `Monthly Active Users (MAUs)`: The number of active users accessing Tumblr each month.
- `Traffic Data`: Traffic trends from 2018 to 2023, showing fluctuations in site visits.

### File Structure:
- **`code.ipynb`**: Jupyter notebook containing code for time series analysis, forecasting, and data scraping.
- **`Presentation slides.pdf`**: Presentation slides summarizing the key findings of Yahoo's acquisition of Tumblr and its implications.
- **`Report.pdf`**: Detailed report discussing the acquisition, valuation methodology, user growth forecasting, and monetization strategies.
- **`requirements.txt`**: Python dependencies required to run the analysis.

## Analysis Workflow

### 1. Data Collection
- **Web Scraping**: Data related to Tumblr’s user base, traffic, and demographic information was scraped using APIs and Selenium.
- **Data Sources**: Key data sources include Business Insider, Demand Sage, and public reports on Tumblr’s user statistics and growth trends.

### 2. Time Series Forecasting
- **Exponential Smoothing**: Used to forecast Tumblr's future user growth, leveraging historical data.
- **TBATS Model**: Employed for advanced forecasting of user growth trends, providing more accurate predictions with lower RMSE and MAE compared to Exponential Smoothing.

### 3. Valuation Methodology
- **Revenue Per User (ARPU)**: Projected future revenue potential based on user growth and engagement trends.
- **Strategic Implications**: Assessed Tumblr's unique value proposition, including its content ecosystem, user engagement, and potential for targeted advertising.

## Key Findings

### 1. User Growth Forecasting:
- **TBATS Model Performance**: TBATS outperformed Exponential Smoothing in predicting future user growth, with a much lower error rate. It suggests that Yahoo might have overestimated future growth during the acquisition.
  
### 2. Monetization Challenges:
- Despite increased user growth, Tumblr faced challenges in effectively monetizing its platform through advertising without alienating its user base.

### 3. Strategic Opportunities:
- The report identifies several strategic opportunities for Tumblr, including partnerships, expanding content offerings, and leveraging its unique user base for targeted advertising.

### 4. Overvaluation Concerns:
- Based on the TBATS forecast and ARPU analysis, it is suggested that Yahoo overpaid for Tumblr, driven by overly optimistic growth projections.

## Usage

The Jupyter notebook demonstrates the following:
1. **Data Collection**: Scraping data from various sources using APIs and Selenium.
2. **Time Series Analysis**: Implementing Exponential Smoothing and TBATS for user growth forecasting.
3. **Valuation Model**: Analyzing the acquisition's impact through revenue projections and user growth trends.

## Installation

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Yahoo-Tumblr-Acquisition.git
    cd Yahoo-Tumblr-Acquisition
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Acknowledgements

This project was developed as part of the MSc in Business Analytics at Bayes Business School, under the module **Digital Technologies and Value Creation**.

## License

MIT License
