# Clean Energy Access Prioritiser 



## Introduction

The Clean Energy Access Prioritiser (CEAP) is an open-source and open-access decision-support tool designed to identify priority areas for clean energy interventions and investments. The spatial planning tool allows users to evaluate clean energy projects with a multi-sectoral approach, including environmental, socio-economic, technical, and political aspects. 
This web-based tool allows for multi-criteria selections helping identifying priority areas (hot and cold spots) in real-time based on custom priorities. The automatic geo-processing capabilities encompass more than 30 variables, spanning aspects such as energy demand, environmental and social conditions.
The CEAP can be of interest to both institutional and private stakeholders in the energy sector, i.e. policymakers, international donors, governments, and philanthropic investors.


## CEAP variables

(This list is updated on a regular basis, as soon as a new variable is available on the tool)

**Table 1. Market supply variables: minimum/maximum values and source of information**


| Variable  | Minimum value (red) |	Maximum value (green)  | Source |
| ------------- | ------------- | ------------- | ------------- |
| Closest to the grid | Longest distance to electric grid (LV; MV; HV) per planning unit  | Shortest distance to electric grid (LV; MV; HV) per planning unit. | (Kakoulaki & Moner-Girona. 2020)|
| Farthest from the grid  | Shortest distance to electric grid (LV; MV; HV) per planning unit | Longest distance to electric grid (LV; MV; HV) per planning unit | (Kakoulaki & Moner-Girona. 2020) |
| Power plants | Lowest density of power plants per planning unit. | Highest density of power plants per planning unit.  | (Sanchez et al. 2020) |
| Solar potential	  | Lowest solar potential, measured by a long term yearly average of global horizontal irradiation in the planning unit.  | Highest solar potential, measured by a long term yearly average of global horizontal irradiation in the planning unit. |(Huld et al. 2020) |
| Wind potential  | Minimum wind resources measured by mean wind power density in the planning unit.   | Maximum wind resources measured by mean wind power density in the planning unit.  | (Global Wind Atlas. 2023) |
| Hydropower potential | Lowest hydropower potential in the planning unit.  | Highest hydropower potential in the planning unit. | (Sanchez et al. 2020) |
| Most accessible areas  | Longest accessibility time to travel to the area.  | Shortest accessibility time to travel the area. | (Weiss et al. 2015) |
| Least accessible areas | Shortest accessibility time to travel the area.  | Longest accessibility time to travel to the area. | (Weiss et al. 2015) |
| Electricity grid (existing or planned)	  | Highest density of electric lines per planning unit.  | Lowest density of electric lines per planning unit | (Kakoulaki & Moner-Girona. 2020) |


**Table 2. Market demand variables: minimum/maximum values and source of information**

| Variable                                   | Minimum value (red)                                              | Maximum value (green)                                           | Source                                                             |
| ------------------------------------------ | --------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ |
| Industrial areas                           | Planning unit is not covered by built-up surface allocated to dominant non-residential (NRES) uses | Planning unit is fully covered by built-up surface allocated to dominant non-residential (NRES) uses | (Pesaresi et al. 2020)                                             |
| Population                                 | Lowest density of residential population per planning unit       | Highest density of residential population per planning unit      | (Schiavina et al. 2023)                                            |
| Health centers                             | Lowest density of health facilities per planning unit           | Highest density of health facilities per planning unit          | (Kakoulaki & Moner-Girona. 2021)                                   |
| Educational facilities (primary and secondary) | Lowest density of educational facilities per planning unit        | Highest density of educational facilities per planning unit       | Process of publication (Moner-Girona, et al 2023)                    |
| Educational facilities without electricity (primary and secondary) | Lowest density of educational facilities lacking access to electricity per planning unit | Highest density educational facilities lacking access to electricity per planning unit | Process of publication (Moner-Girona, et al 2023) |
| Area equipped for irrigation               | Planning unit is not covered by irrigated areas                 | Planning unit is fully covered by irrigated areas               | (Siebert et al. 2013)                                               |
| Groundwater irrigation                     | Planning unit is not covered by irrigated area supplied by groundwater | Planning unit is fully covered by irrigated area supplied by groundwater | (Siebert et al. 2013)                                               |
| Livestock                                  | Lowest density of livestock per planning unit                   | Highest density of livestock per planning unit                  | (Timothy et al. 2014)                                               |


**Table 3. Environmental and climate variables: minimum/maximum values and source of information**

| Variable                                   | Minimum value (red)                                              | Maximum value (green)                                           | Source                                                             |
| ------------------------------------------ | --------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ |
| Elevation                                  | Lowest elevation per planning unit                                | Highest elevation per planning unit                              | (Rosen et al. 2007)                                                 |
| Slope                                      | Lowest slope per planning unit                                    | Highest slope per planning unit                                  | (Rosen et al. 2007)                                                 |
| Natural areas                              | Planning unit is not covered by natural areas                     | Planning unit is entirely covered by natural areas               | (Buchhorn, 2022)                                                    |
| Intact forest                              | Planning unit is not covered by Intact Forest                     | Planning unit is entirely covered by Intact Forest               | (Potapov et al. 2017)                                               |
| Protected and Conserved Areas              | Planning unit is not covered by Protected and Conserved Areas     | Planning unit is entirely covered by Protected and Conserved Areas | (UNEP-WCMC and IUCN, 2023)                                           |
| Temperature anomalies                      | Lowest variation of average global temperatures compared to a reference value in the planning unit | Highest variation of average global temperatures compared to a reference value in the planning unit | (Vose et al. 2021)                                                  |
| Drought risk                               | Planning units less likely to be affected by droughts             | Planning units most likely to be affected by droughts            | (Carrão et al. 2016)                                                |


**Table 4. Socio-political variables: minimum/maximum values and source of information**

| Variable                                   | Minimum value (red)                                              | Maximum value (green)                                           | Source                                                             |
| ------------------------------------------ | --------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------------ |
| Food security                              | Lowest vulnerability to hunger, highest food quality in the planning unit | Highest vulnerability to hunger, lowest food quality in the planning unit | (INFORM. 2023)                                                      |
| Armed conflict                             | Lowest number of political violence and protest events in the planning unit | Highest number of political violence and protest events in the planning unit | (ACLED. 2022)                                                       |
| Refugee camps                              | Lowest amount of refugee settlements in the planning unit        | Highest amount of refugee settlements in the planning unit       | (Baldi et al. 2021)                                                 |
| Connectivity                               | Lowest mobile network performance                                | Highest mobile network performance                               | (Ookla. 2022)                                                       |




____________
### Authors: 
Luca Battistella, Anna Bertelli, Magda Moner-Girona



