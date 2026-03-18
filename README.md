# 🌍 Geopolitical Energy Analysis Dashboard

A **1-page interactive Power BI dashboard** built using **Excel + Power BI** to visualize the intersection of global energy markets, geopolitical conflict, and strategic risk.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 🛢️ Total Oil Production | **13 Billion** barrels |
| 💰 Total Military Spending | **$446.05K** |
| ⚠️ High Risk Routes | **367** |
| 📈 Average Brent Price | **$99.44 / barrel** |
| 🌐 Countries in Conflict | **22** |

---

## 🗺️ Dashboard Sections

### 1. KPI Summary Cards
* 5 top-level KPI cards for instant executive-level insights
* Covers oil production, military spending, risk routes, pricing, and conflict count

### 2. Total Country by Role in Conflict *(Horizontal Bar Chart)*
* **7 conflict roles** tracked: Supporter, Direct, Strategic Ally, Energy Supplier, Neutral, Regional Actor, Mediator
* Supporter role leads with **152 countries**, Mediator lowest at **133**

### 3. Total Oil Production by Region *(Pie Chart)*
* **5 regions** compared: Middle East (21.27%), Europe (20.48%), North America (19.84%), Asia (19.57%), South America (18.85%)
* Nearly **equal regional distribution** highlighting global energy spread

### 4. Route by Strategic Risk Level *(Donut Chart)*
* **7 strategic chokepoints** monitored:
  * Turkish Straits, Suez Canal, Bab el-Mandeb, Cape of Good Hope
  * Panama Canal, Strait of Hormuz, Malacca Strait
* Risk shares range from **12.8% to 16.47%**

### 5. Total Oil Production by Country *(Treemap)*
* **Top 3 producers:** Saudi Arabia (738M), China (700M), Syria (676M)
* **20+ countries** visualized with production volumes in millions

### 6. Brent Oil Price vs WTI Oil Price by Month *(Line Chart)*
* **12-month** dual-line trend comparison
* Prices tracked in the **$10K–$15K** range across the year
* Clear seasonal patterns and price convergence visible

---

## 🔧 Tools & Technologies

* **Microsoft Excel** — Data sourcing, cleaning & transformation
* **Microsoft Power BI** — Dashboard design, DAX measures & interactive visuals
* **DAX** — Custom KPI calculations
* **Power Query** — Data modelling and shaping

---

## 🎛️ Filters / Slicers

* `Country` — Filter by individual nation
* `Region` — Drill into specific geographic zones
* `Strategic_Risk_Level` — Isolate by risk category

---

## 📁 Project Structure

```
📦 Geopolitical-Energy-Analysis
 ┣ 📄 GeopoliticalEnergyAnalysis.pbix   # Power BI Dashboard file
 ┣ 📊 data.xlsx                          # Source Excel dataset
 ┗ 📝 README.md                          # Project documentation
```

---

## 🚀 How to Run

1. Clone this repository
2. Open `GeopoliticalEnergyAnalysis.pbix` in **Power BI Desktop**
3. Refresh data if needed via *Home → Refresh*
4. Use the top slicers to filter by Country, Region, or Risk Level

---

## 📌 Use Cases

* Geopolitical risk analysis for **energy sector decision-making**
* Strategic planning around **oil supply chain vulnerabilities**
* Academic or policy research on **conflict and energy correlation**

---

*Built with 💡 Power BI | Data visualized across 22 conflict nations and 5 global regions*
