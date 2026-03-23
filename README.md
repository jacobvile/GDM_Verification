**Analysis of the Google DeepMind (GDM) Tropical Cyclone Intensity Forecasts for the 2025 Atlantic Hurricane Season**

Vile et al.

**Description of Data Files**

**1)	GDM_data_2025.csv**

Google DeepMind ensemble model output for 2025 Atlantic tropical cyclones (TCs). See manuscript for processing and filtering steps.

Variables:

•	init_time: Model initialization date and time (UTC)

•	track_id: TC ID (Automated Tropical Cyclone Forecasting System format)

•	sample: Ensemble member number (0–49)

•	valid_time: Model forecast valid date and time 

•	lead_time_hours: Forecast time (hours)

•	lat: TC latitude

•	lon: TC longitude

•	maximum_sustained_wind_speed_knots: TC intensity (knots)


**2)	The SHIPS_RI_Probabilities.csv**

Statistical Hurricane Intensity Prediction Scheme Rapid Intensification Index (SHIPS-RII) probabilities for 2025 Atlantic TCs

Variables: 

•	init_time: Model initialization date and time (UTC)

•	track_id: TC ID (Automated Tropical Cyclone Forecasting System format)

•	SHIPS-RII: Probability of rapid intensification over following 24 h (percent)

•	Verification: Flag if RI was observed over following 24 h (0 indicates RI was not observed and 1 indicates RI was observed)


**3)	Other_Forecasts_2025.csv**

Model output and other forecasts used to validate and compare forecast performance for 2025 Atlantic TCs

Variables:

•	init_time: Model initialization date and time (UTC)

•	track_id: TC ID (Automated Tropical Cyclone Forecasting System format)

•	model: Model/forecast ID (FNV3 – Google DeepMind ensemble mean, HFSA – Hurricane Analysis and Forecast System version A, OFCL – NHC official forecast)

•	valid_time: Model forecast valid date and time 

•	lead_time_hours: Forecast time (hours)

•	lat: TC latitude

•	lon: TC longitude

•	maximum_sustained_wind_speed_knots: TC intensity (knots)


**4) Vile_et_al_plots.ipynb**

Jupyter Notebook containing the code used to generate figures 3 and 4 of the manuscript.

