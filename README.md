# 🌊 Environmental Toxin Detection and Analysis in River Ecosystems

> **How clean are our major river systems? Identifying pollution hotspots, seasonal patterns, and contaminant relationships to support environmental monitoring.**

- **Question:** Which river systems show the highest toxin levels? What relationships exist between heavy metals, nutrients, and water quality indicators?
- **Dataset:** 1,305 monitoring records across 6 major river systems (2018–2023)
- **Tools Used:** Python — Pandas · NumPy · Matplotlib · Seaborn · SciPy · StatsModels
- **Top Finding:** Yangtze & Nile show significantly higher heavy metal concentrations; Mercury and Arsenic co-occur strongly (r = 0.70)
- **Impact:** Informs targeted monitoring and pollution mitigation strategies for river management

## 📈 Visual Insights

<!-- ![Toxin Concentrations by River System] (https://github.com/kelvinokojie29/Environmental-Toxin-Detection-and-Analysis-in-River-Ecosystems/blob/main/Assets/Average%20Toxin%20Levels%20by%20River%20System.png)
*Bar chart comparing average Lead, Arsenic, and Mercury levels across river systems* -->

<!-- ![Correlation Heatmap](Assets/correlation-heatmap.png)
*Relationships between toxins, pH, temperature, and dissolved oxygen* -->

<!-- ![Toxin Levels by Season](Assets/seasonal-boxplot.png)
*Box plot showing pollution variation across seasons* --> 

---

## 📊 Dataset Overview

| Field | Description |
|---|---|
| Date | Sampling date (2018–2023) |
| River_System | Major river monitored |
| pH_Level | Acidity/alkalinity measurement |
| Temperature | Water temperature (°C) |
| Lead, Mercury, Arsenic | Heavy metal concentrations |
| Nitrates, Phosphates | Nutrient levels |
| Dissolved_Oxygen | Oxygen availability in water |

> ⚠️ **Data Note:** Dataset used for educational and demonstration purposes. Analysis results should not be used as official environmental assessment data.

---

## 🔑 Key Findings

### 📍 Pollution Hotspots by River
- **Yangtze River** — Highest average Lead (6.91) and Arsenic concentrations
- **Nile River** — Second highest in Lead (6.78); statistically significant difference from Amazon (t = -5.76, p < 0.001)
- **Amazon River** — Relatively lower heavy metal concentrations among systems analysed

### ⏱️ Toxin Levels Overview
- **Arsenic** recorded the highest average concentration (3.60) across all systems
- **Lead** averaged 3.01, while **Mercury** showed the lowest overall levels (0.60)
- Nitrates were the most abundant non-metal contaminant detected

### 🔬 Relationships Between Contaminants
- **Mercury ↔ Arsenic:** Strong positive correlation (r = 0.70) — suggests common pollution sources
- **pH & Lead:** Moderate correlation (r = 0.33); however, pH explains only **3.4%** of variation in pollution levels — other environmental factors are far more influential
- Mercury, Nitrates, Phosphates, and Arsenic showed weak to negligible correlation with pH

### 🌸 Seasonal Patterns
- **Spring** recorded the highest median pollution levels
- **Autumn** showed the lowest median levels
- Outliers present across all seasons — indicating occasional pollution spikes that deviate from typical conditions

---

## 🧠 Analysis Workflow

| Stage | What We Did |
|---|---|
| **Data Preparation** | Loaded CSV; handled missing values; converted dates to datetime format |
| **Exploratory Analysis** | Descriptive statistics; toxin averages; river-by-river comparisons |
| **Visualisation** | Bar charts, time-series trends, correlation heatmaps, seasonal box plots |
| **Statistical Testing** | T-test between Nile & Yangtze; linear regression (pH vs pollution); correlation analysis |
| **Conclusion** | Synthesised findings into actionable insights for river monitoring |

### Statistical Methods Used
- ✅ Independent two-sample t-test
- ✅ Pearson correlation analysis
- ✅ Linear regression modelling
- ✅ Time-series trend analysis

---

## 💡 Recommendations & Implications

| Priority | Action | Rationale |
|---|---|---|
| 🔴 High | Increase monitoring frequency in Yangtze & Nile systems | Consistently elevated heavy metal levels |
| 🟡 Med | Investigate common sources of Mercury & Arsenic | Strong correlation suggests shared origin |
| 🟡 Med | Boost sampling during Spring months | Highest median toxin concentrations observed |
| 🟢 Low | Expand dataset with additional variables (rainfall, proximity to industry) | pH alone explains very little pollution variation |

---

## 📚 Full Documentation

- 📖 **[Detailed Analysis Approach & Methodology](Doc/Analysis_Approach)** — Step-by-step workflow, code logic, and statistical explanations
- 📓 **[Interactive Jupyter Notebook](Notebooks/Environmental Toxin Analysis in River Systems.ipynb)** — Full Python code, visualisations, and outputs

---

## 🛠️ Tools & Libraries
- ✅ pandas    · numpy     → Data manipulation & analysis
- ✅ matplotlib · seaborn  → Data visualisation
- ✅ scipy.stats           → Hypothesis testing
- ✅statsmodels           → Time-series & regression analysis

## 📄 License
MIT License — educational and non-commercial use permitted.

**Author:** Okojie Kelvin Echiejile
**Data Analyst | Python · SQL · Data Visualisation · Statistical Analysis**
📍 Manchester, UK
