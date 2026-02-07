# UK Grid Command ⚡🌍  
**National Grid Carbon Intelligence Dashboard**

https://ukci.selpha.com/

UK Grid Command is a real-time, data-driven dashboard for understanding the **carbon intensity of Great Britain’s electricity grid**—how “clean” or “dirty” the power is right now, how it has changed over the last 24 hours, and where it’s heading next.

It brings together **live grid carbon intensity (gCO₂/kWh)**, **generation mix breakdowns**, **regional rankings**, and **short-term forecasts** in a single, easy-to-scan interface.

---

<img width="2048" height="1247" alt="image" src="https://github.com/user-attachments/assets/285b2d49-ac61-4833-ab68-26071b721654" />

<img width="2048" height="1247" alt="image" src="https://github.com/user-attachments/assets/40191c0e-9b9c-4ccf-928f-60bcb5453aff" />

<img width="2048" height="1228" alt="image" src="https://github.com/user-attachments/assets/f8b85ad2-2404-4776-9241-6b69eea45c23" />

<img width="2048" height="1220" alt="image" src="https://github.com/user-attachments/assets/40eef619-6c02-4bc8-bad6-795f9562c522" />

<img width="2048" height="1221" alt="image" src="https://github.com/user-attachments/assets/9c06539c-f634-42e5-a369-5e7b651aade9" />

<img width="2048" height="1229" alt="image" src="https://github.com/user-attachments/assets/c961b893-1fd3-4c79-aefe-b6679910d199" />

---

## What you can do

### ✅ Live carbon intensity (Overview)
- See the **current grid carbon intensity** in **gCO₂/kWh** with an at-a-glance status label (e.g., *Moderate*).
- Track key splits:
  - **Renewable share**
  - **Low-carbon share** (renewables + nuclear)
  - **Fossil fuel share**
- Review **last 24h carbon intensity** with **Actual vs Forecast** trends.
- Identify:
  - **Cleanest regions**
  - **Highest-intensity regions**

### ⚙️ Generation Mix (Generation Mix tab)
Understand *why* the grid looks the way it does:
- **Live generation mix breakdown** by source (e.g., wind, gas, nuclear, biomass, imports, etc.)
- Multiple views for fast interpretation:
  - Horizontal bar breakdown
  - Donut by category (Renewable / Nuclear / Fossil / Imports & Other)
  - Radar snapshot
  - Source detail cards with percentages

### 🗺️ Regional view (Regional tab)
Compare carbon intensity across Great Britain:
- Bar chart of **regional carbon intensity**
- Ranked list of all regions
- **Top regions’ generation mix** (so you can see what’s driving the ranking)

### 🔮 Forecasting (Forecast tab)
Plan around cleaner electricity:
- **Next 24h carbon intensity forecast** curve
- A **timeline** of forecasted intensity values
- **Intensity distribution** (how many periods are Very Low / Low / Moderate / High / Very High)
- A highlighted **optimal usage window** concept for shifting flexible demand (when available)

### 🧠 Methodology (Methodology tab)
A transparent explanation of how the forecast is produced, including:
- **Machine learning ensemble** (multiple models blended into a single forecast)
- **Power flow modeling** (approximating how electricity moves through the GB grid, including constraints/losses and imports)
- **Nowcasting / live updates** (regular refreshes using the latest real-time grid measurements)

It also explains why this matters for:
- **Carbon pricing exposure**
- **ESG / Scope 2 reporting**
- **Energy trading & operational decision-making**

---

## How to read “carbon intensity”
**Carbon intensity** is measured in **grams of CO₂ per kilowatt-hour (gCO₂/kWh)**.  
Lower values generally mean the grid is running on a higher share of **wind/solar/nuclear**, while higher values often reflect more **gas/coal** and/or lower renewable output.

The dashboard groups intensity into an index-style scale:
- **Very Low**
- **Low**
- **Moderate**
- **High**
- **Very High**

(Exact thresholds are shown in the Methodology section of the site.)

---

## Data source & refresh
This dashboard is powered by live grid datasets from **UK National Grid ESO / NESO** carbon intensity services (as referenced in the UI).  
The interface is designed to **auto-refresh regularly** so the display stays close to real time.

---

## Who it’s for
- **Households & EV owners**: shift charging or heavy appliance use to cleaner windows  
- **Sustainability teams**: better understand day-to-day electricity emissions signals  
- **Engineers & operators**: monitor regional intensity and generation drivers  
- **Analysts & traders**: track conditions that influence price, fuel mix, and emissions  

---

## Disclaimer
This project provides **informational** estimates and short-term forecasts. It should not be treated as a certified emissions ledger. For compliance-grade reporting, rely on your organization’s approved methodologies and data sources.

---

## Screens / Navigation
- **Overview** → live intensity + last 24h trend + regional best/worst  
- **Generation Mix** → what’s producing electricity right now  
- **Regional** → which parts of GB are cleanest/dirtiest and why  
- **Forecast** → near-term outlook and potential greener windows  
- **Methodology** → how the forecast works + why it matters  

---
