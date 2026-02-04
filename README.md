# Energy & Sustainability Analysis

This project analyses long-term trends in renewable energy usage and CO₂ emissions
using World Bank Open Data, with a focus on Germany between 1990 and 2020.

The goal is to explore how the expansion of renewable energy relates to changes
in per-capita CO₂ emissions, using transparent and reproducible data analysis
methods.

---

## Research Questions
- How has renewable energy consumption evolved in Germany over time?
- How have per-capita CO₂ emissions changed over the same period?
- What descriptive relationship can be observed between these two trends?

---

## Data Sources
All data is sourced from the World Bank Open Data platform.

### Renewable Energy Consumption
- **Indicator:** Renewable energy consumption (% of total final energy consumption)  
- **World Bank code:** `EG.FEC.RNEW.ZS`

This indicator measures the share of energy from renewable sources (such as wind,
solar, hydro, and biomass) in a country’s total final energy consumption. It is
commonly used to track progress in energy transition and sustainability policies.

Values are expressed as a percentage of total final energy use.

---

### CO₂ Emissions per Capita
- **Indicator:** CO₂ emissions per capita (excluding LULUCF)  
- **World Bank code:** `EN.GHG.CO2.PC.CE.AR5`

This indicator measures annual CO₂ emissions from fossil fuel combustion and
industrial processes, divided by population. Emissions related to land-use
change and forestry are excluded to focus on emissions directly linked to energy
use and industrial activity.

Values are reported in metric tonnes of CO₂ per person per year.

---

### Scope
- **Country:** Germany  
- **Time period:** 1990–2020  

The analysis focuses on this period due to consistent data availability and to
avoid incomplete observations in the most recent years.

---

## Methodology
The analysis follows a structured workflow:

1. Data loading and inspection  
2. Missing data checks and cleaning  
3. Filtering to Germany  
4. Reshaping data from wide to long format  
5. Merging renewable energy and CO₂ datasets at the year level  
6. Exploratory time-series visualisation  
7. Descriptive correlation analysis  

---

## Key Findings
- Renewable energy share in Germany increases steadily over the period, with
  accelerated growth after the mid-2000s.
- CO₂ emissions per capita show a long-term declining trend, with periods of
  stagnation.
- A strong negative correlation is observed between renewable energy share and
  CO₂ emissions per capita, indicating an inverse relationship over time.
- This relationship is descriptive and does not establish causality.

---

## Limitations
- The analysis focuses on a single country and cannot be generalised.
- Correlation does not imply causation.
- Other factors such as energy efficiency, economic structure, and policy
  instruments are not explicitly modelled.
