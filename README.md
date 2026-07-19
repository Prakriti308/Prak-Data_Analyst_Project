<div align="center">
  <h1>🏨 Revenue Insights in the Hospitality Domain</h1>
  <p><b>An End-to-End Data Analytics Dashboard for Atliq Grands</b></p>
</div>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Power%20Query-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power Query" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="DAX" />
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/CSV_Data-000000?style=for-the-badge&logo=pandas&logoColor=white" alt="CSV" />
</div>

<br>

## 📊 Project Overview

**Atliq Grands**, a prominent player in the hospitality industry, has been experiencing a decline in market share and revenue in the luxury/business hotel category due to strategic moves by competitors and ineffective management decisions. 

To turn things around, the managing director has decided to incorporate "Business and Data Intelligence" to help regain their market share and revenue. This project delivers a comprehensive, interactive **Power BI Dashboard** that provides actionable insights to Atliq Grands' executive management team.

## 🛠️ Tech Stack & Skills Used

- **Data Integration & Transformation:** Power Query
- **Data Modeling:** Star Schema (Dimension & Fact Tables)
- **Calculations & Metrics:** DAX (Data Analysis Expressions)
- **Visualization & Reporting:** Power BI Desktop
- **Project Documentation:** Excel, CSV, PDF 

## 📂 Data Model (Star Schema)

The dataset consists of 5 main tables modeled into a Star Schema for optimized reporting:

### Dimension Tables:
- `dim_date`: Date hierarchy, week numbers, and weekday/weekend classification.
- `dim_hotels`: Details of properties including unique IDs, names, category (Luxury/Business), and city.
- `dim_rooms`: Room classifications (Standard, Elite, Premium, Presidential).

### Fact Tables:
- `fact_aggregated_bookings`: Aggregated daily data including successful bookings and total room capacity per hotel.
- `fact_bookings`: Granular data showing individual booking IDs, check-in/out dates, guest counts, booking platforms, status (Checked Out, Cancelled, No Show), ratings, and generated vs. realized revenue.

## 📈 Key Metrics & Development Stages

The development of this dashboard was structured across multiple stages:

1. **Stage 1 - Power Query** (`stage1_power_query.pbix`): Extracting, cleaning, and transforming raw CSV data into an optimized structure.
2. **Stage 2 - DAX Measures** (`stage2_dax_measures.pbix`): Creating calculated columns and robust DAX measures to calculate critical hospitality KPIs:
   - **RevPAR** (Revenue Per Available Room)
   - **ADR** (Average Daily Rate)
   - **Occupancy %**
   - **Realization %**
   - **Cancellation Rate**
3. **Stage 3 - Visual Creation** (`stage3_visual_creation_demo.pbix`): Designing an interactive, visually appealing executive dashboard based on the provided mock-ups (`mock_up_dashboard_atliq_grands.png`).

## 🚀 How to Use

1. Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed on your machine.
2. Download or clone this repository to your local computer.
3. Open the main file: **`Revenue-Insights-in-the-Hospitality-Domain.pbix`**.
4. Explore the final, fully functional dashboard by interacting with the filters (such as City, Room Class, Month, and Week) to discover dynamic business insights.
