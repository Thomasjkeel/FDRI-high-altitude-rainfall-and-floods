# NRFA-rain-gauge-heights-vs-floods
Examples comparing the proportion of rain falling at given altitudes during/before flood events in FDRI catchments (Severn and Tweed).

## Severn catchment
[Bewdley](https://nrfa.ceh.ac.uk/data/station/info/54001) (gauge height: 18.8 m) is used as the main catchment

Compared with three high altitude sites: [Abermule](https://nrfa.ceh.ac.uk/data/station/info/54014) (86.8 m), [Dolwen](https://nrfa.ceh.ac.uk/data/station/info/54080) (147.3 m) and [Plynlimon Flume](https://nrfa.ceh.ac.uk/data/station/info/54022) (321.3 m).

Rainfall falling -10 to 0 days before event is considered

**Table 1.** *Bewdley catchment 5-flood average (see notebook for exact dates)*
| Height above sea level (m) |	Area of catchment above that height (%)	| Rainfall (%) | diff |
|------|-------|------|-------|
| 18.8 (Bewdley) | 100.00 | 100.00 | 0.00 |
| 50 | 98.47 | 98.79 | -0.32 |
| 86.8 (Abermule) | 75.25 | 81.03 | -5.78 |
| 100 | 64.00 | 72.04 | -8.04 |
| 147.3 (Dolwen) | 42.87 | 53.61 | -10.73 |
| 200 | 31.23 | 41.94 | -10.71 |
| 250 | 22.87 | 32.60 | -9.73 |
| 300 | 16.13 | 24.20 | -8.07 |
| 321.4 (Plynlimon Flume) | 13.26 | 20.41 | -7.16 |
| 350 | 10.37 | 16.49 | -6.12 |
| 400 | 6.46 | 10.91 | -4.45 |
| 450 | 3.54 | 6.28 |	-2.74 |
| 500 | 1.62 | 3.00 |	-1.38 |
| 550 | 0.76 | 1.43 |	-0.67 |
| 600 | 0.30 | 0.56 |	-0.26 |
| 650 | 0.09 | 0.17 |	-0.08 |
| 700 | 0.05 | 0.09 |	-0.04 |

### Map of example flood event
Flood events occurred on: 2008-03-17, 2008-11-11, 2012-04-30, 2013-02-15, 2020-01-15.  
More maps available under `River Severn/Figures/`
<img src="River%20Severn/Figures/fiveflood_mean_bewdley_10d_prop_rain.png" width="800">

### Compare height and area profile
<img src="River%20Severn/Figures/bewdley_all_floods_lineplot_threshold.png" width="600">


## Tweed catchment
[Norham](https://nrfa.ceh.ac.uk/data/station/info/21009) (gauge height: 46 m) is used as the main catchment

Compared with two high altitude sites: [Fruid Water](https://nrfa.ceh.ac.uk/data/station/info/21001) (297.5 m) and [Kingledores](https://nrfa.ceh.ac.uk/data/station/info/21014) (214.1 m).

Rainfall falling -10 to 0 days before event is considered

**Table 2.** *Norham catchment 5-flood average (see notebook for exact dates)*
| Height above sea level (m) |	Area of catchment above that height (%)	| Rainfall (%) | diff |
|------|-------|------|-------|
| 46 (Norham) | 100.00 | 100.00 | 0.00 |
| 50 | 96.71 | 98.51 | -1.80 |
| 100 | 86.90 | 93.54 | -6.64 |
| 150 | 76.95 | 87.36 | -10.41 |
| 200 | 65.17 | 78.51 | -13.34 |
| 214 (Kingledores) | 61.74 | 75.61 | -13.87 |
| 250 | 51.66 | 66.19 | -14.53 |
| 297.5 (Fruid Water) | 38.01 | 52.17 | -14.16 |
| 350 | 25.23 | 37.29 | -12.06 |
| 400 | 16.51 | 26.05 | -9.54 |
| 450 | 9.97 | 16.57 | -6.60 |
| 500 | 5.72 | 10.23 | -4.51 |
| 550 | 3.11 | 5.79 | -2.68 |
| 600 | 1.88 | 3.62 | -1.74 |
| 650 | 1.02 | 2.05 | -1.03 |
| 700 | 0.61 | 1.27 | -0.66 |
| 750 | 0.23 | 0.47 | -0.24 |
| 800 | 0.05 | 0.09 | -0.04 |

### Map of example flood event
Flood events occurred on: 2016-01-10, 2018-11-29, 2020-01-11, 2021-02-20, 2022-12-30.  
More maps available under `River Tweed/Figures/`
<img src="River%20Tweed/Figures/fiveflood_mean_norham_10d_prop_rain.png" width="800">

### Compare height and area profile
<img src="River%20Tweed/Figures/norham_all_floods_lineplot_threshold.png" width="600">