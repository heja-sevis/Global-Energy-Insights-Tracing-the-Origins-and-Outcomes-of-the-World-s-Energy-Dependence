# 🔌 Global Energy Insights: Tracing the Origins and Outcomes

An advanced data science and machine learning dashboard designed to analyze, visualize, and forecast global energy consumption patterns. This project was developed as part of a **Computer Engineering Bachelor's Graduation Project**.

**🔗 Live:** [Global Energy Insights: Tracing the Origins and Outcomes View the Dashboard on Streamlit](https://global-energy-insights-tracing-the-origins-and-outcomes.streamlit.app)

---

## 🚀 Project Overview

This dashboard serves as a comprehensive tool for researchers and energy analysts to understand how energy consumption has evolved globally. It doesn't just show historical data; it applies data mining to find associations between energy types and machine learning to forecast future needs.

### 📊 Key Modules

* **🏠 Home:** Project mission and feature summary.
* **🌍 Global Map:** Spatial analysis of per capita energy consumption across different eras using interactive Plotly choropleth maps.
* **🌐 Deep Analysis:** Uses the **Apriori Algorithm** to identify hidden relationships between energy sources.
    * Dynamic filtering for **Support, Confidence, and Lift** metrics.
    * Correlation heatmaps to visualize the co-occurrence of energy usage.
* **📈 Growth Rates:** Real-time calculation of annual percentage changes in energy source consumption.
* **🗺 Country-Specific Breakdown:** Detailed "Energy Basket" analysis with automated insights on the most/least dominant sources for any selected country.
* **🔮 Predictive Forecasting:** Utilizes **Prophet** for robust time-series forecasting.
    * Predicts future consumption trends with uncertainty intervals (confidence levels).
    * Provides automated summaries of predicted growth or decline.

## 🛠 Technical Stack

| Category | Tools |
| :--- | :--- |
| **Framework** | Streamlit |
| **Data Handling** | Pandas, NumPy, Scikit-learn |
| **Data Mining** | MLxtend (Apriori & Association Rules) |
| **Forecasting** | Prophet (Time Series modeling) |
| **Visualization** | Plotly (Express & Graph Objects), Seaborn, Matplotlib |

## 📂 Data Source

The dataset is curated from Our World in Data (OWID), covering a wide range of energy metrics—including fossil fuels, renewables, and nuclear power—across over 200 countries from 1965 to 2024.

## 🎓 Graduation Thesis
This project was developed as my **Computer Engineering Graduation Thesis**. 

It represents a comprehensive study on global energy data, focusing on the implementation of data mining algorithms and machine learning models to analyze environmental impacts and future energy trends. The entire pipeline from data preprocessing and analysis to the deployment of the web-based dashboard was designed and implemented by me as the final requirement for my degree.

---
