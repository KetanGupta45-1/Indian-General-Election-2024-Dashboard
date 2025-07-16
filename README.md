# 🗳️ Indian General Elections 2024 - Power BI Dashboard

A comprehensive Power BI project that visualizes and analyzes the results of the 2024 Indian General Elections at the **national, state**, and **constituency levels**. The dashboard is designed to provide clear insights into **party-wise**, **alliance-wise**, and **region-wise** performances.

---

## 📌 Overview

This interactive dashboard is structured into multiple pages and enables users to explore:

- 🏛️ **National Overview**: Seat share of alliances like NDA, INDIA, and Others.
- 🗺️ **State-wise Summary**: Which alliance/party dominated in each state.
- 🧭 **Constituency-Level Details**: Vote share, winner/runner-up stats, and margins.
- 📋 **Detailed Grid View**: Tabular result summary across all constituencies.

> 📅 Voting Period: 19th April – 1st June 2024  
> 🗓️ Result Declared: 4th June 2024  
> 📊 Total Seats: 543  

---

## 📊 Dashboard Highlights

### 1. **National Overview**
- 🚩 **NDA Alliance**: 292 seats (53.78%)
- 🟦 **INDIA Alliance**: 234 seats (43.09%)
- 👥 **Others/Independent**: 17 seats (3.13%)

Includes visuals:
- Party logos and seat contribution within alliances
- Portrait visuals of key figures (PM candidates)
- Total number of parties per alliance

---

### 2. **State-wise Demographics**
- Interactive map showing:
  - Total seats per state
  - Majority alliance per state
  - Hover functionality to show state-level breakdown

Maps include:
- 🎯 Winning party/alliance by state
- 🧭 Constituency markers by winning alliance

---

### 3. **Political Landscape: State-Level**
- Choose any state from dropdown
- Detailed seat distribution across:
  - INDIA
  - NDA
  - Others
- Pie chart for vote share among parties
- Table showing party-wise results

📍 Example (Maharashtra):
- INDIA: 30 seats
- NDA: 17 seats
- Others: 1 seat

---

### 4. **Constituency-Based Analysis**
- Select any constituency from a dropdown
- Displays:
  - 🏆 Winner, Runner-Up, and 2nd Runner-Up
  - Vote count, % vote share
  - Win margin
- Info on:
  - Total participants
  - Postal votes
  - EVM votes

📍 Example (Adilabad):
- Winner: BJP (Godam Nagesh)  
- Vote Share: 45.98%  
- Margin: 90,652

---

### 5. **Details Grid View**
- Table showing:
  - Constituency
  - Winning candidate, party, and alliance
  - Total votes & margin
  - Runner-up candidate

This tab offers a printable and searchable format for reference.

---

## 🗂️ Datasets Used

| File                  | Description |
|-----------------------|-------------|
| `partywise_results.csv` | Seat count and alliances per party |
| `states.csv`            | State metadata for mapping |
| Power BI Data Model    | Includes `constituencywise_results`, `statewise_results`, etc.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** (for measures, filters, and interactivity)
- **CSV Files** for structured data import
- **Custom Visualizations** (Map, Donut Charts, KPI Cards)

---

## 🌟 Key Insights

- NDA secured a majority with 292 seats
- INDIA alliance performed strongly in Maharashtra, Tamil Nadu, and Kerala
- Constituency-level margins reveal highly competitive regions
- Visual maps help identify political strongholds and shifts

---

## 🔍 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use filters (state, constituency) to explore granular details
3. Hover over maps and charts for tooltips and comparisons

---

## 📸 Screenshots
<img width="1852" height="737" alt="Screenshot 2025-07-16 085605" src="https://github.com/user-attachments/assets/74233880-b745-4534-9e2c-703be63bbd15" />
<img width="1414" height="737" alt="Screenshot 2025-07-16 085616" src="https://github.com/user-attachments/assets/ab5248a0-c50c-4507-9d09-2cc4d8fdb2e4" />
<img width="1421" height="733" alt="Screenshot 2025-07-16 085625" src="https://github.com/user-attachments/assets/de2ad7d5-b6e2-46e0-aa8e-5628f4d8a4ae" />
<img width="1435" height="738" alt="Screenshot 2025-07-16 085634" src="https://github.com/user-attachments/assets/4cfee77c-8c1d-488a-933e-beb6daef79d7" />
<img width="1435" height="740" alt="Screenshot 2025-07-16 085641" src="https://github.com/user-attachments/assets/3deffca3-a02d-4d14-b5d4-106a1939d2b0" />
