# Pakistan's Economic Pulse 2016-2025

📊 Pakistan's Economic Pulse (2016–2025) A decade of data, A vision for tomorrow  

🌟 Project Overview 

This project provides an integrated data science analysis of Pakistan's economic landscape from 2016 to 2025. It explores the complex interplay between climatic variability, industrial productivity (measured via the Quantum Index of Manufacturing - QIM), and national trade performance. By bridging the gap between environmental indicators and economic outputs, the study offers a holistic view of how heat stress and seasonal cycles impact Pakistan's manufacturing and trade deficit.

🚀 Key Features:

Integrated Data Pipeline: Merges diverse datasets covering climate (temperature/precipitation), manufacturing (QIM), and trade (Imports/Exports) into a unified analytical framework.

Real-Time SARIMAX Forecasting: A sophisticated Seasonal AutoRegressive Integrated Moving Average with eXogenous factors model that predicts trade trends 12 months into the future.

Interactive Streamlit Dashboard: A web-based application hosting dynamic visualizations, industry benchmarks, and correlation heatmaps.

Probabilistic Visualizations: "Fan chart" forecasts featuring 95% Confidence Intervals, acknowledging mathematical uncertainty in long-term economic trends.

🛠️ Technical Methodology Model Architecture: 

SARIMAX To move beyond simple linear correlations, we implemented a professional-grade SARIMAX model designed to handle the high volatility and seasonality of economic data.

Seasonality: Captures recurring 12-month "peaks and valleys" in manufacturing output.

Exogenous Variables: Utilizes month-based dummy variables to treat each month as a unique category, significantly improving the accuracy of seasonal cycle recognition. 

Data Normalization: Employs MinMaxScaler to ensure numerical stability for high-magnitude trade values.

Training Focus: Prioritizes data from 2016 onwards to ensure predictions reflect modern economic realities.

📈 Key Insights Obtained  

Climate-Industry Link: Statistical proof that Extreme Heat (>15 hot days/month) negatively impacts industrial factory output, creating a "heat tax" on productivity.

Seasonal Manufacturing: Clear evidence that manufacturing output slows during hot summer months (June–July) compared to the "busy season" (January–March).

Trade Dependency: Visual confirmation of Pakistan's consistent Trade Deficit, where imports significantly and consistently outpace exports.

💻 Tech Stack Language: 

Python  Framework: 

Streamlit (Web App)  

Libraries: * Data Manipulation: Pandas, NumPy  Visualization: Plotly (Interactive), Matplotlib, Seaborn  

Modeling: Statsmodels (SARIMAX), Scikit-learn (MinMaxScaler)  

👥 Contributors  

Muhammad Ali Hassan   

Malaika Salam

Wania Adnan

Ayesha Saleh
