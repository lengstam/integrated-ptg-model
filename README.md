# integrated-ptg-model
A model of a power-to-gas plant integrated with wastewater treatment and co-digestion. Used and explained in "Optimising power-to-gas integration with wastewater treatment and biogas: A techno-economic assessment of CO2 and by-product utilisation" by Engstam, L., Janke, L., Sundberg, C. and Nordberg, Å. (2025) in Applied Energy, Volume 377 Part B, 124534, https://doi.org/10.1016/j.apenergy.2024.124534.

The system consists of a PEM electrolyzer, compressed hydrogen storage and a biological methanation reactor. Based on actual plant data, hydrogen is produced to upgrade biogas to biomethane through direct CO2 methanation. Process by-products (heat and oxygen) are simultaneously used to reduce energy consumption in a wastewater treatment plant. This model optimizes both annual operation on an hourly basis and system configuration to minimize production cost (levelized cost of power-to-gas).

Use by defining investigated capacity ranges for electrolyzer, hydrogen storage, methanation reactor and renewables (wind and solar) in "simulation.py" and running the script. If a single configuration is defined, more detailed information about its operation can be accessed by enabling "simulation_details" and "plots".

Note that paths to hourly data files must be changed upon download. Electricity system data is available from 2018 to 2021 and for the four Swedish electricity bidding zones (SE1-SE4). Furthermore, slightly different results may be had compared to the study above depending on the optimizer used. 
