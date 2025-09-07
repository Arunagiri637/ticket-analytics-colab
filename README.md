# Ticket Analytics (Colab + DuckDB)

This project analyzes IT ticket data using **Google Colab**, **DuckDB**, and **Plotly**.  
It cleans, transforms, and visualizes ticket resolution performance.

## Features
- Upload Excel/CSV ticket data
- Build staging table (`stg_tickets`) with cleaned data
- Create marts:
  - Average resolution time by category & priority
  - Closure rate by assigned group
  - Monthly ticket summary
- Dashboard:
  - 📌 KPI cards (Total Tickets, Avg Resolution Time, Closure Rate %)
  - 📈 Trends over time
  - 🔥 Heatmap of delays
  - 📊 Closure rate ranking
  - 📦 Resolution time distribution

## How to Run
1. Open the notebook in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/ticket-analytics-colab/blob/main/ticket_analysis.ipynb)
2. Upload your Excel file with ticket data.
3. Run all cells step by step.
4. View KPIs and charts in the dashboard.

## Requirements
- Google Colab (no setup needed)
- Libraries (already in notebook): `duckdb`, `pandas`, `openpyxl`, `plotly`

## License
MIT

