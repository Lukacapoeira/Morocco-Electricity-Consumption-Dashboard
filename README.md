# Morocco-Electricity-Consumption-Dashboard
## 📌 Project Overview An interactive Power BI dashboard designed to analyze the impact of environmental factors (temperature, humidity, natural light) on electricity consumption across three distinct power zones in Tetouan, Morocco.
## 🛠️ Tech Stack & Techniques
* **Tool:** Power BI
* **Data Prep (ETL):** Power Query (Splitting date/time, data type formatting)
* **Data Modeling:** Built a Star Schema with a dedicated Calendar table and disconnected parameter tables for UI/UX optimization.
* **Advanced DAX:** Created custom measures to handle complex filtering scenarios. For example, used a combination of `SUMX`, `VALUES`, and `SWITCH` to allow dynamic multi-selection of zones via custom slicers without breaking the visual totals.
* **UI/UX:** Dark mode design, custom tooltips for deeper hourly/environmental insights, and custom-built navigation buttons.

## 📊 Key Features
* **Time Series Analysis:** Tracks energy peaks across months and specific hours.
* **Environmental Correlation:** Compares power consumption against Average Temperature and Diffuse Flows (Natural Light).
* **Dynamic Zone Filtering:** Users can filter data by selecting single or multiple zones simultaneously.
## 🚀 How to Use / Run Locally
1. Download the `Morocco_Energy_Dashboard.pbix` file from this repository.
2. Open the file using **Power BI Desktop**.
3. Interact with the slicers at the top (Zone 1, Zone 2, Zone 3) to filter the dataset.
4. Hover over the charts to see custom tooltips with additional weather data.
