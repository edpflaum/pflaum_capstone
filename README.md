## Renewable Energy Generation and Carbon Emissions in the U.S.
Objective: Final YSE EDS Capstone focusing on the relationship between renewable energy growth and carbon emissions decline in the US over the course of the 21st century. 
Yale School of the Environment - Environmental Data Science Certificate Program
Student: Elizabeth Pflaum | Submitted: April 2026
## 50-Word Summary
This project uniquely identifies and captures the relationship between renewable energy generation across the United States and overall carbon emissions from the past quarter-century. Using data from the EIA, the US Energy Information Administration, I collected monthly electricity generation and inventory from the EPA on US Greenhouse Gas Emissions and Sinks.
## Data Collection
- ** Period: 2000 - 2025**
- ** Sites: United States**
- ** Frequency: Monthly**
- ** Instruments: State, local, and federal electricity generation sites; carbon emissions trackers nationally
## File Organization
- ** analysis/ - R scripts in Jupyter notebook
- ** data/ - metadata and data documentation
- ** rawdata/ - original files and discovered data
- ** processeddata/ - cleaned intermediary files and analysis results
- ** outputs/ - figures and any reports 
- ** archive/ - legacy data and previously examined data
## Repository Structure
us-renewable-energy-emissions/
│
├── README.md                              ← Project overview, methodology, key findings
│
├── data/
│   ├── raw/
│   │   └── EDS_Monthly_energy_generation.xlsx   ← Original dataset (unaltered)
│   └── README_data.md                      ← Variable definitions + data source
│
├── scripts/
│   └── analysis.R                          ← Main R script (data cleaning + 3 figures)
│
├── outputs/
│   ├── fig1_renewable_growth.png           ← Renewable generation over time
│   ├── fig2_fossil_trend.png               ← Fossil generation (emissions proxy)
│   └── fig3_relationship.png               ← Renewable share vs fossil generation
│   └── key_findings.md                     ← Concise interpretation of results
│
└── LICENSE.md
## Requirements
- ** R, Python
- ** Packages: pandas, tidyverse, dplyr, ggplot2, tidyr, readxl, matplotlib.pyplot
## Conclusion
The expansion of renewable energy in the past quarter-century has contributed to reducing carbon emissions in the United States. CO2 emissions from electricity peaked in the mid-2000s and has since declined. 
  Key Insights: Renewable Expansion, Fossil Fuel Usage Decline, Inverse Relationship between Renewable Energy and Fossil Fuel Emission Generation
## Contact
- Elizabeth Pflaum - edpflaum@gmail.com
## License
- Please cite and give credit to the EIA, Energy Information Administration, when using this data.
