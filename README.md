# 🇮🇳 India Agricultural Market Analysis Dashboard

## Project Overview

This project delivers a data-driven analysis of **India’s agricultural commodity markets**, focusing on how prices evolve across time, regions, and market conditions.

Using daily price data, the study examines **long-term price trends, market-wide volatility, price spread dynamics, seasonal (monsoon) effects, and structural shocks such as Covid-19**. The analysis is presented through **interactive Looker Studio dashboards**, enabling both high-level market monitoring and deep commodity-level exploration.

The objective is to translate complex price movements into **clear, actionable insights** that can support **procurement strategy, market risk assessment, and data-informed decision-making**.

## 🛠️ Tools & Technologies

- **Looker Studio** – Interactive dashboards and data storytelling  
- **Python** – Data preprocessing, volatility analysis, forecasting models  
- **Pandas & NumPy** – Data manipulation and time-series analysis  
- **Machine Learning** – Price forecasting and feature-based insights  
- **Statistical Analysis** – Volatility, spread correlation, and shock impact evaluation  
- **Kaggle Dataset** – Daily commodity prices across Indian markets
  
## ⭐ Key Insights

### 1️⃣ Market Overview & Long-Term Price Trends
- Average commodity prices in India show a **strong upward trend from 2001 to 2025**, indicating structural price growth rather than short-term fluctuations.
- The market covers **373 commodities across 3,900+ markets**, reflecting high geographic and product-level diversity.
- Price increases accelerate noticeably after major macro shocks, suggesting increased sensitivity to external factors.

### 2️⃣ Covid-19 Shock Impact
- The Covid period triggered a **sharp and persistent increase in agricultural commodity prices** across India.
- Volatility and price spread both peak during and after Covid, indicating **heightened market uncertainty**.
- Post-Covid prices do **not revert to pre-Covid levels**, suggesting a **structural shift rather than a temporary shock**.
- The Covid Shock Index highlights Covid as one of the most influential macro-level disruptors in the dataset.

### 3️⃣ Price Volatility & Spread Dynamics
- Price volatility varies significantly across commodities, with certain products consistently exhibiting **higher risk profiles**.
- The relationship between price spread and volatility is **positive but moderate**, indicating that spread alone does not fully explain market instability.
- High-volatility commodities tend to cluster in specific product groups, enabling **risk-based commodity segmentation**.
- Volatility distribution analysis allows classification of commodities into **recommended vs. avoid** categories based on risk thresholds.

### 4️⃣ Seasonal (Monsoon) Impact
- Agricultural prices display **clear seasonal patterns**, closely aligned with India’s monsoon cycle.
- During monsoon periods, increased supply pressure leads to **temporary price stabilization** for certain commodities.
- Outside monsoon seasons, price volatility and spread tend to increase, reflecting **supply uncertainty and regional dependency**.
- Seasonal insights help distinguish **structural price movements** from short-term seasonal fluctuations.

### 5️⃣ Forecasting & Machine Learning Insights
- Machine learning–based forecasting models are used to estimate **future price trajectories** for selected high-impact commodities.
- Forecast results indicate **continued upward pressure on prices**, especially for commodities with historically high volatility.
- Model outputs help identify **early warning signals** for potential price shocks.
- Forecasting insights support **proactive procurement planning** and forward-looking risk management.

## 📊 Dashboard İçeriği

The Looker Studio dashboard is structured into **five main analytical sections**, each designed to answer a specific market question.

### 🔹 1. KPI & Market Overview
- Overall market coverage: number of commodities, states, districts, and markets  
- Long-term average price trend (2001–2025)  
- Quality distribution (FAQ vs Non-FAQ commodities)  
- Geographic price distribution across India  

---

### 🔹 2. Covid Impact Analysis
- Covid Shock Index and period-based price comparison  
- Volatility and spread comparison across pre-Covid, Covid, and post-Covid periods  
- Identification of permanent price level shifts caused by Covid  

---

### 🔹 3. Price Volatility & Spread Analysis
- Commodity-level volatility distribution  
- Relationship between price spread and volatility over time  
- Identification of high-risk commodities based on volatility thresholds  
- Risk-based classification: recommended vs avoid commodities  

---

### 🔹 4. Seasonal (Monsoon) Impact Analysis
- Average price comparison between monsoon and non-monsoon periods  
- Seasonal volatility patterns  
- Regional monsoon impact heatmap  
- Identification of most and least monsoon-sensitive commodities  

---

### 🔹 5. Forecasting & Machine Learning Insights
- Price forecasts for selected high-impact commodities  
- Model performance metrics and error analysis  
- Forward-looking insights for future price risk scenarios  
- Use of forecasting results to support proactive decision-making

## 📁 Dataset

The analysis is based on a publicly available Kaggle dataset containing **daily agricultural commodity prices across Indian markets**.

- **Source:** Kaggle – Daily Commodity Prices of India  
  https://www.kaggle.com/datasets/khandelwalmanas/daily-commodity-prices-india  
- **Time range:** 2001–2025  
- **Coverage:** Multiple commodities, markets, districts, and states  

The dataset is used as-is for analytical purposes and visualized through interactive Looker Studio dashboards.

## 💡 Business Insights

- Agricultural commodity prices in India exhibit **structural upward trends**, indicating that price increases are driven by long-term market dynamics rather than short-term noise.
- **Volatility and spread metrics** serve as effective early indicators of market risk, enabling better prioritization of high-risk commodities.
- The **Covid-19 shock created a permanent price level shift**, increasing both volatility and uncertainty across markets.
- **Seasonal (monsoon) effects** temporarily stabilize prices but do not offset underlying structural pressures.
- **Forecasting insights** provide forward-looking signals that support proactive procurement planning and risk-aware decision-making.

Overall, integrating volatility analysis, macro-shock assessment, and forecasting enables a **more resilient and data-driven market strategy**.
## 👩‍💻 Author

**Dilay Bezazoğlu**  
Data Analyst | Data Science Trainee  

SQL, Python, BigQuery, Looker Studio, Data Visualization, Machine Learning  
Market Analytics, Price Volatility, Time Series Analysis  
🔗 GitHub: https://github.com/dilaybezazoglu 
