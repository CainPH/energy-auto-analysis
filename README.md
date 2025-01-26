# energy-auto-analysis
energy-automation-analysis/
  ├── data/                # Raw data files
  ├── notebooks/          # Jupyter analysis
  ├── src/               # Python scripts
  ├── requirements.txt   # Dependencies
  └── README.md         # Documentation
    So yeah, I reckon this will be a model of the load profiles of hyperscale vs colocation and their impact on the local grids, peak timing, locations relative to substations etc, then using that analysis of the US environment to draw insights in Australia and Southeast Asia. I think looking first at modelling load profiles, then
    The raw data sources I plan to use are AEMO grid data, public dc locations, energy consumption reports with a focus on northern virginia, given I assume there's a wealth of data that comes out of there. Step by step is likely to be 
    Project Setup
Create GitHub repo
Set up data folders
Write initial research question

  Data Collection
US EIA power data
Data center locations
Power consumption stats

  Analysis Steps
Load profile comparison
Geographic distribution
Grid stability metrics
Cost implications

  Outputs
Technical analysis (code)
Policy brief (2-3 pages)
Interactive visualizations
Recommendations

  RQ: How the nature of high density AI/ML data centre being either colocation/hyperscale change their impact on the grid?
  Hypothesis: Colocation workloads will result in greater grid degradation due to unpredictable training workloads, unplanned peaks. Other outcomes I'm unsure, need to determine the metrics.

  Grid Impact Metrics:
Peak load timing/magnitude
Ramp rates (MW/minute)
Power quality variations
Grid frequency stability

  DC Classification:
Hyperscale: Google, Meta, Microsoft
Colocation: Digital Realty, Equinix

  Data needed:
Load profiles (15-min intervals)
Power density (kW/rack)
Utility infrastructure upgrades
Grid stability events
