# Philippine Wholesale Electricity Market Analytics

## Overview
This project analyzes electricity market data in the Philippines to understand how electricity prices behave over time. Using publicly available datasets from the Independent Electricity Market Operator of the Philippines (IEMOP), the study examines the relationship between generation levels, regional market conditions, and electricity prices in the Wholesale Electricity Spot Market (WESM).

The project aims to answer the following research question:

***How do generation levels and regional market conditions relate to electricity prices in the Philippine Wholesale Electricity Spot Market (WESM)?***

---

## Data Sources
This project utilizes publicly available Philippine WESM datasets published by the IEMOP.

The primary datasets include:

### 1. RTD Market Clearing Price
**Key fields:**
- Run Time
- Trading Interval
- Region Name
- Resource Name
- Commodity Type
- Marginal Price

**Purpose:**
- Analyze market clearing prices across regions, resources, and commodity types.
- Identify periods of price volatility and extreme market conditions.

---

### 2. RTD Prices and Schedules
**Key fields:**
- Run Time
- Trading Interval
- Region Name
- Resource Name
- Resource Type
- Scheduled Generation (MW)
- Locational Marginal Price (LMP)
- Loss Factor
- Congestion Component

**Purpose:**
- Examine the relationship between scheduled generation and electricity prices.
- Assess the impact of transmission losses and congestion on market prices.

---

### 3. RTD Regional Summaries
**Key fields:**
- Run Time
- Trading Interval
- Region Name
- Market Requirement (MW)
- Load Bid (MW)
- Generation (MW)
- Market Imports (MW)
- Market Exports (MW)
- Losses (MW)

**Purpose:**
- Evaluate regional supply and demand conditions.
- Analyze energy flows, imports, exports, and system losses.

---

### 4. Registered Capacity – Generation
**Key fields:**
- Trading Day
- Trading Period
- Resource Name
- Maximum Capacity (MW)

**Purpose:**
- Measure available generation capacity.
- Compare installed capacity against scheduled generation and market conditions.

---

**Dataset Source:**

All datasets are sourced from the IEMOP WESM Market Data Portal: https://www.iemop.ph/the-market/market-data/

---

## Data Limitations

- Historical data availability depends on records published by IEMOP.
- Market prices are influenced by external factors not directly captured in the datasets, such as fuel costs, weather conditions, regulatory interventions, and operational decisions.
- This study focuses on Real-Time Dispatch (RTD) market data and does not represent the full scope of electricity market operations in the Philippines.

---

## Objectives

The project aims to:

- Analyze how generation levels relate to electricity prices in WESM.
- Examine the relationship between regional market conditions and electricity prices.
- Track electricity prices as the primary market outcome variable.
- Provide insights for energy analysts, researchers, and data professionals on market behavior and pricing dynamics.

---

## Expected Dashboard Outputs

Potential analyses include:

### Price Trends
- Market Clearing Price trends by region and time period.
- Identification of peak and off-peak pricing patterns.

### Supply and Demand Analysis
- Relationship between generation and regional demand.
- Detection of supply shortages and excess generation periods.

### Regional Market Comparison
- Comparison of electricity prices across Luzon, Visayas, and Mindanao.
- Regional demand and generation profiles.

### Generation Resource Analysis
- Contribution of different resource types to supply.
- Capacity utilization by region.

### Price Drivers Exploration
- Relationship between generation, demand conditions, and prices.
- Identification of conditions associated with price spikes.

### Market Overview
- Summary KPIs for demand, generation, and prices.
- Interactive filtering by date, region, and interval.




