# Smart Stock Insight Platform (AI-Based)

A high-performance financial analytics dashboard engineered to provide real-time market insights and volatility-aware trend predictions.

---

## Engineering Overview
This platform is a full-stack implementation designed to bridge financial data with automated analytical logic. It utilizes a multi-factor analysis engine to process live market feeds and generate actionable intelligence.

**Live Prototype:** [stockinsightai5.vercel.app](https://stockinsightai5.vercel.app/)

---

## Core Analytical Engine
The backend architecture implements a multi-factor analysis engine to evaluate market conditions:

* **Momentum Analysis:** Tracks RSI (Relative Strength Index) and 3-day trend vectors.
* **Volatility Detection:** Monitors Price Change (%) and Moving Average Crossovers (SMA).
* **Quantitative Scoring:** Generates an AI Score (-10 to +10) based on Volume Trend and Trend Strength.
* **Predictive Logic:** Computes a Confidence Score and Predicted Price using historical datasets.

---

## Technical Architecture

### Backend:
* **Python (Flask):** Architected the RESTful API for real-time data handling.
* **yFinance:** Integrated for high-fidelity historical and live market data retrieval.

### Frontend:
* **JavaScript & Chart.js:** Engineered interactive data visualizations for trend rendering.
* **Modern UI:** Developed a glassmorphism interface optimized for financial monitoring.

---

## Logic Workflow
1. **Ingestion:** Backend initiates a real-time fetch for the target security via yFinance.
2. **Processing:** The Python engine calculates indicators (RSI, SMA, Support/Resistance).
3. **Inference:** Analytical logic interprets data points to output a Buy/Sell/Hold signal.
4. **Visualization:** Data is serialized and pushed to the frontend for dynamic rendering.

---

## Developed By: Team Code Catalyst
* **Anuruddha Kumar Kahar**
* **Purohit Kamleshsingh Savalsingh**
* **Aayush Singh**
* **Shrimali Jainam Ravindrakumar**
* **Joshi Rudram Manojbhai**

---

## Disclaimer
This platform is for educational purposes only. Predictions are generated through algorithmic logic and do not constitute professional financial advice.
