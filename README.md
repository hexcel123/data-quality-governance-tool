🌍 CO₂ Emissions & Net Zero Scenario Tracker
Tools: Python | R | Power BI | REST APIs | Pandas | ggplot2  
Domain: Sustainability Analytics | Energy Policy | Data Strategy  
Portfolio: github.com/hexcel123
---
Project Overview
An open-source analytics platform extending academic research on Bristol’s net-zero 2030 target into a fully deployable, live-data emissions tracker. Integrates real-time data from the UK Government emissions API and transport datasets, with Power BI scenario modelling allowing users to simulate the impact of policy interventions on 2030 targets.
---
Business Problem
National and local governments — and major energy companies like BP — need reliable, data-driven tools to track progress against net-zero commitments and model the impact of policy changes before implementation.
---
What I Built
Live Data Integration: Python scripts pulling from DESNZ emissions API, DfT transport statistics API, and ONS population data; refreshed nightly via scheduled jobs
Data Transformation: R scripts for sector-level emissions decomposition, per-capita normalisation, and year-on-year trend analysis
Scenario Modelling: Power BI what-if parameters enabling users to adjust EV adoption rates, public transport usage, and industrial output to project emissions trajectories
Governance: Full data lineage documentation and version control of all source datasets
---
Key Results
Metric	Value
Emission Reduction Pathway Identified	18% by 2030
Data Sources Integrated	5 live APIs
Scenarios Modelled	12 policy combinations
Dashboard Refresh Frequency	Daily
---
Skills Demonstrated
✅ Live API data integration and ETL  
✅ Python and R for statistical analysis  
✅ Power BI what-if scenario modelling  
✅ Data governance and lineage documentation  
✅ Sustainability and energy policy domain knowledge
---
Repository Structure
```
co2-net-zero-tracker/
├── ingestion/          # API connectors and scheduling
├── transformation/     # R and Python processing scripts
├── dashboard/          # Power BI .pbix with scenario parameters
├── docs/               # Data lineage and governance docs
├── notebooks/          # Academic analysis notebooks
└── README.md
```
---
Project by Hezekiah Akinkuade | hakinkuade@gmail.com
