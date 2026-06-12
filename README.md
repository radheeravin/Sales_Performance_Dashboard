
# ⚡ AI Sales Performance Dashboard

A premium, AI-powered Streamlit dashboard built for real sales decisions. 6 interactive pages + built-in ML for forecasting, anomaly detection, and customer segmentation.

### 🧠 AI Analytics Engine
- *3-Month Sales Forecast* — Linear regression model projects revenue + confidence bands
- *Anomaly Detection* — Z-score flags unusual spikes/drops in sales & profit automatically  
- *RFM Customer Segmentation* — K-Means clustering labels customers: Champions, Loyal, At-Risk, etc.
- *Smart Insights* — Natural-language takeaways generated from your data, no SQL needed

### 📄 6 Interactive Pages
Page | What you get
🏠 **Overview** | Live KPIs, revenue trends, forecast, anomalies, geo map, AI insights feed
🗺️ **Regional Analysis** | State/city drill-down, regional trends, margin heatmaps
📦 **Product Intelligence** | Category + sub-category breakdown, top/bottom SKUs, discount impact analysis
👥 **Customer Insights** | RFM segments, top customers, repeat vs one-time buyer behavior
💰 **Profitability** | Margin trends over time, loss-making products, discount vs profit correlation
🚚 **Logistics** | Ship mode efficiency, delivery speed tiers, cost vs speed trade-offs
### 🎨 Premium UI
- Dark-mode glassmorphism with animated floating blobs
- Fully responsive grid layout for mobile + desktop
- Hover animations on KPI cards for instant feedback
- Modern typography with Google Fonts Inter

### ⚡ Quick Start
*1. Install*
pip install -r requirements.txt
*2. Run*
streamlit run dashboard.py
Plug in your `data/train.csv` Superstore-style dataset and get real-time analytics instantly.

### 🛠 Tech Stack
*Frontend*: Streamlit  
*Data*: Pandas + NumPy  
*Visuals*: Plotly interactive charts  
*AI/ML*: scikit-learn for forecasting + clustering

---

Want me to also make a shorter "landing page" version for GitHub README + a longer investor/demo version?
