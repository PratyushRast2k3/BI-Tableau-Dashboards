# BI-Tableau-Dashboards
Two Tableau BI dashboards — SDG 12 coffee sustainability (Starbucks) &amp; SDG 3/6 water analytics (Unilever) | MSc Business Analytics, University of Glasgow |
# Business Intelligence Dashboards — SDG Analytics (Tableau)

![Tableau](https://img.shields.io/badge/Tableau-Desktop-E97627?style=flat&logo=tableau&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Cleaning-3776AB?style=flat&logo=python&logoColor=white)
![University](https://img.shields.io/badge/University%20of-Glasgow-003865?style=flat)
![Subject](https://img.shields.io/badge/MGT5491-Business%20Intelligence-2E7D32?style=flat)
![SDG](https://img.shields.io/badge/UN%20SDG-3%20%7C%206%20%7C%2012-0099CD?style=flat)

> **MSc Business Analytics · MGT5491 Business Intelligence Practice · University of Glasgow · 2026**

---

## Overview

Two end-to-end business intelligence projects built in **Tableau Desktop**, analysing real-world public datasets through the lens of **UN Sustainable Development Goals (SDGs)**. Both projects follow a complete BI workflow: business problem definition → data sourcing → Python data cleaning → Tableau dashboard design → strategic recommendations for a named multinational company.

---

## Dashboard 1 — Global Coffee Sustainability (SDG 12)

### Business Problem

Starbucks sources coffee from over 30 countries. With global coffee production growing 193% since 1961 and supply concentrated in just a few regions, the company faces mounting sustainability risks — deforestation, yield inefficiency, and supply chain concentration. This dashboard provides a BI framework for Starbucks to align its sourcing strategy with **SDG 12 (Responsible Consumption & Production)**.

### Key Results

- **Identified a 193.36% growth in global coffee production since 1961** — by analysing FAOSTAT agricultural data across 10 top-producing countries — resulting in a quantified baseline for Starbucks to measure its SDG 12 alignment against long-term supply trends.

- **Revealed Vietnam as the most land-efficient producer at 2,800+ hg/ha** — by building a yield efficiency comparison chart across 10 countries — resulting in a data-driven recommendation for Starbucks to prioritise Vietnam-model precision farming investments in low-yield regions (Ethiopia, Uganda, Peru).

- **Diagnosed supply chain concentration risk** — by mapping global production distribution on a choropleth map — resulting in a strategic recommendation to diversify sourcing into emerging African producers to reduce dependency on Brazil and Vietnam.

- **Demonstrated Brazil's SDG-aligned production model** — by analysing a dual-axis production vs. area harvested chart (1961–2023) — resulting in evidence that increased output without land expansion is achievable, directly supporting SDG 12 goals.

### Dashboard Components

| Visual | Type | Insight |
|--------|------|---------|
| % Change in Production | KPI Card | 193.36% growth since 1961 baseline |
| Total Production 2023 | KPI Card | 9,058,586 tonnes globally |
| Average Yield 2023 | KPI Card | 1,102.6 kg/ha — efficiency benchmark |
| Production vs Area Harvested | Dual-axis line chart | Brazil: efficient · Ethiopia: land-expansive |
| Global Coffee Production | Choropleth map | Concentration risk: Brazil dominates |
| Yield Efficiency | Bar chart | Vietnam 2,800+ hg/ha vs global avg |

### Dataset

| Property | Detail |
|----------|--------|
| Source | FAOSTAT — Food and Agriculture Organization of the UN |
| Coverage | 1961–2023 · 10 countries |
| Countries | Brazil, Vietnam, Colombia, Indonesia, Ethiopia, Honduras, Uganda, Peru, India, Guatemala |
| Link | [fao.org/faostat](https://www.fao.org/faostat/) |

### Strategic Recommendations for Starbucks

1. **Invest in low-yield regions** — Fund farmer training, better seedlings, and agronomy support in Ethiopia, Uganda, and Peru to increase yields without expanding land area
2. **Diversify supply chain** — Build partnerships in emerging East African producers to reduce concentration risk in Brazil and Vietnam
3. **Reward SDG-aligned suppliers** — Offer sustainability premiums to suppliers demonstrating Brazil-model efficiency (production up, land stable)

---

## Dashboard 2 — Global Water & Health Analytics (SDG 3 & 6)


### Business Problem

Unilever manufactures water-dependent consumer goods (detergents, personal care, beverages) across markets with vastly different water access levels. Communities with poor water security have lower purchasing power, higher disease burden, and reduced workforce productivity — directly threatening Unilever's long-term market sustainability. This dashboard provides a BI framework for Unilever to align its market strategy with **SDG 3 (Good Health & Well-being)** and **SDG 6 (Clean Water & Sanitation)**.

### Key Results

- **Quantified a 22.6 percentage point gap between basic and safely managed water access** — by building KPI cards from World Bank SDG indicators (2020 baseline) — resulting in evidence that 85.73% of the population has basic water access but only 63.14% has safely managed water, exposing a hidden infrastructure gap.

- **Identified Ethiopia and Kenya as highest-priority intervention markets** — by mapping basic water access on a global choropleth — resulting in a targeted recommendation for Unilever to deploy water-security partnerships and hygiene campaigns in Sub-Saharan Africa first.

- **Demonstrated a strong negative correlation between water access and child mortality** — by plotting a scatter analysis of water access vs. under-5 mortality across 9 countries — resulting in a business case for Unilever that improving water access directly expands its consumer base by reducing disease burden and increasing economic participation.

- **Quantified open defecation as Ethiopia's top sanitation risk at 17%** — by building a comparative bar chart across 9 countries — resulting in a specific recommendation to expand Unilever's Lifebuoy "Help a Child Reach 5" hygiene campaign into high-risk markets.

- **Delivered actionable Unilever product strategy** — by combining all dashboard insights — resulting in three concrete recommendations: water-efficient product lines, community hygiene campaigns, and quarterly BI-driven sustainability evaluation.

### Dashboard Components

| Visual | Type | Insight |
|--------|------|---------|
| Water Access % | KPI Card | 85.73% basic access globally |
| Safely Managed Water % | KPI Card | 63.14% — 22.6pp gap vs basic |
| Under-5 Mortality Rate | KPI Card | 26.53 per 1,000 live births |
| Open Defecation Rate | KPI Card | 6.29% avg — up to 17% in Ethiopia |
| Safely Managed Water Trend | Line chart | UK/USA >95% vs Ethiopia <15% |
| Global Water Access | Choropleth map | Sub-Saharan Africa: critical gap |
| Under-5 Mortality Trend | Stacked area chart | All countries declining 2006–2020 |
| Water Access vs Mortality | Scatter plot | Strong negative correlation |
| Open Defecation Comparison | Bar chart | Ethiopia 17% vs UK/USA ~0% |

### Dataset

| Property | Detail |
|----------|--------|
| Source | World Bank SDG DataBank |
| Coverage | 2006–2020 · 9 countries |
| Countries | Bangladesh, Ethiopia, India, Indonesia, Kenya, Philippines, UK, USA |
| Indicators | Basic water access · Safely managed water · Under-5 mortality · Open defecation |
| Link | [databank.worldbank.org](https://databank.worldbank.org/source/sustainable-development-goals-(sdgs)) |

### Strategic Recommendations for Unilever

1. **Target Sub-Saharan Africa first** — Ethiopia, Kenya, and Bangladesh have the largest gaps between basic and safely managed water — highest commercial and humanitarian opportunity
2. **Develop water-efficient product lines** — Low-rinse detergents, waterless personal care, affordable water-purification solutions for markets with unreliable supply
3. **Scale Lifebuoy campaigns** — Expand "Help a Child Reach 5" model into high open-defecation markets — directly supports SDG 3 and builds brand equity
4. **Embed BI in sustainability reporting** — Integrate quarterly SDG dashboard evaluation into Unilever's sustainability review cycle

---

## Data Preparation (Python)

Both projects used **Python / Jupyter Notebook** for data cleaning before import into Tableau:

```python
import pandas as pd
import numpy as np

# Load raw dataset
df = pd.read_csv('raw_data.csv')

# Remove missing values — nulls misinterpreted as zero in Tableau
df.dropna(inplace=True)

# Type conversion for correct Tableau rendering
df['year'] = df['year'].astype(int)
df['value'] = df['value'].astype(float)

# Standardise country names for geographic mapping
df['country'] = df['country'].str.strip().str.title()

# Remove infinite values from ratio calculations
df.replace([np.inf, -np.inf], np.nan, inplace=True)
df.dropna(inplace=True)

# Export cleaned dataset
df.to_csv('cleaned_data.csv', index=False)
```

**Cleaning steps applied:**
- Missing value identification and removal
- Numeric type conversion (float, integer standardisation)
- String whitespace and capitalisation standardisation
- Infinite value handling from ratio/percentage calculations
- Country name standardisation for Tableau geographic recognition

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard design, KPI cards, charts, maps |
| Tableau Public | Live dashboard hosting and sharing |
| Python 3.12 | Data cleaning and preparation |
| pandas | Data manipulation, type conversion |
| Jupyter Notebook | Development environment |
| FAOSTAT | Agricultural production dataset |
| World Bank DataBank | SDG health and water indicators |

---

## Ethical Considerations

Both analyses follow responsible BI practice:

- **Correlation ≠ causation** — all findings are presented as associations, not causal claims
- **Data transparency** — missing values were removed and documented, not imputed
- **Country-level comparisons** — individual country judgements avoided; systemic factors acknowledged
- **FAOSTAT limitations** — social and environmental factors not captured in production data are noted explicitly
- **Unbiased framing** — recommendations are commercial AND humanitarian, not one-sided

---

## Academic References

- FAOSTAT (2024). Crops and Livestock Production Database. [fao.org/faostat](https://www.fao.org/faostat/)
- World Bank (2024). Sustainable Development Goals DataBank. [databank.worldbank.org](https://databank.worldbank.org)
- United Nations (2023). Sustainable Development Goals. [sdgs.un.org](https://sdgs.un.org/goals)
- Starbucks (2024). Global Environmental and Social Impact Report. [starbucks.com/responsibility](https://www.starbucks.com/responsibility)
- Unilever (2024). Sustainability Strategy and Progress Reports. [unilever.co.uk/sustainability](https://www.unilever.co.uk/sustainability/)

---

## About

This project is part of my MSc Business Analytics portfolio at the University of Glasgow (2025–26).

**Pratyush Rastogi** · [LinkedIn](https://www.linkedin.com/in/pratyush-rastogi-483b021bb/) · [GitHub](https://github.com/PratyushRast2k3)
