## Looking at the Big Picture: [SimpleAnimation](https://www.eodashboardhackathon.org/challenges/water-quality/looking-at-the-big-picture/teams/simpleanimation/project)

## Earth Observatory Dashboard Hackathon 2021 Submission

## By Jack Hester, Claudia Herbert, Nathan McCall and William Kaminski

## Overview

Our code provides an engine to access water quality imagery from <a href="https://docs.sentinel-hub.com/api/latest/data/sentinel-3-olci-l1b/">Sentinel-3</a> and true color imagery from <a href="https://docs.sentinel-hub.com/api/latest/data/sentinel-2-l1c/">Sentinel-2</a> for any geographic region, and to create animations from these images. We also provide example analysis of water quality, traffic, shipping, and lockdown data accessible that were accessible through the  <a href="https://eodashboard.org/">Earth Observatory Dashboard</a>.

A project walkthrough, including examples of our animations, can be found in our <a href="https://docs.google.com/presentation/d/1ICpBsGad9guDAPmckSQgMn7REZDlzgcKfVOhFIKhyZU/edit?usp=sharing">SimpleAnimation presentation</a>.

## Code structure

All of our code is accessible via jupyter notebooks. You can also access the individual parts of our project in the folders, which include task-specific notebooks and some related data.

- 'IseBay_WaterQuality_Cars.ipynb': Takes user input dates and returns plots and summary statistics for water quality and car activity data from Ise Bay 

- 'Ise_Bay_Nagoya_Graph.ipynb':  Read in water quality and car data and create a bar chart showing their relation to lock down periods and chlorophyll-a concentrations

- 'rgb_image_sentinel2.ipynb': Download and save true-color (rgb) imagery data from Sentinel 2 over a specified date range for any geographic area

- 'WQ_Imagery_Sentinel3.ipynb': Download and save water quality imagery from Sentinel 3 over a specified date range for any geographic area

- 'animation.ipynb': Generate a gif from downloaded imagery files

- 'raster_avg.ipynb': Get the average value of tiff imagery files; note, this is a crude average that is not representative of the true values behind the imagery

## Data sources and notes

Data csv files uploaded are originally from [EO Dashboard](https://eodashboard.org/)

Nagoya, Activity Car Density change in Nagoya Port: https://eodashboard.org/?poi=JP03-E9&indicator=E9

Ise Bay Total Suspended Matter concentration anomaly (%): https://eodashboard.org/?indicator=N3b&poi=JP06-N3b

Ise Bay, Chl-a, Water Quality Time Series, Chlorophyll-a concentration anomaly: https://eodashboard.org/?indicator=N3b&poi=JP04-N3b

Sentinel-2 L1C. (n.d.). Sentinelhub. Retrieved June 30, 2021, from https://docs.sentinel-hub.com/api/latest/data/sentinel-2-l1c/

Sentinel-3 OLCI L1B. (n.d.). Sentinelhub. Retrieved June 30, 2021, from https://docs.sentinel-hub.com/api/latest/data/sentinel-3-olci-l1b/

COVID-19 Community Mobility Report. (n.d.). COVID-19 Community Mobility Report. Retrieved June 29, 2021, from https://www.google.com/covid19/mobility?hl=en

