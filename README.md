# eodashhackathon-2021
## Looking at the Big Picture: [SimpleAnimation](https://www.eodashboardhackathon.org/challenges/water-quality/looking-at-the-big-picture/teams/simpleanimation/project)

## By Jack Hester, Claudia Herbert, William Kaminski, and Nathan McCall

## Overview

Our code provides an engine to access water quality imagery from Sentinel-3 and true color imagery from Sentinel-2 and create animations from these images. We also provide example analysis of water quality, traffic, shipping, and lockdown data accessible through the  <a href="https://eodashboard.org/)>Earth Observatory Dashboard</a>.

A project overview, including examples of our animations, can be found in our <a href="">SimpleAnimation presentation</a> [add link].

## Code structure

All of our code is accessible via the jupyter notebooks. There is a main notebook at the root level that includes all of our core code. You can also access specific portions of the code in the "notebooks" folder, which includes task-specific notebooks.


## Data sources and notes

Data csv files uploaded are originally from [EO Dashboard](https://eodashboard.org/)

Nagoya, Activity Car Density change in Nagoya Port: https://eodashboard.org/?poi=JP03-E9&indicator=E9

Ise Bay Total Suspended Matter concentration anomaly (%): https://eodashboard.org/?indicator=N3b&poi=JP06-N3b

Ise Bay, Chl-a, Water Quality Time Series, Chlorophyll-a concentration anomaly: https://eodashboard.org/?indicator=N3b&poi=JP04-N3b

Sentinel-2 L1C. (n.d.). Sentinelhub. Retrieved June 30, 2021, from https://docs.sentinel-hub.com/api/latest/data/sentinel-2-l1c/

Sentinel-3 OLCI L1B. (n.d.). Sentinelhub. Retrieved June 30, 2021, from https://docs.sentinel-hub.com/api/latest/data/sentinel-3-olci-l1b/

COVID-19 Community Mobility Report. (n.d.). COVID-19 Community Mobility Report. Retrieved June 29, 2021, from https://www.google.com/covid19/mobility?hl=en

### Markdowns: 
- 'IseBay_WaterQuality_Cars.ipynb': Markdown file that takes user input dates and returns plots and summary statistics for water quality and car activity data from Ise Bay 
