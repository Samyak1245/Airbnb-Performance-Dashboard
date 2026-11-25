# Airbnb Performance Dashboard

An interactive dashboard that tracks how a portfolio of 71 Airbnb properties performs across **Paris, Tokyo and New York** (Sep 2024 – Aug 2026).

## 🔗 Live Demo

**[Open the dashboard](https://samyak1245.github.io/Airbnb-Performance-Dashboard/)**

// https://samyak1245.github.io/Airbnb-Performance-Dashboard/

## What it shows

- **KPI cards:** Revenue, ADR, Occupancy, RevPAR, Bookings, Cancellation rate, Host payout and Avg rating, each compared with the previous period
- **Trends:** monthly revenue by city and occupancy
- **Benchmarks:** ADR and occupancy against the market
- **Breakdowns:** revenue by city and property type, booking outcomes, channels, guest segments and guest ratings
- **Top 10 listings** table that you can re-rank by any column
- **Auto-generated insights** that update with your filters

## How to use it

1. Pick a **city** (or all three) at the top.
2. Choose a **date range** with the From / To month selectors.
3. Switch between **light and dark** mode with the ◐ button.

## Built with

- HTML, CSS and JavaScript (a single `index.html` file)
- [Chart.js](https://www.chartjs.org/) for charts
- Data prepared from an Excel workbook using Python (pandas)

## Notes

- The dataset is synthetic
- Occupancy = booked nights ÷ (booked + available nights). All values are in USD.
