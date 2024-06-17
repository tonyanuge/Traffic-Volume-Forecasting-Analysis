
Traffic Volume Forecasting Analysis

 Overview
This repository contains a project focused on analyzing and forecasting traffic volume. The analysis uses historical traffic data to understand patterns and predict future traffic volumes at selected sites in Dublin. 

 Repository Structure
- notebooks/: Jupyter notebooks for data analysis and forecasting.
- data/: Contains the datasets used for the analysis.
- models/: Saved models and scripts for forecasting traffic volume.
- README.md: Project overview and instructions.

 Data
The primary dataset used in this project is THA21.csv, which includes the following columns:
- Statistic Label: Description of the traffic statistic being measured.
- Year: The year of the recorded statistic.
- Transport Traffic Site: The specific traffic site where data was collected.
- Weeks of the year: The week of the year for the recorded data.
- UNIT: The unit of measurement (e.g., number).
- VALUE: The recorded value of the statistic.

 Data Source
The data was sourced from
1. Transport Infrastructure Ireland. Available at: https://data.tii.ie/index.html
2. OECD. (n.d.). Stats. https://stats.oecd.org/
3. Central Statistics Office. (2023). THA21.20231203T191256, ROA19.20231213T191237 [Dataset]. https://data.cso.ie/.
4. Government of Ireland. (2023). MTM01.20231213195548. Available at: https://data.gov.ie/dataset/mtm01-rainfall.
5. OECD. (2023). DP_LIVE_03122023232021488. https://data.oecd.org/transport/freight-transport.htm.
6. Transport for Ireland. (2023). NaPTAN. https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fwww.transportforireland.ie%2FtransitData%2FData%2FNaPTAN.xlsx&wdOrigin=BROWSELINK.
7. Department for Transport, UK. (n.d.). Edinburgh Traffic. https://roadtraffic.dft.gov.uk/local-authorities/29.
8. Department for Transport, UK. (n.d.). Leeds Traffic. https://roadtraffic.dft.gov.uk/local-authorities/63.



 Usage
 Jupyter Notebooks
The primary analysis and forecasting are performed in Jupyter notebooks. You can start Jupyter Notebook by running:

bash
jupyter notebook


Open the notebook CA2_TrafficVolumeForecast_Analysis.ipynb to explore the data analysis and forecasting steps.

 Scripts
For running the scripts directly, use:

bash
python scripts/traffic_forecasting.py


 Analysis and Forecasting
 Data Exploration
The initial steps involve loading the dataset and exploring its structure. Key steps include:
- Understanding the distribution of traffic volume across different sites and weeks.
- Visualizing historical trends.
- Identifying patterns and anomalies.

 Forecasting Models
The project employs various forecasting models to predict traffic volume:
- Time Series Analysis
- ARIMA Models
- Machine Learning Models

 Results
The results of the analysis and forecasting are documented in the notebooks. Key findings include:
- Trends in weekly traffic volume.
- Predicted traffic volume for future weeks.



  Contact
For any questions or issues, please open an issue in the repository or contact Tony Anuge at osianuge@yahoo.com.

