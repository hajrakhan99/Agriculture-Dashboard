# Agriculture-Dashboard
Power BI dashboard analyzing agricultural sales (₹ Lakh), production (Tonnes), and profit across Indian states, seasons, and crop categories — built with interactive slicers and multi-chart visuals.

 🌾 Agriculture Sales and Production Dashboard
 
> An interactive Power BI dashboard providing end-to-end visibility into agricultural sales, production volumes, and profitability — segmented by crop, season, state, and crop type.
 
---
 
## 📌 Short Description (for GitHub repo)
 
> Power BI dashboard analyzing agricultural sales (₹ Lakh), production (Tonnes), and profit across Indian states, seasons, and crop categories — built with interactive slicers and multi-chart visuals.
 
---
 
## 📊 Dashboard Overview
 
This `.pbix` file contains a single-page Power BI report titled **"Agriculture Sales and Production Dashboard"**. It is designed to help stakeholders quickly understand performance across key agricultural dimensions.
 
The dashboard is built on a single data table — `Agriculture_Data` — and uses a dark green gradient theme with agriculture-themed imagery for a professional, domain-specific visual identity.
 
---
 
## 📁 File Structure
 
| File / Component | Description |
|---|---|
| `Agriculture_dashboard.pbix` | Main Power BI report file |
| `Report/Layout` | Report page definitions and visual configurations |
| `DataModel` | Compressed data model (xPress9 compression) |
| `Report/StaticResources/` | Background image, theme file, and icon assets |
 
---
 
## 📈 Visuals Included
 
| Visual Type | Metric Displayed |
|---|---|
| **Bar Chart** | Sales (₹ Lakh) by State and Crop |
| **Line Chart** | Production (Tonnes) by Crop Type |
| **Area Chart** | Profit (₹ Lakh) by Season |
| **Donut Chart** | Production (Tonnes) share by Crop |
| **KPI Card** | Total Profit (₹ Lakh) |
| **KPI Card** | Total Sales (₹ Lakh) |
| **KPI Card** | Total Production (Tonnes) |
| **Slicer** | Filter by Crop |
 
---
 
## 🗃️ Dataset Fields
 
The underlying `Agriculture_Data` table contains the following fields:
 
| Field | Description |
|---|---|
| `State` | Indian state where the crop was produced/sold |
| `Crop` | Specific crop name (e.g., Wheat, Rice, etc.) |
| `Crop_Type` | Category of crop (e.g., Cereal, Vegetable, etc.) |
| `Season` | Agricultural season (e.g., Kharif, Rabi, Zaid) |
| `Sales_INR_Lakh` | Sales value in Indian Rupees (Lakhs) |
| `Production_Tonnes` | Crop production volume in metric tonnes |
| `Profit_INR_Lakh` | Profit value in Indian Rupees (Lakhs) |
 
### Measures
 
| Measure | Description |
|---|---|
| `TOTAL SALES` | Aggregated total sales across all records |
| `TOTAL PRODUCTION` | Aggregated total production volume |
 
---
 
## 🛠️ Tools & Technologies
 
- **Power BI Desktop** — report authoring and data modelling
- **DAX** — custom measures (Total Sales, Total Production)
- **Power Query** — data transformation (implied)
- **Theme** — CY24SU10 base theme with custom dark green gradient styling
 
---
 
## 🚀 How to Use
 
1. Download and open `Agriculture_dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).
2. The data model is embedded — no external data source connection is required.
3. Use the **Crop slicer** to filter all visuals by a specific crop.
4. Hover over charts for detailed tooltips on sales, production, and profit.
 
---
 
## 📋 Requirements
 
- Power BI Desktop (latest version recommended)
- No external database or API connection needed — data is embedded in the file
 
---
 
## 👤 Author
 
**Hajra Khan**  
Created: February 2026 | Last updated: April 2026
